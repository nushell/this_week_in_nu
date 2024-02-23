# This Week in Nushell #235

## Nushell

- fdncred [removed unused dependencies](https://github.com/nushell/nushell/pull/11938), [fixed the `debug info`](https://github.com/nushell/nushell/pull/11909) command to populate process information accurately, [enabled `last` to work with ranges](https://github.com/nushell/nushell/pull/11906), and [updated to the latest versions of reedline and rusqlite](https://github.com/nushell/nushell/pull/11878).
- devyn [replaced `debug_assert!` with `assert!`](https://github.com/nushell/nushell/pull/11937) in signature checks and [added support for closures as arguments to the `zip` command](https://github.com/nushell/nushell/pull/11924).
- ayax79 improved stability with contributions to [handle configuration panics](https://github.com/nushell/nushell/pull/11935) and [wrap the REPL in a catch_unwind to restart it upon a panic](https://github.com/nushell/nushell/pull/11860).
- WindSoilder made [stderr output improvements for failed external commands](https://github.com/nushell/nushell/pull/11914) and ensured certain commands like [open, rm, and cp don't perform globbing](https://github.com/nushell/nushell/pull/11886) when inputs are variables or string interpolations.
- dmatos2012 focused on user experience with a [fix for date formatting](https://github.com/nushell/nushell/pull/11908) according to the user's locale.
- dannou812 added [new tests and fixes for the `move` command](https://github.com/nushell/nushell/pull/11904), making it more robust.
- sholderbach embarked on a cleanup mission with [removal of unused implementations and error variants](https://github.com/nushell/nushell/pull/11903), and [updating the `roxmltree` dependency](https://github.com/nushell/nushell/pull/11876).
- lpnh [corrected keybinding names and improved formatting](https://github.com/nushell/nushell/pull/11889) in the default Nushell configuration.
- IanManske made internal improvements to how [`Value`](https://github.com/nushell/nushell/pull/11885) and [`Record`](https://github.com/nushell/nushell/pull/11810) are converted.
- kit494way improved some user commands by [splitting `commandline` into subcommands](https://github.com/nushell/nushell/pull/11877) and [fixing a panic in `seq date`](https://github.com/nushell/nushell/pull/11871).
- kubouch optimized the Nushell engine by [removing an unnecessary state clone](https://github.com/nushell/nushell/pull/11872).
- yurivict implemented [FreeBSD compatibility enhancements](https://github.com/nushell/nushell/pull/11869).
- ysthakur refined error messaging by [specifying which files were not found in `ShellError::FileNotFound`](https://github.com/nushell/nushell/pull/11868).

## Extension Improvements

- texastoland added [syntax highlighting support for the spread syntax](https://github.com/nushell/vscode-nushell-lang/pull/174).

## Documentation Updates

- PolvosMagicos provided [instructions for setting Nushell as the default shell in Kitty Terminal](https://github.com/nushell/nushell.github.io/pull/1256).
- WindSoilder corrected documentation to [accurately reflect STDOUT and STDERR in the results table](https://github.com/nushell/nushell.github.io/pull/1253).

## Nu_Scripts Developments

- AucaCoyan fixed issues with [optional argument handling in GitHub scripts](https://github.com/nushell/nu_scripts/pull/763).
- fj0r introduced [new commands](https://github.com/nushell/nu_scripts/pull/761) and [enhancements to Kubernetes-related scripts](https://github.com/nushell/nu_scripts/pull/759).
- amtoine worked on [renaming package files](https://github.com/nushell/nu_scripts/pull/701) and [splitting packages into `nu-themes` and `nu-hooks`](https://github.com/nushell/nu_scripts/pull/700) for better organization.

## reedline

- icp1994 updated [rusqlite to ensure stability](https://github.com/nushell/reedline/pull/754) and kept the SQL engine up-to-date.
>
