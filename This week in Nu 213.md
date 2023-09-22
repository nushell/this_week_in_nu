# This week in Nushell #213


## Nushell

- fdncred [added functionality to evaluate `$nu` during `--ide-check`](https://github.com/nushell/nushell/pull/10470), and [optimized aarch64 when able](https://github.com/nushell/nushell/pull/10433), and [added a new command: `into value`](https://github.com/nushell/nushell/pull/10427), and [allowed the `values` command to support `LazyRecord`s](https://github.com/nushell/nushell/pull/10418)
- anka-213 [improved the parser to prevent cubic time on nested parentheses](https://github.com/nushell/nushell/pull/10467), and [fixed exponential parser time on sequence of [[[[](https://github.com/nushell/nushell/pull/10439), and [fixed tilde-expansion for multi-byte unicode chars](https://github.com/nushell/nushell/pull/10434)
- Hofer-Julian [made Nushell changes for the improved history isolation in reedline](https://github.com/nushell/nushell/pull/10402)
- sholderbach [removed dead BSON related tests](https://github.com/nushell/nushell/pull/10458), and [improved assertions in `src/tests.rs`](https://github.com/nushell/nushell/pull/10449), and [bumped to `0.85.1` development version](https://github.com/nushell/nushell/pull/10431), and [pinned reedline to `0.24` for release](https://github.com/nushell/nushell/pull/10426), and [bumped version for the `0.85` release](https://github.com/nushell/nushell/pull/10425), and [simplified `nu!` test macros.](https://github.com/nushell/nushell/pull/10403), and [ran clippy in tests](https://github.com/nushell/nushell/pull/10394), and [split up `nu-protocol/src/engine/engine_state.rs`](https://github.com/nushell/nushell/pull/10368), and [improved `select` row perf for large N](https://github.com/nushell/nushell/pull/10355)
- WindSoilder [updated the lock file](https://github.com/nushell/nushell/pull/10437), and [added a fix to not overwrite arg's type if it's annotated explicitly](https://github.com/nushell/nushell/pull/10424)
- zhiburt [added a new `--abbreviated` option to `table`](https://github.com/nushell/nushell/pull/10399)
- tokatoka [added 2 fuzzers for nu-path, nu-parser](https://github.com/nushell/nushell/pull/10376)
- GPadley [mapped `DirectoryNotFound` to `FileNotFound` for `open` command (issue #10085)](https://github.com/nushell/nushell/pull/10089)
- amtoine [removed `str replace --string` after deprecation](https://github.com/nushell/nushell/pull/10064)
- stormasm [updated the doc in toolchain.toml describing the update plan](https://github.com/nushell/nushell/pull/10453)

## Extension

- fdncred created [Update to nushell 0.85.0](https://github.com/nushell/vscode-nushell-lang/pull/155)
- nerditation created [use `which` to search `nu` location, add icon too.](https://github.com/nushell/vscode-nushell-lang/pull/153)

## Documentation

- Hofer-Julian created [Change to an actual link in last blog post](https://github.com/nushell/nushell.github.io/pull/1070)
- hustcer created [Refresh commands' docs for v0.85](https://github.com/nushell/nushell.github.io/pull/1069)
- kubouch created [Refactor const section](https://github.com/nushell/nushell.github.io/pull/1068), and [Release notes for `0.85.0`](https://github.com/nushell/nushell.github.io/pull/1046)
- edhowland created [Fix Rust example in contributor-book/plugins.md that does not compile in recent Nushell versions](https://github.com/nushell/nushell.github.io/pull/1067)
- sholderbach created [Fix formatting in `de/book/hooks`](https://github.com/nushell/nushell.github.io/pull/1065), and [`float` instead of `decimal`](https://github.com/nushell/nushell.github.io/pull/1064)
- FilipAndersson245 created [Adds a note about mimalloc being default now](https://github.com/nushell/nushell.github.io/pull/1063)
- petrisch created [DE translation for hooks and background_tasks](https://github.com/nushell/nushell.github.io/pull/1062)
- bradfitz created [Update 2023-09-05-why-uu.md](https://github.com/nushell/nushell.github.io/pull/1061)
- fdncred created [Blog post documenting our integration with uutils](https://github.com/nushell/nushell.github.io/pull/1047)
- JoaquinTrinanes created [Fix direnv not using transformed values](https://github.com/nushell/nushell.github.io/pull/960)

## Nu_Scripts

- fj0r created [git-v2: new command `gcf` for copying files from other branch](https://github.com/nushell/nu_scripts/pull/616), and [kubernetes/kn: create namespace when it doesn't exist](https://github.com/nushell/nu_scripts/pull/610)
- marcelarie created [Use 0.85 syntax in `direnv` module](https://github.com/nushell/nu_scripts/pull/615), and [Use new syntax in `rbenv` module](https://github.com/nushell/nu_scripts/pull/614)
- baehyunsol created [use `repeat` instead of string multiplication](https://github.com/nushell/nu_scripts/pull/612)
- amtoine created [tix the release note PR opening script](https://github.com/nushell/nu_scripts/pull/611), and [fix scripts](https://github.com/nushell/nu_scripts/pull/594)
- sholderbach created [Update the bump-version script](https://github.com/nushell/nu_scripts/pull/609), and [Move `random/into decimal` to `random/into float`](https://github.com/nushell/nu_scripts/pull/606)

## reedline

- sholderbach created [Bump version for `0.24` release](https://github.com/nushell/reedline/pull/638)
- Hofer-Julian created [Improve history isolation](https://github.com/nushell/reedline/pull/634)
