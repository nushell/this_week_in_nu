# This week in Nushell #209


## Nushell

- IanManske [created a `Record` type](https://github.com/nushell/nushell/pull/10103)
- jntrnr [bumped to 0.84](https://github.com/nushell/nushell/pull/10093), and did some [Serde](https://github.com/nushell/nushell/pull/10061) [stuff](https://github.com/nushell/nushell/pull/10078), and [moved 'bytes' back to commands](https://github.com/nushell/nushell/pull/10051), and [Spanned Value step 1: span all value cases](https://github.com/nushell/nushell/pull/10042)
- fdncred [bumped rust-toolchain to 1.70.0](https://github.com/nushell/nushell/pull/10113), and [bumped nushell to dev version 0.84.1](https://github.com/nushell/nushell/pull/10101), and [removeed `--column` from `length` command and remove `record` processing](https://github.com/nushell/nushell/pull/10091), and [updated install/build scripts to include `--locked`](https://github.com/nushell/nushell/pull/10086), and [allowed `help` to return a `Type::Table`](https://github.com/nushell/nushell/pull/10082), and [allowed `return` to return any nushell value](https://github.com/nushell/nushell/pull/10067), and [tried to fix `into datetime` to accept more dt formats](https://github.com/nushell/nushell/pull/10063), and [enabled/updated some example tests so they work again](https://github.com/nushell/nushell/pull/10058), and [tried to document the more obscure testbin commands](https://github.com/nushell/nushell/pull/10057)
- matthias-Q [allowed for `.parq` file ending as alternative to `.parquet`](https://github.com/nushell/nushell/pull/10112)
- Hofer-Julian [added a notice to enable develop mode on Windows](https://github.com/nushell/nushell/pull/10111), and [renamed the Toolkit's `pretty-print-command`](https://github.com/nushell/nushell/pull/10110)
- rgwood [fixed watch not detecting modifications on Windows](https://github.com/nushell/nushell/pull/10109)
- ito-hiroki [fixed tab completion order of directories to be consistent with order of files](https://github.com/nushell/nushell/pull/10102)
- sholderbach [removed illegal star dependency](https://github.com/nushell/nushell/pull/10095), and [removed global clippy `-A` from `toolkit.nu`](https://github.com/nushell/nushell/pull/10073), and [removed clippy global `-A` from CI](https://github.com/nushell/nushell/pull/10072), and [polished `CONTRIBUTING`, add Rust style](https://github.com/nushell/nushell/pull/10071), and [pinned reedline to 0.23.0](https://github.com/nushell/nushell/pull/10070)
- amtoine [removed Clippy flags from the PR template](https://github.com/nushell/nushell/pull/10087), and [reverted "deprecate `--format` and `--list` in `into datetime` (#10017)"](https://github.com/nushell/nushell/pull/10055), and [made the code page optional for `std clip`](https://github.com/nushell/nushell/pull/10053)
- kubouch [removed "let config" warning](https://github.com/nushell/nushell/pull/10068), and [recursively exported constants from modules](https://github.com/nushell/nushell/pull/10049), and [simplified virtualenv testing](https://github.com/nushell/nushell/pull/10035)
- horasal [added encoding auto-detection for `decode`](https://github.com/nushell/nushell/pull/10030)
- herobs [fixed 9156 endian consistency](https://github.com/nushell/nushell/pull/9873)
- nibon7 submitted [Don't use `oldtime` feature of chrono ](https://github.com/nushell/nushell/pull/9577), and [Use built-in is_terminal instead of is_terminal::is_terminal](https://github.com/nushell/nushell/pull/9550)

## Documentation

- fdncred created [update fdncred's item + typo](https://github.com/nushell/nushell.github.io/pull/1022)
- rgwood created [Update Reilly's comments in birthday blog post](https://github.com/nushell/nushell.github.io/pull/1021)
- github-actions[bot] created [Compressed Images](https://github.com/nushell/nushell.github.io/pull/1020), and [Compressed Images](https://github.com/nushell/nushell.github.io/pull/1015)
- jntrnr created [Add Nushell birthday post](https://github.com/nushell/nushell.github.io/pull/1019)
- webwurst created [Fix typo](https://github.com/nushell/nushell.github.io/pull/1018)
- hustcer created [Refresh command docs for Nu v0.84](https://github.com/nushell/nushell.github.io/pull/1016), and [Some improvements to `make_docs.nu`](https://github.com/nushell/nushell.github.io/pull/1009), and [Update table mode config doc, fix #1007](https://github.com/nushell/nushell.github.io/pull/1008)
- sholderbach created [Sections for release notes](https://github.com/nushell/nushell.github.io/pull/1014)
- kubouch created [Break down shoutouts to separate sections](https://github.com/nushell/nushell.github.io/pull/1013), and [Add intro sentence; Change `str replace` note](https://github.com/nushell/nushell.github.io/pull/1012), and [Add export const and scope notes](https://github.com/nushell/nushell.github.io/pull/1011)
- jwarlander created [Use '--locked' in cargo install snippet for dataframe feature](https://github.com/nushell/nushell.github.io/pull/1010)
- amtoine created [Release notes for `0.84.0`](https://github.com/nushell/nushell.github.io/pull/988)

## Nu_Scripts

- AntoineSebert created [Add `dfr` before `into df` and `into nu`](https://github.com/nushell/nu_scripts/pull/585)
- siph created [init nix scripts](https://github.com/nushell/nu_scripts/pull/584)
- fj0r created [Upgraded to 0.84](https://github.com/nushell/nu_scripts/pull/583)
- sholderbach created [Script to generate the excerpt of the GH release](https://github.com/nushell/nu_scripts/pull/566)

## reedline

- sholderbach created [Bump version for 0.23 release](https://github.com/nushell/reedline/pull/626)
