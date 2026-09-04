# Axum Auth
This is a demo project showing how to handle user auth via JWT tokens using Axum (web framework for Rust) for REST APIs.

## Prerequisites
- [Rust](https://rust-lang.org/tools/install/)
- [Docker](https://docs.docker.com/desktop/)
- SQLx CLI

## Installing SQLx CLI
Only need to download the Postgres features:
```
cargo install sqlx-cli --no-default-features --features native-tls,postgres
```

## Scripts
- `cargo fmt` &nbsp; runs formatter
- `cargo fmt -- --check` &nbsp; checks formatting
- `cargo clippy` &nbsp; runs linter
- `cargo build` &nbsp; compiles code in dev mode
- `cargo build --release` &nbsp; compiles code for release
- `cargo run` &nbsp; compiles code in dev mode and starts server
- `cargo run --release` &nbsp; compiles code for release and starts server