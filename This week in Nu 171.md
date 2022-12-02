# This week in Nushell #171


## Nushell

- zhiburt created a new [`less` like pager](https://github.com/nushell/nushell/pull/6984) and [Deliver a few fixes for `explore` command](https://github.com/nushell/nushell/pull/7310), and 
- raccmonteiro created a new [`uniq-by` command](https://github.com/nushell/nushell/pull/7295)
- dmatos2012 [allowed tables in the ++ operator](https://github.com/nushell/nushell/pull/7051)
- fdncred [added a `:q!` alias to explore command](https://github.com/nushell/nushell/pull/7326), and [fix `cal` input_output_types signature](https://github.com/nushell/nushell/pull/7306), and [bump to dev release v0.72.1](https://github.com/nushell/nushell/pull/7281), and [add comments to release-pkg for manual running](https://github.com/nushell/nushell/pull/7277), and [update release-pkg.nu to include more recent less version](https://github.com/nushell/nushell/pull/7265), and [fix dfr datetime conversion](https://github.com/nushell/nushell/pull/7264), and [add a more verbose description of operators](https://github.com/nushell/nushell/pull/7263), and [add `help operators` command](https://github.com/nushell/nushell/pull/7254), and [pin to rust v1.65](https://github.com/nushell/nushell/pull/7249), and [add `into record` command](https://github.com/nushell/nushell/pull/7225)
- webbedspace [edited help text and examples in `explore` for readability](https://github.com/nushell/nushell/pull/7324), and [Rename `$env.config.explore_config` to `$env.config.explore` (for consistency with `$env.config.ls`, `$env.config.table` etc.)](https://github.com/nushell/nushell/pull/7317), and [Add `-n` flag to `sort` (formerly only available on `sort-by`)](https://github.com/nushell/nushell/pull/7293)
- rgwood [fixed the handling of mixed LF+CRLF in `lines`](https://github.com/nushell/nushell/pull/7316), and [Handle `ctrl-c` in `RawStream` iterator](https://github.com/nushell/nushell/pull/7314), and [Clean up .sh scripts with shellcheck](https://github.com/nushell/nushell/pull/7261), and [Upgrade `windows` and `trash` crates](https://github.com/nushell/nushell/pull/7259)
- hustcer [used setup-rust-toolchain for release workflow](https://github.com/nushell/nushell/pull/7315), and [Remove inactive actions-rs/toolchain@v1.0.6 for release workflow](https://github.com/nushell/nushell/pull/7302), and [Update release script to nu v0.71 and use ubuntu-20.04 to build nu binary](https://github.com/nushell/nushell/pull/7290)
- kubouch [fixed the where -b flag](https://github.com/nushell/nushell/pull/7313)
- jntrnr made [a couple minor updates to xml deps](https://github.com/nushell/nushell/pull/7311), and [Simple README updates](https://github.com/nushell/nushell/pull/7279), and [bump to 0.72](https://github.com/nushell/nushell/pull/7272), and [Clean up keyword lines in help](https://github.com/nushell/nushell/pull/7243)
- sholderbach [added a deprecation note for removed `build-string`](https://github.com/nushell/nushell/pull/7307), and [Fix failing test after #7051](https://github.com/nushell/nushell/pull/7299), and [Remove unused dev-dependencies](https://github.com/nushell/nushell/pull/7285), and [Implement more math commands (e.g. trig, ln)](https://github.com/nushell/nushell/pull/7258), and [Suggest using float on `Value::Int` overflow](https://github.com/nushell/nushell/pull/7253), and [Add did-you-mean suggestions for bitwise ops](https://github.com/nushell/nushell/pull/7252), and [Add did-you-mean suggestions for operators](https://github.com/nushell/nushell/pull/7251), and [Add logical `xor` operator](https://github.com/nushell/nushell/pull/7242)
- WindSoilder [fixed try for external command runs to failed](https://github.com/nushell/nushell/pull/7300), and [make histogram sorted](https://github.com/nushell/nushell/pull/7267), and [add -f, --force for save command](https://github.com/nushell/nushell/pull/7262)
- Decodetalkers [updated chrono](https://github.com/nushell/nushell/pull/7132)
- bgeron created [Fix documentation for merge](https://github.com/nushell/nushell/pull/7329)

## Extension

- fdncred [updated the extension for nushell 0.72](https://github.com/nushell/vscode-nushell-lang/pull/70)

## Documentation

- WindSoilder [added a command signature section](https://github.com/nushell/nushell.github.io/pull/671)
- Kissaki [fixed typo in 0.71 release notes](https://github.com/nushell/nushell.github.io/pull/692)
- raccmonteiro [fixed a typo](https://github.com/nushell/nushell.github.io/pull/691)
- fdncred [updated a closure syntax example](https://github.com/nushell/nushell.github.io/pull/688)
- sholderbach [fixed tip boxes in `book/custom_commands.md`](https://github.com/nushell/nushell.github.io/pull/686), and [Autoformat book/types_of_data.md](https://github.com/nushell/nushell.github.io/pull/685), and [Fix octal literal mentions](https://github.com/nushell/nushell.github.io/pull/684), and [Update operator docs](https://github.com/nushell/nushell.github.io/pull/683)
- rgwood [updated docs for dataframe+database feature change](https://github.com/nushell/nushell.github.io/pull/679), and [v0.72 blog post](https://github.com/nushell/nushell.github.io/pull/666)
- webbedspace [added config.nu structure changes](https://github.com/nushell/nushell.github.io/pull/675)

## Nu_Scripts

- Decodetalkers created [feat: add example for starship and shell_space](https://github.com/nushell/nu_scripts/pull/320)
- WindSoilder created [fix merge doesnt support block input](https://github.com/nushell/nu_scripts/pull/318)


## reedline

- jmoore34 created [Make DefaultPrompt configurable](https://github.com/nushell/reedline/pull/519)
