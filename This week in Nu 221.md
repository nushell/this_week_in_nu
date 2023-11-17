# This week in Nushell #221


## Nushell

- schrieveslaach [implemented LSP Text Document Synchronization](https://github.com/nushell/nushell/pull/10941)
- kubouch [made a fix to uu_cp](https://github.com/nushell/nushell/pull/11080)
- fdncred [bumped rust-toolchain to 1.72.1](https://github.com/nushell/nushell/pull/11079), [optimized/cleaned up a few of the `table` changes](https://github.com/nushell/nushell/pull/11076), [corrected table example syntax](https://github.com/nushell/nushell/pull/11074), [added a "default" table theme](https://github.com/nushell/nushell/pull/11072), [tweaked `table` example/parameter text](https://github.com/nushell/nushell/pull/11071), and [allowed parsing of human readable datetimes](https://github.com/nushell/nushell/pull/11051)
- sophiajt [fixed the output type for 'view files'](https://github.com/nushell/nushell/pull/11077)
- WindSoilder [added a cross platform null-device name to std](https://github.com/nushell/nushell/pull/11070), [fixed custom commands' default value](https://github.com/nushell/nushell/pull/11043), and [made `reject` support list input directly](https://github.com/nushell/nushell/pull/11024)
- dead10ck [fixed `into binary -c` to return 0 as single byte](https://github.com/nushell/nushell/pull/11068), and [improved testing support](https://github.com/nushell/nushell/pull/10692)
- IanManske [fixed `rm` path handling](https://github.com/nushell/nushell/pull/11064)
- zhiburt made improvements+fixes to table rendering: [1](https://github.com/nushell/nushell/pull/11058), [2](https://github.com/nushell/nushell/pull/11054)
- sholderbach [moved to a clearer reedline keyboard enhancement API](https://github.com/nushell/nushell/pull/11045) and did lots of version bumping: [1](https://github.com/nushell/nushell/pull/11056), [2](https://github.com/nushell/nushell/pull/11053), [3](https://github.com/nushell/nushell/pull/11044), [4](https://github.com/nushell/nushell/pull/11031)
- nibon7 [applied nightly clippy fixes](https://github.com/nushell/nushell/pull/11083)
- FMotalleb [fixed the use of `HTTP_PROXY` in `http get`](https://github.com/nushell/nushell/pull/11026)
- amtoine removed lots of unused/obsolete functionality: [1](https://github.com/nushell/nushell/pull/11000), [2](https://github.com/nushell/nushell/pull/10839), [3](https://github.com/nushell/nushell/pull/10784), [4](https://github.com/nushell/nushell/pull/10773)

## Extension

- EmilyGraceSeville7cf created [More conditional and loop snippets](https://github.com/nushell/vscode-nushell-lang/pull/165)

## Documentation

- github-actions[bot] created [Compressed Images](https://github.com/nushell/nushell.github.io/pull/1147)
- hustcer created [Refresh command docs for Nu v0.87](https://github.com/nushell/nushell.github.io/pull/1144)
- sophiajt created [Add 2023 survey results](https://github.com/nushell/nushell.github.io/pull/1143)
- WindSoilder created [Rename back from `Changelog` to `Blog`](https://github.com/nushell/nushell.github.io/pull/1141)
- MarikaChlebowska created [Fix broken link](https://github.com/nushell/nushell.github.io/pull/1140)
- Traister101 created [Clarify Dumping files into directory](https://github.com/nushell/nushell.github.io/pull/1139)
- amtoine created [add a few fixes for the release note of 0.86.0](https://github.com/nushell/nushell.github.io/pull/1115), and [Release notes for `0.87.0`](https://github.com/nushell/nushell.github.io/pull/1114)

## Nu_Scripts

- WindSoilder created [remove null-stream](https://github.com/nushell/nu_scripts/pull/670)
- fj0r created [cwdhist: can place the path anywhere in the buffer](https://github.com/nushell/nu_scripts/pull/669), and [cwdhist: remove sqlite3 dependency](https://github.com/nushell/nu_scripts/pull/661)
- sholderbach created [Update `nu_release.nu` for 0.87 release](https://github.com/nushell/nu_scripts/pull/668), and [Change `nu-deps` script to not care about waves](https://github.com/nushell/nu_scripts/pull/667)
- Abdillah created [completions/git: fix support for path relative to current directory](https://github.com/nushell/nu_scripts/pull/666)
- amtoine created [fix the TOC of the release note template](https://github.com/nushell/nu_scripts/pull/664), and [fix the indentation of the comments in the release note template...](https://github.com/nushell/nu_scripts/pull/663), and [add a command to get last release date in the release note template](https://github.com/nushell/nu_scripts/pull/662), and [add a few enhancements to the `create-pr` script for releases](https://github.com/nushell/nu_scripts/pull/642), and [complete the release note template](https://github.com/nushell/nu_scripts/pull/637), and [make `list-merged-prs` a module and add template example](https://github.com/nushell/nu_scripts/pull/636)

## reedline

- Hofer-Julian created [Also run clippy on examples](https://github.com/nushell/reedline/pull/666)
- sholderbach created [Bump version for `0.26.0` release](https://github.com/nushell/reedline/pull/664), and [Properly handle optional event modes](https://github.com/nushell/reedline/pull/659)
- ClementNerma created [Add more derive impl for HistoryItemId](https://github.com/nushell/reedline/pull/662), and [Make `Result` and `ReedlineError` public](https://github.com/nushell/reedline/pull/661)
- p00f created [CwdAwareHinter: remove cwd filter when there are no results](https://github.com/nushell/reedline/pull/656)
