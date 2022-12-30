# This week in Nushell #175


## Nushell

- kubouch [expanded Nushell's help system](https://github.com/nushell/nushell/pull/7611)
- sholderbach [fixed quoting of empty string in `to nuon`](https://github.com/nushell/nushell/pull/7632), and [Update `Cargo.lock` to `powierza-coefficient 1.0.2`](https://github.com/nushell/nushell/pull/7629), and [Fix the syntax highlighting in `help metadata`](https://github.com/nushell/nushell/pull/7628), and [Fix usage of deprecated C-style logical `and`](https://github.com/nushell/nushell/pull/7627), and [Include clippy check for dataframe in CI](https://github.com/nushell/nushell/pull/7596), and [Further cleanup of `Span::test_data` usage + span fixes](https://github.com/nushell/nushell/pull/7595)
- jaudiger [corrected some really tiny typos.](https://github.com/nushell/nushell/pull/7635)
- webbedspace made [slight edits to `ls` and `zip`'s help text](https://github.com/nushell/nushell/pull/7626), and [disallowed `^` in `def` command names](https://github.com/nushell/nushell/pull/7606), and [Add extra_usage messages for subcommand-only commands](https://github.com/nushell/nushell/pull/7594), and [`columns` now errors when given a non-record non-table](https://github.com/nushell/nushell/pull/7593), and [Change instances of `Value::string("foo", Span::test_data())` to `Value::test_string("foo")`](https://github.com/nushell/nushell/pull/7592)
- micouy [updated `powierza-coefficient` to `1.0.2`](https://github.com/nushell/nushell/pull/7625)
- fdncred [added `--mime-type(-m)` to `ls` in the `type` column](https://github.com/nushell/nushell/pull/7616)
- hustcer [fixed const examples](https://github.com/nushell/nushell/pull/7610), and [Fix an example of `env` command](https://github.com/nushell/nushell/pull/7603)
- Mehrbod2002 implemented [Allow Number and Boolean type to be key in `from yaml`](https://github.com/nushell/nushell/pull/7607), and [Fix #6888 and rename `fill-na` to `fill-nan`](https://github.com/nushell/nushell/pull/7565)
- zhiburt [fixed table expand wrap in case no header is there](https://github.com/nushell/nushell/pull/7605), and [Fix some issues with table wrapping of lists](https://github.com/nushell/nushell/pull/7598)
- kianmeng [fixed typos by codespell](https://github.com/nushell/nushell/pull/7600)
- WindSoilder [fixed a python plugin example](https://github.com/nushell/nushell/pull/7599)
- NotLebedev created a [to toml fix](https://github.com/nushell/nushell/pull/7597)
- rgwood [fixed an error message when interrupting table with `ctrl+c`](https://github.com/nushell/nushell/pull/7588)


## Documentation

- hustcer [refreshed docs for v0.73](https://github.com/nushell/nushell.github.io/pull/717), and [Fix book/make_docs.nu for nu v0.73+](https://github.com/nushell/nushell.github.io/pull/716)
- kubouch [added an image; Fmt](https://github.com/nushell/nushell.github.io/pull/718)
- sholderbach [fixed styling on 0.73 release notes](https://github.com/nushell/nushell.github.io/pull/714)

## Nu_Scripts


- fdncred created [update coloring scripts with newer syntax](https://github.com/nushell/nu_scripts/pull/336), and [update 20k script with save changes](https://github.com/nushell/nu_scripts/pull/335), and [update sparkline script](https://github.com/nushell/nu_scripts/pull/334)
- skelly37 created [Fix `dict` and `cdpath` for 0.73](https://github.com/nushell/nu_scripts/pull/333)
