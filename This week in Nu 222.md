# This week in Nushell #222

## Nushell

- WindSoilder [made it possible to pass switch values dynamically](https://github.com/nushell/nushell/pull/11057), and [improved redirection so it supports redirecting stderr while piping stdout to the next command](https://github.com/nushell/nushell/pull/10851)
- ysthakur created [a spread operator for list literals](https://github.com/nushell/nushell/pull/11006)
- amtoine [deprecated `std clip`](https://github.com/nushell/nushell/pull/11097), and [removed `def-env` and `export def-env`](https://github.com/nushell/nushell/pull/10999)
- hustcer made lots of fixes to the release workflows: [1](https://github.com/nushell/nushell/pull/11146), [2](https://github.com/nushell/nushell/pull/11145), [3](https://github.com/nushell/nushell/pull/11121)
- drbrain did several internal refactorings to help with error messages ([1](https://github.com/nushell/nushell/pull/11126), [2](https://github.com/nushell/nushell/pull/11125), [3](https://github.com/nushell/nushell/pull/11124), [4](https://github.com/nushell/nushell/pull/11123), [5](https://github.com/nushell/nushell/pull/11120), [6](https://github.com/nushell/nushell/pull/11119), [7](https://github.com/nushell/nushell/pull/11118), [8](https://github.com/nushell/nushell/pull/11094), [9](https://github.com/nushell/nushell/pull/11093), [10](https://github.com/nushell/nushell/pull/10983)) and [added a new `is-terminal` command to determine if stdin/out/err are a terminal](https://github.com/nushell/nushell/pull/10970)
- sholderbach [moved more commands to the opaque `Record` type](https://github.com/nushell/nushell/pull/11122), [bumped `procfs` to 0.16.0](https://github.com/nushell/nushell/pull/11115), [bumped the Nu version to `0.87.2`](https://github.com/nushell/nushell/pull/11114), and [used the new record API in `describe --detailed`](https://github.com/nushell/nushell/pull/11075), and [improved developer documentation](https://github.com/nushell/nushell/pull/11052)
- danielsomerfield [fixed the toolkit to run for the whole workspace on 'check pr'](https://github.com/nushell/nushell/pull/11112)
- IanManske [refactored `Value` cell path functions to fix bugs](https://github.com/nushell/nushell/pull/11066)
- tskinn [added a new `mktemp` command](https://github.com/nushell/nushell/pull/11005)
- MarikaChlebowska [added a more descriptive error message when passing a list to `from_csv`](https://github.com/nushell/nushell/pull/10962)

## Documentation

- Ktoks created [Update creating_errors.md](https://github.com/nushell/nushell.github.io/pull/1154)
- sholderbach created [Clean up contributor book](https://github.com/nushell/nushell.github.io/pull/1153)
- ppenguin created [Add `parse` examples to *Parsing*](https://github.com/nushell/nushell.github.io/pull/1152)
- arnau created [Unifies all cookbook codeblocks to use the same style.](https://github.com/nushell/nushell.github.io/pull/1151), and [Add a cookbook comparing jq and nushell](https://github.com/nushell/nushell.github.io/pull/1150)
- 132ikl created [Add a snippet to suggest using the ? operator for environmental variables](https://github.com/nushell/nushell.github.io/pull/1142)

## Nu_Scripts

- amtoine created [add `clip` from standard library](https://github.com/nushell/nu_scripts/pull/674)
- WindSoilder created [Using def --env instead of def-env](https://github.com/nushell/nu_scripts/pull/673)
- fj0r created [rename `cmd parse` to `argx` to improve importing](https://github.com/nushell/nu_scripts/pull/671)
