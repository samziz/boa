# Boa

[![Build Status][build_badge]][build_link]
[![codecov](https://codecov.io/gh/samziz/boa/branch/master/graph/badge.svg)](https://codecov.io/gh/boa-dev/boa)
[![](http://meritbadge.herokuapp.com/boa)](https://crates.io/crates/boa)
[![](https://docs.rs/Boa/badge.svg)](https://docs.rs/Boa/)

This is an experimental JavaScript lexer, parser, and compiler written in Rust.
Currently, it has support for some of the language.

## Running

### With `cargo install`

- Clone this repo.
- Run with `cargo run -- test.js` where `test.js` is an existing JS file.
- If any JS doesn't work then it's a bug. Please raise an issue!

### Installing

- `cd` into `boa_cli`.
- Run `cargo install --path .`.

### Profiling

See [Profiling](./docs/profiling.md).

### Online sandbox (using WASM)

There is a sandbox [here](https://boa-dev.github.io/boa/). You can get more verbose errors when running from the command line.

### Debugging

Check [debugging.md](./docs/debugging.md) for more info on debugging.

### Benchmarks

See [Benchmarks](https://boa-dev.github.io/boa/dev/bench/).

## Contributing

Please, check the [CONTRIBUTING.md](CONTRIBUTING.md) file to know how to
contribute in the project. You will need Rust installed and an editor. We have
some configurations ready for VSCode.

You can check the internal development docs at <https://boa-dev.github.io/boa/doc>.

## License

This project is licensed under the [Unlicense](./LICENSE-UNLICENSE) or [MIT](./LICENSE-MIT) licenses, at your option.
