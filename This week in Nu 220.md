# This week in Nushell #220


## Nushell

- CAD97  [limited `run-external --redirect-combine sh` test to not(Windows)](https://github.com/nushell/nushell/pull/10905), and [improved case insensitivity consistency](https://github.com/nushell/nushell/pull/10884)
- IanManske [refactored the `flatten` command](https://github.com/nushell/nushell/pull/11017), [added an `exec` command for Windows](https://github.com/nushell/nushell/pull/11001), [refactored `Closure` captures to use `Vec`](https://github.com/nushell/nushell/pull/10940), [refactored env conversion to eliminate `Value::follow_cell_path_not_from_user_input`](https://github.com/nushell/nushell/pull/10926), [refactored to use `Record::get` instead of `Value` functions](https://github.com/nushell/nushell/pull/10925), and [refactored `drop columns` to fix issues](https://github.com/nushell/nushell/pull/10903)
- sholderbach [refactored `transpose` and improve perf](https://github.com/nushell/nushell/pull/11013), [added `Record::truncate` for trimming based on len](https://github.com/nushell/nushell/pull/11004), [added `Record::drain` to take out elements by range](https://github.com/nushell/nushell/pull/11002), [refactored `table` cmd and `nu-table` with Record API](https://github.com/nushell/nushell/pull/10930), [refactored `find` in terms of clean `Record` API](https://github.com/nushell/nushell/pull/10929), [used record API in more parts of `nu-protocol`](https://github.com/nushell/nushell/pull/10928), [used `Record`'s public API in a bunch of places](https://github.com/nushell/nushell/pull/10927), and [refactored+fixed `Config`<->`Value` mechanism](https://github.com/nushell/nushell/pull/10896)
- hustcer [fixed the Alpine docker file](https://github.com/nushell/nushell/pull/10992)
- drbrain [converted ShellError::DatetimeParseError to named fields](https://github.com/nushell/nushell/pull/10991), [matched toolkit clippy settings to CI clippy settings](https://github.com/nushell/nushell/pull/10984), [converted ShellError::UnsupportedInput to named fields](https://github.com/nushell/nushell/pull/10971), [restored test_config tests](https://github.com/nushell/nushell/pull/10954), [showed plugin extra usage and search terms](https://github.com/nushell/nushell/pull/10952), and [updated description and error types for `split-by`](https://github.com/nushell/nushell/pull/10865)
- fdncred [allowed vscode-specific ansi escape sequence to set path](https://github.com/nushell/nushell/pull/10990), [allowed `items` to properly evaluate block settings](https://github.com/nushell/nushell/pull/10980), [updated an `items` example to send data through the pipeline](https://github.com/nushell/nushell/pull/10976), [removed unnecessary files](https://github.com/nushell/nushell/pull/10966), [updated `trash` dependency to 3.1.2](https://github.com/nushell/nushell/pull/10965), and [added the color-backtrace crate for more intuitive backtraces](https://github.com/nushell/nushell/pull/10942)
- KAAtheWiseGit [added a special error case for `alias`](https://github.com/nushell/nushell/pull/10975), [fixed issues with `error make` refactor](https://github.com/nushell/nushell/pull/10950)
- dzorya created [a better help message for MissingPositional error](https://github.com/nushell/nushell/pull/10949)
- ayax79 [added support for Polars structs](https://github.com/nushell/nushell/pull/10943)

## Documentation

- wanesty created [Cookbook ssh agent - alternatives fixing zombie agents](https://github.com/nushell/nushell.github.io/pull/1138)
- cosineblast created [Add Pipelines section about stdout output](https://github.com/nushell/nushell.github.io/pull/1137)
- noverby created [Add Argument Type Interpretation to Scripts](https://github.com/nushell/nushell.github.io/pull/1136)
- stfacc created [Add instructions to change default shell for GNOME Console](https://github.com/nushell/nushell.github.io/pull/1134)
- amtoine created [update the Direnv section in the cookbook](https://github.com/nushell/nushell.github.io/pull/1119)

## Nu_Scripts

- fnuttens created [Add git aliases](https://github.com/nushell/nu_scripts/pull/660), and [Add git push origin --delete aliases](https://github.com/nushell/nu_scripts/pull/659)
- fj0r created [shift_alt_e to switch cwdhist history mode](https://github.com/nushell/nu_scripts/pull/658), and [change cwdhist_menu layout to `list`](https://github.com/nushell/nu_scripts/pull/657), and [cwdhist: alternative to zoxide](https://github.com/nushell/nu_scripts/pull/656)

## reedline

- fdncred created [don't allow certain examples to compile without their features](https://github.com/nushell/reedline/pull/658)
- LevitatingBusinessMan created [re-enable bracketed paste on not(windows) (fixes #9944) (fixes #648)](https://github.com/nushell/reedline/pull/657)
