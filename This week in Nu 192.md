# This week in Nushell #192


## Nushell

- zhiburt [fixed #9038](https://github.com/nushell/nushell/pull/9042), and [Bump `tabled` dependency to 0.11](https://github.com/nushell/nushell/pull/8922)
- amtoine [fixed: filter the `std help ...` by name, usage and search terms](https://github.com/nushell/nushell/pull/9035), and [FIX: give same order in `std help ...` as in `help ...`](https://github.com/nushell/nushell/pull/9034), and [TRIAGE: add the `needs-triage` to all `ISSUE_TEMPLATE`s](https://github.com/nushell/nushell/pull/9023), and [FEATURE: add `--expand` to `std clip`](https://github.com/nushell/nushell/pull/8970), and [FEATURE: add the `bench` command to the standard library](https://github.com/nushell/nushell/pull/8969)
- stevenxxiu [fixed: fix cursor position when cursor is at the end of the commandline](https://github.com/nushell/nushell/pull/9030), and [fix: set the initial repl cursor pos, fixes #8943](https://github.com/nushell/nushell/pull/8955)
- TrMen [added more examples to `help use`](https://github.com/nushell/nushell/pull/9024), and [Fix unexpected flattening of data by par-each (Issue #8497)](https://github.com/nushell/nushell/pull/9007)
- hustcer [removed npm install instruction](https://github.com/nushell/nushell/pull/9022), and [Add npm installation instruction](https://github.com/nushell/nushell/pull/8982)
- rgwood [slimmed down tests](https://github.com/nushell/nushell/pull/9021), and [Move from `winres` to better-maintained `winresource` fork](https://github.com/nushell/nushell/pull/9001)
- fdncred [fixed compilation error](https://github.com/nushell/nushell/pull/9016), and [Update rust-toolchain.toml to 1.67.1](https://github.com/nushell/nushell/pull/9012), and [add `--ide-ast` for a simplistic ast for editors](https://github.com/nushell/nushell/pull/8995), and [update `ast` to support output to json](https://github.com/nushell/nushell/pull/8962)
- sholderbach [bumped to `0.79.1` dev version](https://github.com/nushell/nushell/pull/8998), and [Pin `reedline` to `0.19.0` release](https://github.com/nushell/nushell/pull/8996), and [Bump version for `0.79.0` release](https://github.com/nushell/nushell/pull/8980)
- WindSoilder created [support blink cursor, and fix underscore's cursorshape](https://github.com/nushell/nushell/pull/8990), and [using ratatui instead of tui](https://github.com/nushell/nushell/pull/8952)
- pingiun [added extern def which allows raw arguments](https://github.com/nushell/nushell/pull/8956), and [Add --redirect-combine option to run-external](https://github.com/nushell/nushell/pull/8918)
- Mehrbod2002 created [Flags and args on def](https://github.com/nushell/nushell/pull/8953)
- MariaSolOs [changed type of parameter default values to `Option<Value>`](https://github.com/nushell/nushell/pull/8940)
- ito-hiroki [fixed completion on `$nu` to show correct menus](https://github.com/nushell/nushell/pull/8919)
- 1Kinoti [allowed records to have type annotations](https://github.com/nushell/nushell/pull/8914)
- Trivernis [fixed warning on declared config variable that originates from commands](https://github.com/nushell/nushell/pull/8891)

## Extension

- fdncred created [update changelog](https://github.com/nushell/vscode-nushell-lang/pull/115), and [update syntax for 0.79.0](https://github.com/nushell/vscode-nushell-lang/pull/114)

## Documentation

- amtoine created [fix the "`std` import" section of the 0.79 changelog](https://github.com/nushell/nushell.github.io/pull/892), and [add the note about the standard library](https://github.com/nushell/nushell.github.io/pull/885)
- hustcer created [Update npm install instruction](https://github.com/nushell/nushell.github.io/pull/891), and [Refresh command docs for nu v0.79.0](https://github.com/nushell/nushell.github.io/pull/889), and [Add npm installation instruction](https://github.com/nushell/nushell.github.io/pull/882)
- dependabot[bot] created [Bump yaml from 2.1.3 to 2.2.2](https://github.com/nushell/nushell.github.io/pull/888)
- Ifthel created [Use explicit printing in custom_commands.md](https://github.com/nushell/nushell.github.io/pull/887), and [Improve `insert` and `update` examples in working_with_lists.md](https://github.com/nushell/nushell.github.io/pull/886)
- kai-tub created [Update standard_library.md](https://github.com/nushell/nushell.github.io/pull/883)
- MariaSolOs created [Fix some typos and other nits to the variable documentation](https://github.com/nushell/nushell.github.io/pull/881)
- 1Kinoti created [update variable documentation](https://github.com/nushell/nushell.github.io/pull/880)
- sholderbach created [Release notes for `0.79.0` release.](https://github.com/nushell/nushell.github.io/pull/872)
- presidento created [Add info about echo, print and log commands to the book](https://github.com/nushell/nushell.github.io/pull/870)
- pingiun created [Add ppid to ps examples](https://github.com/nushell/nushell.github.io/pull/864)

## Nu_Scripts

- fj0r created [optimize kube_stat with ensure-cache](https://github.com/nushell/nu_scripts/pull/470), and [refactor left_prompt decorator logic](https://github.com/nushell/nu_scripts/pull/469), and [atuin](https://github.com/nushell/nu_scripts/pull/468), and [powerline : NU_POWER_MODE and NU_POWER_BENCHMARK](https://github.com/nushell/nu_scripts/pull/464), and [prompt powerline suppor color theme](https://github.com/nushell/nu_scripts/pull/461), and [refactor: unified configuration environment variables](https://github.com/nushell/nu_scripts/pull/460), and [prompt](https://github.com/nushell/nu_scripts/pull/455)
- siph created [fix readme navigation links](https://github.com/nushell/nu_scripts/pull/467)
- Hofer-Julian created [Update CODEOWNERS after refactor](https://github.com/nushell/nu_scripts/pull/466)
- Yethal created [Update to-ini.nu](https://github.com/nushell/nu_scripts/pull/465)
- fdncred created [some cleanup](https://github.com/nushell/nu_scripts/pull/463)
- sholderbach created [Include `nu-std` in the release script](https://github.com/nushell/nu_scripts/pull/462)
- Darkness9724 created [Fix wolframalpha.nu](https://github.com/nushell/nu_scripts/pull/459)
- RickCogley created [Enhance by getting length of symbol string](https://github.com/nushell/nu_scripts/pull/458), and [Add nupass.nu password generator](https://github.com/nushell/nu_scripts/pull/450)
- melMass created [refactor: ✨ ](https://github.com/nushell/nu_scripts/pull/418)

## reedline

- sholderbach created [Bump version for 0.19 release](https://github.com/nushell/reedline/pull/575)
- nibon7 created [Restore the cursor shape when reedline exits](https://github.com/nushell/reedline/pull/574)
- stevenxxiu created [feat: add `current_insertion_point()` to return the current insertion point of the input buffer](https://github.com/nushell/reedline/pull/573)
- WindSoilder created [support bracketed paste](https://github.com/nushell/reedline/pull/571)
