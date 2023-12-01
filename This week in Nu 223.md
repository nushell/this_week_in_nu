# This week in Nushell #223


## Nushell

- WindSoilder [added new `o>>`, `e>>`, `o+e>>` redirection operators to append output to an external file](https://github.com/nushell/nushell/pull/10764), [fixed a redirection bug](https://github.com/nushell/nushell/pull/11191), and [worked on redirection tests](https://github.com/nushell/nushell/pull/11172)
- ysthakur [implemented a spread operator for record literals](https://github.com/nushell/nushell/pull/11144)
- fdncred added an experimental `stor` family of commands for working with in-memory SQLite databases: ([1](https://github.com/nushell/nushell/pull/11170), [2](https://github.com/nushell/nushell/pull/11194)) and [added a new `ExternalResolved` syntax shape to show found externals via syntax highlighting in the repl](https://github.com/nushell/nushell/pull/11135)
- nibon7 improved error messages and validation for `str index-of`: [1](https://github.com/nushell/nushell/pull/11201), [2](https://github.com/nushell/nushell/pull/11190)
- KAAtheWiseGit [improved `input list` so it can handle more data types](https://github.com/nushell/nushell/pull/11195), and [forbidded reserved variable names as function arguments](https://github.com/nushell/nushell/pull/11169)
- cosineblast [removed file I/O from some tests that don't need it](https://github.com/nushell/nushell/pull/11182)
- IanManske [improved `nu-protocol` so docs build with all features enabled](https://github.com/nushell/nushell/pull/11180)
- drbrain [converted more ShellError variants to named fields](https://github.com/nushell/nushell/pull/11173)
- sholderbach [reverted "Adding support for Polars structs"](https://github.com/nushell/nushell/pull/11171)
- rfaulhaber [bumped `sysinfo` to 0.29.11](https://github.com/nushell/nushell/pull/11166)
- MarikaChlebowska [improved some filter commands so they preserve metadata](https://github.com/nushell/nushell/pull/11160)
- NotLebedev [improved target expansion in the `cp` command](https://github.com/nushell/nushell/pull/11152)
- sigoden [fixed spans passed to external_completer](https://github.com/nushell/nushell/pull/11008)


## Extension

- glcraft created [Syntax highlight: add "export" to "module"](https://github.com/nushell/vscode-nushell-lang/pull/166)

## Documentation

- ysthakur created [Add section on spread operator](https://github.com/nushell/nushell.github.io/pull/1160)
- stfacc created [Improve workaround for carapace ERR output](https://github.com/nushell/nushell.github.io/pull/1159)
- FMotalleb created [Update coming_from_bash.md](https://github.com/nushell/nushell.github.io/pull/1158)
- MarikaChlebowska created [Replace usage of removed `date format` with `format date` in examples](https://github.com/nushell/nushell.github.io/pull/1157)
- arnau created [Rename def-env to def --env](https://github.com/nushell/nushell.github.io/pull/1155)

## Nu_Scripts

- kjelly created [get deploy complete for ka/kl in kubernetes module](https://github.com/nushell/nu_scripts/pull/680)
- glcraft created [Add `record` module](https://github.com/nushell/nu_scripts/pull/679)
- fnuttens created [Add bat aliases](https://github.com/nushell/nu_scripts/pull/678)

## reedline

- sholderbach created [Build docs.rs docs with all features](https://github.com/nushell/reedline/pull/672)
