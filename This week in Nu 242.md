# This week in Nushell #242


## Nushell

- ayax79 made lots of dataframe improvements: [moved dataframes support to a plugin](https://github.com/nushell/nushell/pull/12220) (this is huge!), [ensured that two columns named 'index' don't exist when converting a DataFrame to a nu value](https://github.com/nushell/nushell/pull/12501), [added a short flag -c to `polars append`](https://github.com/nushell/nushell/pull/12487), [handled relative paths correctly on polars `to-(parquet|jsonl|arrow|etc)`](https://github.com/nushell/nushell/pull/12486), [displayed span information, creation time, and size with `polars ls`](https://github.com/nushell/nushell/pull/12472), and [showed full help when running the `polars` command](https://github.com/nushell/nushell/pull/12462)
- devyn [switched the CI to use macOS-13 instead of macOS-latest, due to failures](https://github.com/nushell/nushell/pull/12493), [added a `GetSpanContents` engine call](https://github.com/nushell/nushell/pull/12439), [isolated tests from user config](https://github.com/nushell/nushell/pull/12437), and [added a `--no-newline` option to `nu`](https://github.com/nushell/nushell/pull/12410)
- fdncred [bumped Nushell to latest reedline](https://github.com/nushell/nushell/pull/12497), introduced [better logging for the `shell_integration` setting](https://github.com/nushell/nushell/pull/12494), and aimed [to be a bit more precise with REPL logging](https://github.com/nushell/nushell/pull/12449)
- sholderbach [fixed up plugin CI for macOS](https://github.com/nushell/nushell/pull/12495), [bumped version to `0.92.3`](https://github.com/nushell/nushell/pull/12476), [bumped our Rust version to stable](https://github.com/nushell/nushell/pull/12471), and [updated MSRV following `rust-toolchain.toml`](https://github.com/nushell/nushell/pull/12455)
- IanManske [updated `kill` to return a single value instead of a stream](https://github.com/nushell/nushell/pull/12480), did a [`drop` refactor](https://github.com/nushell/nushell/pull/12479), [refactored `first` and `last`](https://github.com/nushell/nushell/pull/12478), [mentioned `print` in the `echo` help text](https://github.com/nushell/nushell/pull/12436), and [renamed `IoStream` to `OutDest`](https://github.com/nushell/nushell/pull/12433)
- amtoine [fixed `std log`](https://github.com/nushell/nushell/pull/12470)
- WindSoilder [forced `timeit` to not capture stdout](https://github.com/nushell/nushell/pull/12465), and [made `ls` and `du` support rest parameters](https://github.com/nushell/nushell/pull/12327)
- singh-priyank [fixed a bug with negative file sizes for `into filesize`](https://github.com/nushell/nushell/pull/12443)
- oornaque [fixed typo in help stor import](https://github.com/nushell/nushell/pull/12442)
- texastoland [lexed whitespace in input-output types](https://github.com/nushell/nushell/pull/12339), and [ensured `currently_parsed_cwd` is set for config files](https://github.com/nushell/nushell/pull/12338)

## Documentation

- devyn [posted release notes for 0.92.2](https://github.com/nushell/nushell.github.io/pull/1348)
- intellild [provided an ssh agent workaround for keychain](https://github.com/nushell/nushell.github.io/pull/1347)
- kubouch [updated the 2024-04-09-art-contest-summary](https://github.com/nushell/nushell.github.io/pull/1346) and [added an art contest showcase blog](https://github.com/nushell/nushell.github.io/pull/1344)
- github-actions[bot] [compressed images](https://github.com/nushell/nushell.github.io/pull/1345)
- sophiajt [fixed deadnames and updated contact info](https://github.com/nushell/nushell.github.io/pull/1343)

## Nu_Scripts

- Zuruuh [added composer completions](https://github.com/nushell/nu_scripts/pull/817)
- MilesCranmer [fixed: prefix conda commands with `conda`](https://github.com/nushell/nu_scripts/pull/816), and [fixed non-exported completions](https://github.com/nushell/nu_scripts/pull/815)
- ehdevries [panache-git: stopped printing stderr from Git commands](https://github.com/nushell/nu_scripts/pull/813)
- csc530 [added missing scoop completions](https://github.com/nushell/nu_scripts/pull/812), and [added windows compatibility for command not found hook](https://github.com/nushell/nu_scripts/pull/811)

## reedline

- fdncred [added bashism `!term` to prefix search for the last command beginning with `term`](https://github.com/nushell/reedline/pull/779)
