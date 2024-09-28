# This week in Nushell #266

## Nushell

- replcat [added support for kitty key modifiers in keybindings](https://github.com/nushell/nushell/pull/13906)
- nome [fixed handling of stopped TUI applications on unix](https://github.com/nushell/nushell/pull/13741)
- fdncred [fixed a bug in the toolkit](https://github.com/nushell/nushell/pull/13943), [fixed ls_colors coloring in grid and ls](https://github.com/nushell/nushell/pull/13935), [updated the defaults for shell_integration](https://github.com/nushell/nushell/pull/13929), [added binary input to hash commands](https://github.com/nushell/nushell/pull/13923), [updated the folder_depth algorithm for glob command](https://github.com/nushell/nushell/pull/13915), [updated reedline](https://github.com/nushell/nushell/pull/13909), [fixed the ability to add a plugin by name instead of path](https://github.com/nushell/nushell/pull/13877), and [added threads to the `ls` command to increase performance in some circumstances](https://github.com/nushell/nushell/pull/13836)
- ayax79 [added command `polars len` for performing count(*) like operations](https://github.com/nushell/nushell/pull/13941), [exposed flag truncate-ragged-lines in `polars open`](https://github.com/nushell/nushell/pull/13939), [added command `polars profile` for profiling lazy dataframes](https://github.com/nushell/nushell/pull/13904), and [added `polars concat` to allow concatenation of multiple dataframes](https://github.com/nushell/nushell/pull/13879)
- saurabh10041998 [fixed a Docker image build failure](https://github.com/nushell/nushell/pull/13938)
- hustcer [made some small tweaks to release and nightly workflow](https://github.com/nushell/nushell/pull/13912), and [added loongarch64-unknown-linux-gnu-gcc build target](https://github.com/nushell/nushell/pull/13895)
- WindSoilder [bumped version to 0.98.1](https://github.com/nushell/nushell/pull/13896), and [removed more quotes on external command arguments](https://github.com/nushell/nushell/pull/13883)
- sgvictorino [fixed `inspect` and `explore` panics on empty records](https://github.com/nushell/nushell/pull/13893)
- weirdan [made `input listen` respect `$env.config.use_kitty_protocol`](https://github.com/nushell/nushell/pull/13892)
- NotTheDr01ds [added search terms to `into value`](https://github.com/nushell/nushell/pull/13890), and [made Nu only ask to create config files the first time it's started](https://github.com/nushell/nushell/pull/13857)
- IanManske [fixed `try` not working with `let`, etc.](https://github.com/nushell/nushell/pull/13885), and [fixed `do -p` not waiting for external commands](https://github.com/nushell/nushell/pull/13881)
- fornwall [bumped rustix from 0.38.34 to 0.38.37](https://github.com/nushell/nushell/pull/13878)
- Bahex [added content_type metadata to view source](https://github.com/nushell/nushell/pull/13859)
- dead10ck [added binary type support to polars](https://github.com/nushell/nushell/pull/13830)
- YizhePKU [set current working directory at startup](https://github.com/nushell/nushell/pull/12953)
- anka-213 [fixed panic on too few arguments for custom function](https://github.com/nushell/nushell/pull/10395)

## Extension

- fdncred [updated grammar to nushell 0.98.0, version and changelog](https://github.com/nushell/vscode-nushell-lang/pull/188)

## Documentation

- 132ikl [added warning about display_errors](https://github.com/nushell/nushell.github.io/pull/1562)
- sholderbach [fixed equal operator](https://github.com/nushell/nushell.github.io/pull/1561)

## Nu_Scripts

- schrieveslaach [fixed git diff completions](https://github.com/nushell/nu_scripts/pull/962)
- louiss0 [added yadm completions to the repo](https://github.com/nushell/nu_scripts/pull/960)
- AucaCoyan [fixed `git init --initial-branch` string instead of bool](https://github.com/nushell/nu_scripts/pull/959), and [added completions for `bmc` client](https://github.com/nushell/nu_scripts/pull/932)

## reedline

- uek-1 [fixed demo completions](https://github.com/nushell/reedline/pull/835), and [added partial completions to the MenuNext event](https://github.com/nushell/reedline/pull/828)
- replcat [added test for kitty protocol modifier key in vi mode](https://github.com/nushell/reedline/pull/831)
- WindSoilder [changed ctrl-k to `cut to line end` in emacs mode](https://github.com/nushell/reedline/pull/826)

