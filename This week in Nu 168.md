# This week in Nushell #168


## Nushell

- jt [added additional assignment operators](https://github.com/nushell/nushell/pull/7102), and [Add support for while loops](https://github.com/nushell/nushell/pull/7101), and [Allow field assignment into the env variable](https://github.com/nushell/nushell/pull/7099), and [Update README re: typechecking](https://github.com/nushell/nushell/pull/7094), and [Fix environment conversions](https://github.com/nushell/nushell/pull/7092), and [Limited mutable variables](https://github.com/nushell/nushell/pull/7089), and [Convert 'for' to a statement](https://github.com/nushell/nushell/pull/7086), and [Split blocks and closures](https://github.com/nushell/nushell/pull/7075), and [Turn off foreground processes on macOS](https://github.com/nushell/nushell/pull/7068), and [bump to 0.71, use 1.63 toolchain](https://github.com/nushell/nushell/pull/7061)
- denstiny [fixed (#7097): let-env should not be able to set PWD](https://github.com/nushell/nushell/pull/7100)
- rgwood [improved `rm` error message when file not found](https://github.com/nushell/nushell/pull/7098), and [Remove --separator from `seq date`](https://github.com/nushell/nushell/pull/7096), and [Fix CI failures after PR merge conflicts](https://github.com/nushell/nushell/pull/7072), and [Simplify `seq char`](https://github.com/nushell/nushell/pull/7054), and [Make seq output type consistent (by removing flags)](https://github.com/nushell/nushell/pull/7045), and [Require input for `date format`](https://github.com/nushell/nushell/pull/7043), and [Remove --predicate flag from `find`](https://github.com/nushell/nushell/pull/7042), and [Require column name(s) in `sort-by`](https://github.com/nushell/nushell/pull/7041), and [Proposal: Remove the sqlparser SQLite commands](https://github.com/nushell/nushell/pull/7040)
- fdncred [fixed plugin detection in help commands](https://github.com/nushell/nushell/pull/7088), and [add commented out mold linker usage](https://github.com/nushell/nushell/pull/7081), and [use path.try_exist() to fix silent errors](https://github.com/nushell/nushell/pull/7069), and [bump to dev release 0.71.1](https://github.com/nushell/nushell/pull/7064), and [return value::int instead of value::record in `history session`](https://github.com/nushell/nushell/pull/7049), and [Revert "Fix for escaping backslashes in interpolated strings (fixes #6737)"](https://github.com/nushell/nushell/pull/7038)
- dandavison [fixed command_type classification](https://github.com/nushell/nushell/pull/7074), and [Collapse some `help commands` columns into a single column](https://github.com/nushell/nushell/pull/7052), and [Add accidentally missing tests of some command examples ](https://github.com/nushell/nushell/pull/7035), and [Add an expected result to date format test](https://github.com/nushell/nushell/pull/7031), and [Declare input and output types of commands](https://github.com/nushell/nushell/pull/6796)
- dmatos2012 [fixed overflow on negative bytes](https://github.com/nushell/nushell/pull/7070)
- webbedspace [replaced all instances of 'column path' in `help` messages with 'cell path'](https://github.com/nushell/nushell/pull/7063), and [Add `help` warnings for `path exists` and `path type` regarding usage](https://github.com/nushell/nushell/pull/7062), and [Fixed $in in `where` blocks](https://github.com/nushell/nushell/pull/6976)
- raccmonteiro created [command `open` returns error when does not have parameters (#7048)](https://github.com/nushell/nushell/pull/7058), and [Type validation for `headers` command (#6918)](https://github.com/nushell/nushell/pull/7047)
- sholderbach [pinned reedline to `0.14.0` release](https://github.com/nushell/nushell/pull/7050), and [Make the example names unique across workspace](https://github.com/nushell/nushell/pull/7046), and [Update reedline](https://github.com/nushell/nushell/pull/7023), and [Make example binaries proper cargo examples](https://github.com/nushell/nushell/pull/7019)
- 1Kinoti [added some search-terms to the `platform` category](https://github.com/nushell/nushell/pull/7021)
- gavinfoley [fixed for escaping backslashes in interpolated strings (fixes #6737)](https://github.com/nushell/nushell/pull/7020)
- kubouch [updated contributing guide and PR template](https://github.com/nushell/nushell/pull/7008)
- WindSoilder created [Dependency update: update polar to 0.25](https://github.com/nushell/nushell/pull/6988), and [make `take` behave like `first`](https://github.com/nushell/nushell/pull/6893)
- PerBothner created [New "display_output" hook.](https://github.com/nushell/nushell/pull/6915)
- nibon7 [fixed ignore-errors for select](https://github.com/nushell/nushell/pull/6896)

## Extension

- melMass created [fix: ⚡️ add path for arm brew](https://github.com/nushell/vscode-nushell-lang/pull/68)

## Documentation


- hustcer created [Refresh commands docs for nu v0.71](https://github.com/nushell/nushell.github.io/pull/669)
- hbt created [fix 404 link](https://github.com/nushell/nushell.github.io/pull/668)
- kubouch created [Add review process change](https://github.com/nushell/nushell.github.io/pull/664)
- webbedspace created [Fix let-env Path example to be accurate for Windows](https://github.com/nushell/nushell.github.io/pull/663), and [Update types_of_data.md](https://github.com/nushell/nushell.github.io/pull/661), and [Updated working_with_strings.md (closes #640)](https://github.com/nushell/nushell.github.io/pull/660)
- PerBothner created [Document display_output hook](https://github.com/nushell/nushell.github.io/pull/662)
- sholderbach created [Release notes for nushell 0.71](https://github.com/nushell/nushell.github.io/pull/647)


## Nu_Scripts


- taooceros created [Fix undetected windows enviroment](https://github.com/nushell/nu_scripts/pull/312)


## reedline


- sholderbach created [Use `Box::default()` in more places](https://github.com/nushell/reedline/pull/512), and [Prepare the `0.14.0` release](https://github.com/nushell/reedline/pull/511)
- perlindgren created [Custom validator and prompt code examples](https://github.com/nushell/reedline/pull/500)

