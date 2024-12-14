# This week in Nushell #277

## Nushell

- fdncred [fixed 64-bit hex number parsing](https://github.com/nushell/nushell/pull/14571), [updated reedline](https://github.com/nushell/nushell/pull/14541), and reverted some buggy PRs ([1](https://github.com/nushell/nushell/pull/14560), [2](https://github.com/nushell/nushell/pull/14580))
- sgvictorino [returned const values from `scope variables`](https://github.com/nushell/nushell/pull/14577) and [added support for raw strings in match patterns](https://github.com/nushell/nushell/pull/14573)
- rikukiix [fixed `exec` to decrement SHLVL correctly](https://github.com/nushell/nushell/pull/14570)
- WindSoilder [updated dependencies](https://github.com/nushell/nushell/pull/14569) and [added `-l/--long` flag to du, removed `-a/--all` flag](https://github.com/nushell/nushell/pull/14407)
- NotTheDr01ds did lots of polish for configuration: [updated sample and scaffold files](https://github.com/nushell/nushell/pull/14568), [set empty `ENV_CONVERSIONS` record by default](https://github.com/nushell/nushell/pull/14566), [allowed both NU_PLUGIN_DIRS const and env at the same time](https://github.com/nushell/nushell/pull/14553), [used const NU_LIB_DIRS in startup](https://github.com/nushell/nushell/pull/14549), and [only ran `from_string` conversion on strings](https://github.com/nushell/nushell/pull/14509)
- RobbingDaHood made some parser fixes for comments: [1](https://github.com/nushell/nushell/pull/14562), [2](https://github.com/nushell/nushell/pull/14548)
- cptpiepmatz [fixed `table` command when targeting WASM](https://github.com/nushell/nushell/pull/14530)
- 132ikl [removed grid icons deprecation warning](https://github.com/nushell/nushell/pull/14526) and [changed `help commands` to use name from scope instead of the name from the declaration](https://github.com/nushell/nushell/pull/14490)
- IanManske [made `timeit` take only closures as an argument](https://github.com/nushell/nushell/pull/14483)

## Documentation

- dtenenba [fixed multiple issues with example table](https://github.com/nushell/nushell.github.io/pull/1678)
- Squidroot2 [removed duplicate 'get' in list.md](https://github.com/nushell/nushell.github.io/pull/1676)
- 132ikl [added `cd` to title of Changing Directories in a Custom Command section for searchability](https://github.com/nushell/nushell.github.io/pull/1674)
- NotTheDr01ds [made Moving Around fixes and updates](https://github.com/nushell/nushell.github.io/pull/1672) and [updated Quick Tour chapter](https://github.com/nushell/nushell.github.io/pull/1662)

## Nu_Scripts

- hongquan [followed Include to extract more SSH hosts](https://github.com/nushell/nu_scripts/pull/993)
- a-stevan [prevented return from `toolkit` command](https://github.com/nushell/nu_scripts/pull/992)
- ff2400t [renamed usage to description in commands table](https://github.com/nushell/nu_scripts/pull/990)

## reedline

- milomg [implemented redraw on resize](https://github.com/nushell/reedline/pull/857)

