# just-func-rust

[![crates.io](https://img.shields.io/crates/v/just-func.svg)](https://crates.io/crates/just-func)
[![docs.rs](https://docs.rs/just-func/badge.svg)](https://docs.rs/just-func)
[![pull-request](https://github.com/justland/just-func-rust/actions/workflows/pull-request.yml/badge.svg)](https://github.com/justland/just-func-rust/actions/workflows/pull-request.yml)

Rust implementation of [just-func](https://github.com/justland/just-func).

## Verify

These are the same checks CI runs, in the same order:

```sh
cargo fmt --all --check
cargo clippy --workspace --all-targets --all-features -- -D warnings
cargo test --workspace --all-features
```

## Recommended setup

- <https://github.com/rust-lang/rust-clippy>
- <https://github.com/xd009642/tarpaulin>

## License

[MIT](./LICENSE)
