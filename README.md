
[<img alt="crates.io" src="https://img.shields.io/crates/v/timestampvm.svg?style=for-the-badge&color=fc8d62&logo=rust" height="20">](https://crates.io/crates/timestampvm)
[<img alt="docs.rs" src="https://img.shields.io/badge/docs.rs-timestampvm-66c2a5?style=for-the-badge&labelColor=555555&logo=docs.rs" height="20">](https://docs.rs/timestampvm)
[<img alt="build status" src="https://img.shields.io/github/workflow/status/ava-labs/timestampvm-rs/CI/main?style=for-the-badge" height="20">](https://github.com/ava-labs/timestampvm-rs/actions?query=branch%3Amain)

# timestampvm-rs

Timestamp VM in Rust

See [`tests/e2e`](tests/e2e) for full end-to-end tests.

## Example

```bash
./scripts/build.release.sh

NETWORK_RUNNER_SKIP_SHUTDOWN=1 \
VM_PLUGIN_PATH=$(pwd)/target/release/timestampvm \
./scripts/tests.e2e.sh

VM_PLUGIN_PATH=$(pwd)/target/release/timestampvm \
./scripts/tests.e2e.sh
```
