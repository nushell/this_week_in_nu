# This week in Nushell #226


## Nushell

- dependabot[bot] [bumped unsafe-libyaml from 0.2.9 to 0.2.10](https://github.com/nushell/nushell/pull/11391), and [Bump itertools from 0.11.0 to 0.12.0](https://github.com/nushell/nushell/pull/11360), and [Bump lscolors from 0.15.0 to 0.16.0](https://github.com/nushell/nushell/pull/11359), and [Bump crate-ci/typos from 1.16.24 to 1.16.25](https://github.com/nushell/nushell/pull/11358), and [Bump shadow-rs from 0.24.1 to 0.25.0](https://github.com/nushell/nushell/pull/11282)
- sholderbach [bumped `fancy-regex` to single `0.12.0` version](https://github.com/nushell/nushell/pull/11389), and [Expand the workspace `members` in `Cargo.toml`](https://github.com/nushell/nushell/pull/11387), and [Construct `Record`s only through checked helpers](https://github.com/nushell/nushell/pull/11386)
- IanManske [made `Call::get_flag_expr` return `&Expression` instead of owned value ](https://github.com/nushell/nushell/pull/11388), and [Simplify `SIGQUIT` handling](https://github.com/nushell/nushell/pull/11381), and [Refactor `group-by` with closure grouper](https://github.com/nushell/nushell/pull/11370), and [Remove `Expr::MatchPattern`](https://github.com/nushell/nushell/pull/11367), and [Remove `Value::MatchPattern`](https://github.com/nushell/nushell/pull/11356)
- AucaCoyan created [:memo: Update `str trim` CLI help doc](https://github.com/nushell/nushell/pull/11383)
- nibon7 [fixed build for BSDs](https://github.com/nushell/nushell/pull/11372), and [Bump windows from 0.48.0 to 0.52.0 ](https://github.com/nushell/nushell/pull/11325)
- fdncred [added special emoji handling for debug --raw](https://github.com/nushell/nushell/pull/11368)
- ysthakur created [Only run $env.PROMPT_COMMAND once per prompt (copy of #10986)](https://github.com/nushell/nushell/pull/11366)
- WindSoilder [deprecated `--flag: bool` in custom command](https://github.com/nushell/nushell/pull/11365), and [enable flag value type checking](https://github.com/nushell/nushell/pull/11311)
- 0323pin [fixed build on NetBSD](https://github.com/nushell/nushell/pull/11364)
- stormasm created [nu-cli repl get_command_finished_marker() does not need to be pub](https://github.com/nushell/nushell/pull/11362)
- KAAtheWiseGit [renamed extra's `format` to `format pattern`](https://github.com/nushell/nushell/pull/11355)
- hustcer [downgraded openssl-src to fix riscv64 build target, close #11345](https://github.com/nushell/nushell/pull/11353)
- crides [fixed shell integration markers](https://github.com/nushell/nushell/pull/11352)
- amtoine [improved completions of `use` and `overlay use`](https://github.com/nushell/nushell/pull/11330)
- hardfau1t created [fix(cd): on android/termux fails to cd into /sdcard](https://github.com/nushell/nushell/pull/10329)

## Documentation

- Trent-Fellbootman created [Update types_of_data.md](https://github.com/nushell/nushell.github.io/pull/1184)
- WindSoilder created [add information about switches](https://github.com/nushell/nushell.github.io/pull/1182)
- github-actions[bot] created [Compressed Images](https://github.com/nushell/nushell.github.io/pull/1181)
- amtoine created [logo contest announcement](https://github.com/nushell/nushell.github.io/pull/1180)
- MediosZ created [Sync zh-CN shells_in_shells.](https://github.com/nushell/nushell.github.io/pull/1178)
- braddunbar created [Typo in history menu section](https://github.com/nushell/nushell.github.io/pull/1177)

## Nu_Scripts

- AucaCoyan created [:sparkles: add more `gh` completions](https://github.com/nushell/nu_scripts/pull/713), and [:sparkles: Add the first layer of depth to the cmds](https://github.com/nushell/nu_scripts/pull/708), and [:sparkles: First `gh` completions](https://github.com/nushell/nu_scripts/pull/706)
- robbienohra created [fix: missing regex flag](https://github.com/nushell/nu_scripts/pull/712)
- fj0r created [merge container-inspect into container-process-list](https://github.com/nushell/nu_scripts/pull/711), and [comma: support filter, watch, poll](https://github.com/nushell/nu_scripts/pull/707), and [new module comma and some updates](https://github.com/nushell/nu_scripts/pull/704)
- adrian5 created [Add tokyo-moon theme variant](https://github.com/nushell/nu_scripts/pull/710)
- kjelly created [fix git-v2 and kubernetes](https://github.com/nushell/nu_scripts/pull/703)
