# This week in Nushell #217


## Nushell

- Hofer-Julian did lots of work with long flags/options: [1](https://github.com/nushell/nushell/pull/10787), [2](https://github.com/nushell/nushell/pull/10777), [3](https://github.com/nushell/nushell/pull/10776), [4](https://github.com/nushell/nushell/pull/10775), [5](https://github.com/nushell/nushell/pull/10753), [6](https://github.com/nushell/nushell/pull/10752), [7](https://github.com/nushell/nushell/pull/10668)
- p00f [made hints aware of the current directory](https://github.com/nushell/nushell/pull/10780)
- sholderbach [created a new platform support policy document](https://github.com/nushell/nushell/pull/10778), and did lots of version-bump-related work: [1](https://github.com/nushell/nushell/pull/10755), [2](https://github.com/nushell/nushell/pull/10741), [3](https://github.com/nushell/nushell/pull/10726), [4](https://github.com/nushell/nushell/pull/10725)
- amtoine did lots of work to deprecate+remove old commands ([1](https://github.com/nushell/nushell/pull/10772), [2](https://github.com/nushell/nushell/pull/10771), [3](https://github.com/nushell/nushell/pull/10718), [4](https://github.com/nushell/nushell/pull/10716), [5](https://github.com/nushell/nushell/pull/10715), [6](https://github.com/nushell/nushell/pull/10568), [7](https://github.com/nushell/nushell/pull/10567)) and [added `toolkit run` to run a Nushell revision](https://github.com/nushell/nushell/pull/10687)
- fdncred [renamed `unfold` to `generate`](https://github.com/nushell/nushell/pull/10770), [updated release-pkg.nu with updated manual instructions](https://github.com/nushell/nushell/pull/10759), [added coreutils to cp search terms](https://github.com/nushell/nushell/pull/10738), and [added a `debug info` command to show memory info](https://github.com/nushell/nushell/pull/10711)
- jntrnr [fixed the flag type on release-pkg.nu](https://github.com/nushell/nushell/pull/10762)
- hustcer [fixed winget release submission error](https://github.com/nushell/nushell/pull/10757)
- gaetschwartz [implemented modulo for duration](https://github.com/nushell/nushell/pull/10745)
- WindSoilder [refactored the lex_item implementation](https://github.com/nushell/nushell/pull/10744), and [remove duplicate code to simplify `lite_parsing` logic](https://github.com/nushell/nushell/pull/10735)
- Tiggax [added `--ignore-error` to reject](https://github.com/nushell/nushell/pull/10737)
- 0scvr [allowed empty list inputs in `group-by` and return empty record](https://github.com/nushell/nushell/pull/10730), and [fixed typos in CONTRIBUTING.md](https://github.com/nushell/nushell/pull/10727)
- lavafroth [escaped path that could be a flag](https://github.com/nushell/nushell/pull/10721), and [fix: only escape path containing numbers if they can be valid floating points](https://github.com/nushell/nushell/pull/10719), and [Extract common logic for setting error in `parse_short_flags`](https://github.com/nushell/nushell/pull/10709)
- zhiburt [updated table rendering code to use config color scheme in kv tables and `table -e`](https://github.com/nushell/nushell/pull/10720)
- bobhy [allowed filesystem commands to access files with glob metachars in name](https://github.com/nushell/nushell/pull/10694)

## Extension

- fdncred created [Prepare for release](https://github.com/nushell/vscode-nushell-lang/pull/163)

## Documentation

- 0scvr created [Update outdated std log import in `std_log.nu`](https://github.com/nushell/nushell.github.io/pull/1113)
- hustcer created [Refresh command docs for Nu v0.86](https://github.com/nushell/nushell.github.io/pull/1112)
- das-g created [Nushell 0.86 release notes: fix grammar "to now about" → "to know about"](https://github.com/nushell/nushell.github.io/pull/1111), and [Nushell 0.86 release notes: fix grammar "made their"→"made there"](https://github.com/nushell/nushell.github.io/pull/1110)
- kubouch created [Extend notes about bool options and def changes](https://github.com/nushell/nushell.github.io/pull/1109)
- dependabot[bot] created [Bump postcss from 8.4.29 to 8.4.31](https://github.com/nushell/nushell.github.io/pull/1103)
- amtoine created [Release notes for `0.86`](https://github.com/nushell/nushell.github.io/pull/1071)

## Nu_Scripts

- AntoineSebert created [fix: replace `-c ['name' 'connection']` by `--column { name: connection }`](https://github.com/nushell/nu_scripts/pull/646)
- amtoine created [fix removed commands](https://github.com/nushell/nu_scripts/pull/645), and [make_release: do not annotate boolean switches in public API](https://github.com/nushell/nu_scripts/pull/635), and [enhance release note PR template](https://github.com/nushell/nu_scripts/pull/618), and [add a section about *after the release* in the release README](https://github.com/nushell/nu_scripts/pull/560)
- drbrain created [Improved CDPATH](https://github.com/nushell/nu_scripts/pull/644)
- fj0r created [replace `def-env` with `def --env`](https://github.com/nushell/nu_scripts/pull/641), and [upgrade to 0.86](https://github.com/nushell/nu_scripts/pull/640)
- TechWatching created [Move def before extern in winget-completions.nu](https://github.com/nushell/nu_scripts/pull/638)
- bobhy created [Add widget for nu exe (debug/release, and main vs other branch)](https://github.com/nushell/nu_scripts/pull/634)

## reedline

- p00f created [add cwd aware hinter](https://github.com/nushell/reedline/pull/647)
- sholderbach created [Fix clippy lint from most recent Rust](https://github.com/nushell/reedline/pull/646), and [Bump version for `0.25.0` release](https://github.com/nushell/reedline/pull/645)
