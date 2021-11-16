# Debugging rust-analyzer using [`rr`]

This is an example project that configured VS Code to launch rust-analyzer in the [`rr`] debugger.

You need to adjust the paths in the [`./ra`](./ra) script and in
[`.vscode/settings.json`](.vscode/settings.json) to use it.

Make sure to set `debug = 2` in rust-analyzer's `Cargo.toml`!

When uploading the trace, make sure to pass both the rust-analyzer source dir as well as the
crates.io source dir:

    ./pernosco-submit upload ~/.local/share/rr/rust-analyzer-62/ ~/dev/rust-analyzer ~/.cargo/registry

[`rr`]: https://github.com/rr-debugger/rr
