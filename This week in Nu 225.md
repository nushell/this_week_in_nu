# This week in Nushell #225


## Nushell

- nibon7 [added a new `ulimit` command](https://github.com/nushell/nushell/pull/11324), and [simplified the `clear` implementation](https://github.com/nushell/nushell/pull/11273)
- KAAtheWiseGit [added a `format` base command](https://github.com/nushell/nushell/pull/11334), and [replaced bash with POSIX sh in tests](https://github.com/nushell/nushell/pull/11293)
- AucaCoyan improved IDE support: [:sparkles: Make `hover` equal to `help` command](https://github.com/nushell/nushell/pull/11320), and [:recycle: Match `--ide-hover` with `help` command](https://github.com/nushell/nushell/pull/11284)
- WindSoilder [fixed piping output logic](https://github.com/nushell/nushell/pull/11317)
- Hofer-Julian [moved `stor` commands to category `Database`](https://github.com/nushell/nushell/pull/11315), and [move history into its own module](https://github.com/nushell/nushell/pull/11308)
- AntoineSebert [fixed a build error](https://github.com/nushell/nushell/pull/11302)
- sophiajt [bumped the reedline dependency to 0.27](https://github.com/nushell/nushell/pull/11299)
- amtoine [added a `nothing -> table` signature to `format date`](https://github.com/nushell/nushell/pull/11290), and [disabled directory submodule auto export](https://github.com/nushell/nushell/pull/11157)
- CAESIUS-TIM [fixed a logical error in help glob](https://github.com/nushell/nushell/pull/11286)
- drbrain [added code to enforce that required, optional, and rest positional arguments start with an uppercase and end with a period](https://github.com/nushell/nushell/pull/11285), [did the same for command usage](https://github.com/nushell/nushell/pull/11278), and [converted the remainder of ShellError variants to named fields](https://github.com/nushell/nushell/pull/11276)
- IanManske [fixed replacement closures for `update`, `insert`, and `upsert`](https://github.com/nushell/nushell/pull/11258)
- ayax79 [added Polars struct support without unsafe blocks](https://github.com/nushell/nushell/pull/11229)
- CAD97 [made a change to only run $env.PROMPT_COMMAND once per prompt](https://github.com/nushell/nushell/pull/10986)
- sholderbach [reverted lock file changes due to openssl build failure](https://github.com/nushell/nushell/pull/11328), and did some version bump work ([1](https://github.com/nushell/nushell/pull/11333), [2](https://github.com/nushell/nushell/pull/11303), [3](https://github.com/nushell/nushell/pull/11298))
- fdncred [reverted "Only run $env.PROMPT_COMMAND once per prompt"](https://github.com/nushell/nushell/pull/11340), and [updated reedline to improve resize behavior](https://github.com/nushell/nushell/pull/11339)

## Documentation

- Tamnac created [Add time command to nushell_map.md](https://github.com/nushell/nushell.github.io/pull/1173)
- Trent-Fellbootman created [Update thinking_in_nu.md](https://github.com/nushell/nushell.github.io/pull/1172)
- hustcer created [Refresh command docs for Nu v0.88](https://github.com/nushell/nushell.github.io/pull/1171)
- TheJiahao created [Update `max_history_size` to grouped option `max_size`](https://github.com/nushell/nushell.github.io/pull/1170)
- CAESIUS-TIM created [[zh-CN] Update README, and Getting Started (入门篇)](https://github.com/nushell/nushell.github.io/pull/1168)
- OrionOth created [Update command signature doc to modern syntax](https://github.com/nushell/nushell.github.io/pull/1167)
- RGBCube created [Update background_task.md](https://github.com/nushell/nushell.github.io/pull/1166)
- amtoine created [Release notes for `0.88.0`](https://github.com/nushell/nushell.github.io/pull/1146)
- mb21 created [Extend globbing section in moving_around.md](https://github.com/nushell/nushell.github.io/pull/1125)

## Nu_Scripts

- zyfmix created [Fix: nushell at 0.88.0 start and end are deprecated](https://github.com/nushell/nu_scripts/pull/698)
- AucaCoyan created [:bug: Fix `rustup` use completions and modify README](https://github.com/nushell/nu_scripts/pull/696), and [:sparkles: Add `pnpm` completions](https://github.com/nushell/nu_scripts/pull/692)
- TeaDrinkingProgrammer created [Added updated and improved version of the conda scripts](https://github.com/nushell/nu_scripts/pull/694)
- RGBCube created [Rewrite and expand background task module](https://github.com/nushell/nu_scripts/pull/691)
- drbrain created [Improve git branch cleanup script](https://github.com/nushell/nu_scripts/pull/685)
- amtoine created [add a "bulk rename" command to the stdlib candidates](https://github.com/nushell/nu_scripts/pull/643)

## reedline

- sholderbach created [Bump version to 0.27.1](https://github.com/nushell/reedline/pull/683), and [Try to fix the docs.rs build](https://github.com/nushell/reedline/pull/682), and [Bump version for 0.27 release](https://github.com/nushell/reedline/pull/681)
- danielsomerfield created [Better behaviour on resize](https://github.com/nushell/reedline/pull/675)
