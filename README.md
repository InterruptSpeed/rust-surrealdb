# rust-surrealdb

follow-along of [SurrealDB - Rust Embedded Database - Quick Tutorial](https://www.youtube.com/watch?v=iOyvum0D3LM) by [Jeremy Chone](https://www.youtube.com/c/JeremyChone)

## code status

[![CI](https://github.com/InterruptSpeed/rust-surrealdb/actions/workflows/main.yml/badge.svg)](https://github.com/InterruptSpeed/rust-surrealdb/actions/workflows/main.yml)

## config

```
cargo install cargo-watch
cargo new rust-surrealdb
cd rust-surrealdb
cargo add tokio --features full
cargo add anyhow surrealdb
cargo watch -q -c -x "run -q"
```

## extras

- in VS Code enable fmt on save in Settings->Editor
- consider the ThunderClient extension for VSCode

## surrealdb on macos w/ homebrew

```
brew install surrealdb/tap/surreal
surreal start --user root --pass root --log debug memory
```