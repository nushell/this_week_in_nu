# This week in Nushell #276

## Nushell

- 132ikl [changed tests which may invoke externals to use non-conflicting names](https://github.com/nushell/nushell/pull/14516), and [made `glob` stream](https://github.com/nushell/nushell/pull/14495)
- Bahex [refactored `term query` and added a `--prefix` flag](https://github.com/nushell/nushell/pull/14446), and added a `path self` command for getting absolute paths to files at parse time ([1](https://github.com/nushell/nushell/pull/14303), [2](https://github.com/nushell/nushell/pull/14538))
- fdncred [added file column to `scope modules` output](https://github.com/nushell/nushell/pull/14524), [allowed `select` to stream more](https://github.com/nushell/nushell/pull/14492), [added environment variables for sourced files](https://github.com/nushell/nushell/pull/14486), and [added function to make env vars case-insensitive](https://github.com/nushell/nushell/pull/14390)
- amtoine [fixed multiline strings in NDNUON](https://github.com/nushell/nushell/pull/14519)
- ratherforky [fixed a silent failure in command signature parsing](https://github.com/nushell/nushell/pull/14510)
- michel-slm [bumped the `titlecase` dependency](https://github.com/nushell/nushell/pull/14502)
- alex-kattathra-johnson [shortened --max-time in tests and used a more stable error check](https://github.com/nushell/nushell/pull/14494)
- IanManske [added `--long` flag for `sys cpu`](https://github.com/nushell/nushell/pull/14485), and [removed duplicate implementations of `CallExt::rest`](https://github.com/nushell/nushell/pull/14484)
- RobbingDaHood [fixed file path completion for custom commands](https://github.com/nushell/nushell/pull/14481)
- PegasusPlusUS [added feature: PWD-per-drive to facilitate working on multiple drives on Windows](https://github.com/nushell/nushell/pull/14411)
- Jasha10 [enabled `test_cp_recurse` on macOS](https://github.com/nushell/nushell/pull/14358)
- sgvictorino [normalized special characters in module names to allow variable access](https://github.com/nushell/nushell/pull/14353)
- musicinmybrain updated dependencies ([1](https://github.com/nushell/nushell/pull/14513), [2](https://github.com/nushell/nushell/pull/14489))
- sholderbach [improved the `sleep` example using multiple durations](https://github.com/nushell/nushell/pull/14520), and [added `remove` as a search term on `drop` commands](https://github.com/nushell/nushell/pull/14493)
- ayax79 [improved documentation and error handling around `polars with-column --name`](https://github.com/nushell/nushell/pull/14527), and [converted Filesize to Int for `polars`](https://github.com/nushell/nushell/pull/14491)
- cptpiepmatz [fixed the missing `installed_plugins` field in `version`](https://github.com/nushell/nushell/pull/14488)
- maxim-uvarov [tweaked error message wording](https://github.com/nushell/nushell/pull/14533)

## Documentation

- hustcer [upgraded shiki and vuepress plugins](https://github.com/nushell/nushell.github.io/pull/1668), [allowed wider page content](https://github.com/nushell/nushell.github.io/pull/1667), and [regenerated command docs](https://github.com/nushell/nushell.github.io/pull/1665)
- lfrancke [fixed minor typo](https://github.com/nushell/nushell.github.io/pull/1666)
- NotTheDr01ds [clarified XDG_DATA_DIRS are Unix-only](https://github.com/nushell/nushell.github.io/pull/1663), [added backlink from "Default Shell" to Config chapter](https://github.com/nushell/nushell.github.io/pull/1659), and [added blog and Configuration Chapter Preview for upcoming config changes](https://github.com/nushell/nushell.github.io/pull/1656)
- paulie4 [fixed flags code to only add `short_flag` when needed in `make_docs.nu`](https://github.com/nushell/nushell.github.io/pull/1658), and [cleaned up params/flags and added more keybindings for `explore`](https://github.com/nushell/nushell.github.io/pull/1652)
- fdncred [updated the dataframe cookbook walkthrough](https://github.com/nushell/nushell.github.io/pull/1657)
- hamza-m-masood [updated broken link in loading_data.md](https://github.com/nushell/nushell.github.io/pull/1655)
- jajimajp [fixed typo (Japanese)](https://github.com/nushell/nushell.github.io/pull/1654)

## Nu_Scripts

- e2dk4r [improved code readability for scoop custom-completions](https://github.com/nushell/nu_scripts/pull/989), and [improved performance of getting scoop commands for custom-completions](https://github.com/nushell/nu_scripts/pull/988)
- washanhanzi [added readme for kubernetes module](https://github.com/nushell/nu_scripts/pull/987)
- NotTheDr01ds [reset stdlib-candidate](https://github.com/nushell/nu_scripts/pull/986)

