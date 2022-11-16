# rust-surrealdb

follow-along of [SurrealDB - Rust Embedded Database - Quick Tutorial](https://www.youtube.com/watch?v=iOyvum0D3LM) by [Jeremy Chone](https://www.youtube.com/c/JeremyChone)

## config

```
cargo install cargo-watch
cargo new rust-surrealdb
cd rust-surrealdb
cargo add tokio --features full
cargo add anyhow surrealdb
cargo watch -q -c -x "run -q"
```

in VS Code enable fmt on save in Settings->Editor