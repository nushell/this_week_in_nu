# This week in Nushell #233


## Nushell

- WindSoilder [added new syntax for redirecting stderr and stdout+stderr with a pipe](https://github.com/nushell/nushell/pull/11708), and [fixed file completions for glob patterns](https://github.com/nushell/nushell/pull/11766)
- fdncred bumped some versions ([1](https://github.com/nushell/nushell/pull/11804), [2](https://github.com/nushell/nushell/pull/11793), [3](https://github.com/nushell/nushell/pull/11715)), [made it easier to convert `int`s, to `filesize`s](https://github.com/nushell/nushell/pull/11797), [made `ansi strip` work for more data types](https://github.com/nushell/nushell/pull/11781), [made the `char` command `const`](https://github.com/nushell/nushell/pull/11771), and [allowed strings with thousands separators to be converted to filesize or ints](https://github.com/nushell/nushell/pull/11724)
- hustcer [upgraded the hustcer/setup-nu GitHub action](https://github.com/nushell/nushell/pull/11792)
- nibon7 [upgraded miette from 5.10.0 to 7.0.0](https://github.com/nushell/nushell/pull/11788)
- kubouch bumped some versions ([1](https://github.com/nushell/nushell/pull/11787), [2](https://github.com/nushell/nushell/pull/11782), [3](https://github.com/nushell/nushell/pull/11730)), [improved `def` body parsing](https://github.com/nushell/nushell/pull/11719), and [fixed a panic in `rotate`](https://github.com/nushell/nushell/pull/11718)
- IanManske [added a serde feature for `byte-unit`](https://github.com/nushell/nushell/pull/11786), [fixed up a `LazyRecord` error message](https://github.com/nushell/nushell/pull/11772), and [refactored some Record code](https://github.com/nushell/nushell/pull/11726)
- abusch [allowed specifying a cellpath in `input list`](https://github.com/nushell/nushell/pull/11748), and [upgraded to ratatui 0.26](https://github.com/nushell/nushell/pull/11742)
- TrMen added code to [enforce a call stack depth limit for all calls](https://github.com/nushell/nushell/pull/11729)
- kit494way tweaked the parser to [allow comments in match blocks](https://github.com/nushell/nushell/pull/11717)
- kik4444 tweaked [`query web --query` to return `list<list<string>>` like the scraper crate's `ElementRef::text()`](https://github.com/nushell/nushell/pull/11705)
- crides [improved colors for file-like completions](https://github.com/nushell/nushell/pull/11702)
- KAAtheWiseGit [fixed a panic when parsing an empty file](https://github.com/nushell/nushell/pull/11314)

## Documentation

- WindSoilder created [Update 2024-02-06-nushell_0_90_0.md](https://github.com/nushell/nushell.github.io/pull/1249), and [Update 2024-02-06-nushell_0_90_0.md](https://github.com/nushell/nushell.github.io/pull/1241), and [update escaping glob information](https://github.com/nushell/nushell.github.io/pull/1229)
- kubouch created [Fix typo in value](https://github.com/nushell/nushell.github.io/pull/1248), and [Update release notes for 0.90.0](https://github.com/nushell/nushell.github.io/pull/1244), and [Release notes for 0.90.0](https://github.com/nushell/nushell.github.io/pull/1243), and [Release notes for `0.90.0`](https://github.com/nushell/nushell.github.io/pull/1203)
- abusch created [Fix typo in `into cell-path` in the 0.90.1 release notes](https://github.com/nushell/nushell.github.io/pull/1247)
- hustcer created [Refresh command docs for v0.90.0](https://github.com/nushell/nushell.github.io/pull/1246)
- IanManske created [Escape false <int> HTML element](https://github.com/nushell/nushell.github.io/pull/1245)
- mandarvaze created [Fix typo](https://github.com/nushell/nushell.github.io/pull/1242)
- kit494way created [Remove $nothing](https://github.com/nushell/nushell.github.io/pull/1239)
- kai-tub created [Update `lang-guide/README.md`](https://github.com/nushell/nushell.github.io/pull/1237)
- dnkmmr69420 created [added directions for installing nushell with nix in README.md](https://github.com/nushell/nushell.github.io/pull/1236)
- ysthakur created [Add note about string interpolation at parse time](https://github.com/nushell/nushell.github.io/pull/1227)
- c4lliope created [add env fallback example](https://github.com/nushell/nushell.github.io/pull/1226)
- amtoine created [update the SSH agent snippet](https://github.com/nushell/nushell.github.io/pull/1169)
- Roger-Roger-debug created [Fix syntax errors](https://github.com/nushell/nushell.github.io/pull/1081)

## Nu_Scripts

- dam4rus created [Add refs to git log output](https://github.com/nushell/nu_scripts/pull/757)
- mart-w created [Extend pass completion](https://github.com/nushell/nu_scripts/pull/756)
- melMass created [feat: ✨ add pixi completions](https://github.com/nushell/nu_scripts/pull/755)
- kubouch created [Add script to generate lists of PRs](https://github.com/nushell/nu_scripts/pull/753)
- RGBCube created [background_task: Fix quoted commands and fix deprecation of implicit spreading and clarify docs](https://github.com/nushell/nu_scripts/pull/752)

## reedline

- Cactus-man created [Fix typos and grammar mistakes](https://github.com/nushell/reedline/pull/743)
- kubouch created [Bump to version 0.29](https://github.com/nushell/reedline/pull/742)
- saep created [Remove duplicates from file-based history search](https://github.com/nushell/reedline/pull/741)
