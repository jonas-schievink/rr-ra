# Debugging rust-analyzer using [`rr`]

This is an example project that configured VS Code to launch rust-analyzer in the [`rr`] debugger.

You need to adjust the paths in the [`./ra`](./ra) script and in
[`.vscode/settings.json`](.vscode/settings.json) to use it.

Make sure to set `debug = 2` in rust-analyzer's `Cargo.toml`!

[`rr`]: https://github.com/rr-debugger/rr
