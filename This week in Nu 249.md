# This week in Nushell #249


## Nushell

- IanManske [disallowed more characters in arguments for Windows internal `cmd` commands](https://github.com/nushell/nushell/pull/13009), [restored `path type` behavior](https://github.com/nushell/nushell/pull/13006), [disabled a reedline patch for 0.94.0](https://github.com/nushell/nushell/pull/12986), and [fixed a panic when redirecting nothing](https://github.com/nushell/nushell/pull/12970)
- WindSoilder [fixed `do` closures with required, options, and rest args](https://github.com/nushell/nushell/pull/13002)
- devyn [restored tilde expansion on external command names](https://github.com/nushell/nushell/pull/13001), and [bumped the version to `0.94.1`](https://github.com/nushell/nushell/pull/12988)
- fdncred [fixed a bug in OSC9;9 execution](https://github.com/nushell/nushell/pull/12994)
- kubouch [bumped the version to 0.94.0](https://github.com/nushell/nushell/pull/12987)
- YizhePKU [fixed `touch --reference` using PWD from the environment](https://github.com/nushell/nushell/pull/12976), and [fixed `path type` using PWD from the environment](https://github.com/nushell/nushell/pull/12975)

## Extension

- ajhall [removed `/` and `\` from wordPattern](https://github.com/nushell/vscode-nushell-lang/pull/186)

## Documentation

- Kissaki created [Fix link references in translated books](https://github.com/nushell/nushell.github.io/pull/1430), and [Change inline code to code blocks](https://github.com/nushell/nushell.github.io/pull/1426), and [Update cheat_sheet.md](https://github.com/nushell/nushell.github.io/pull/1425), and [Fix configuration cell-path link reference](https://github.com/nushell/nushell.github.io/pull/1424), and [Fix text typo in 0.94.0 release post](https://github.com/nushell/nushell.github.io/pull/1420)
- IanManske created [Edit 0.94.0 release notes for `parse`](https://github.com/nushell/nushell.github.io/pull/1429), and [Add release note for changes to `parse`](https://github.com/nushell/nushell.github.io/pull/1428), and [Fix typo in 0.94.0 release notes](https://github.com/nushell/nushell.github.io/pull/1421), and [Edit 0.94.0 release notes](https://github.com/nushell/nushell.github.io/pull/1415), and [Edit 0.94.0 release notes](https://github.com/nushell/nushell.github.io/pull/1412), and [Update docs for `sys` deprecation in 0.94.0](https://github.com/nushell/nushell.github.io/pull/1387)
- devyn created [Release notes for `0.94.1`](https://github.com/nushell/nushell.github.io/pull/1427), and [Add some release notes targeted at plugin developers](https://github.com/nushell/nushell.github.io/pull/1417), and [Plugin protocol reference updates for 0.94.0](https://github.com/nushell/nushell.github.io/pull/1416), and [Release notes for `0.94.0`](https://github.com/nushell/nushell.github.io/pull/1378)
- hustcer created [Refresh command docs for Nu v0.94](https://github.com/nushell/nushell.github.io/pull/1419)
- maxim-uvarov created [Dataframes chapter update to reflect the latest changes](https://github.com/nushell/nushell.github.io/pull/1414)
- veeven created [Delete wrong vi motion command `d`](https://github.com/nushell/nushell.github.io/pull/1413)
- NotTheDr01ds created [Initial `$in` language reference](https://github.com/nushell/nushell.github.io/pull/1398)

## Nu_Scripts

- maxim-uvarov created [improve `std bench` and add `significant-digits`](https://github.com/nushell/nu_scripts/pull/859)
- ddanier created [Support whitespace before target name for make completions](https://github.com/nushell/nu_scripts/pull/858)
- IanManske created [Remove `nu-cmd-dataframe` from release script](https://github.com/nushell/nu_scripts/pull/857), and [Edit release notes template](https://github.com/nushell/nu_scripts/pull/853)
- OJarrisonn created [feat: `git clone` completions](https://github.com/nushell/nu_scripts/pull/856), and [feat: add `./gradlew` completions](https://github.com/nushell/nu_scripts/pull/855)
- laisnuto created [Add git coommit completions](https://github.com/nushell/nu_scripts/pull/854)
- 39555 created [Port `before_v0.60/with_externals` and cleanup ](https://github.com/nushell/nu_scripts/pull/852), and [Port `before_v0.60/config_management` `before_v0.60/language` `before_v0.60/prompt` `before_v0.60/tests`](https://github.com/nushell/nu_scripts/pull/851), and [Port `before_v0.60/stdlib_candidate`](https://github.com/nushell/nu_scripts/pull/850), and [Port `before v0.60/virtual_environments`](https://github.com/nushell/nu_scripts/pull/849), and [Port `before_v0.60/data_extraction` `before_v0.60/examples` `before_v0.60/duplicates`](https://github.com/nushell/nu_scripts/pull/847), and [Port `before_v0.60/fuzzy`, `before_v0.60/ls-mods` and `before_v0.60/nu_101` ](https://github.com/nushell/nu_scripts/pull/845)
- Schweber created [modules/nix: init activation-script](https://github.com/nushell/nu_scripts/pull/848)
