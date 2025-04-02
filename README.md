<div align="center">

# alacritty_vello

A library for working for using alacritty terminal support with Vello.

[![dependency status](https://deps.rs/repo/github/endoli/alacritty_vello/status.svg)](https://deps.rs/repo/github/endoli/alacritty_vello)
[![Apache 2.0 or MIT license.](https://img.shields.io/badge/license-Apache--2.0_OR_MIT-blue.svg)](#license)
[![Build status](https://github.com/endoli/alacritty_vello/workflows/CI/badge.svg)](https://github.com/endoli/alacritty_vello/actions)
[![Crates.io](https://img.shields.io/crates/v/alacritty_vello.svg)](https://crates.io/crates/alacritty_vello)
[![Docs](https://docs.rs/alacritty_vello/badge.svg)](https://docs.rs/alacritty_vello)

</div>

## Minimum supported Rust Version (MSRV)

This version of alacritty_vello has been verified to compile with **Rust 1.81** and later.

Future versions of alacritty_vello might increase the Rust version requirement.
It will not be treated as a breaking change and as such can even happen with small patch releases.

<details>
<summary>Click here if compiling fails.</summary>

As time has passed, some of alacritty_vello's dependencies could have released versions with a higher Rust requirement.
If you encounter a compilation issue due to a dependency and don't want to upgrade your Rust toolchain, then you could downgrade the dependency.

```sh
# Use the problematic dependency's name and version
cargo update -p package_name --precise 0.1.1
```
</details>

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution

Contributions are welcome by pull request. The [Rust code of conduct] applies.
Please feel free to add your name to the [AUTHORS] file in any substantive pull request.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be licensed as above, without any additional terms or conditions.

[Rust Code of Conduct]: https://www.rust-lang.org/policies/code-of-conduct
[AUTHORS]: ./AUTHORS
