# This Week in Nushell #256

## Nushell

- devyn [overhauled `$in` expressions](https://github.com/nushell/nushell/pull/13357), [made `ast::Call::span()` and `arguments_span()` more robust](https://github.com/nushell/nushell/pull/13412), [enabled plugins to find and call other commands](https://github.com/nushell/nushell/pull/13407), and [reported parse warnings and compile errors when running script files](https://github.com/nushell/nushell/pull/13369)
- WindSoilder [prohibited break/continue in the `each` and `items` commands](https://github.com/nushell/nushell/pull/13398) and [switched the positions of <initial> and <closure> in the `generate` command so that the closure can have default parameters](https://github.com/nushell/nushell/pull/13393)
- Zoybean [added a --quiet flag to the `watch` command](https://github.com/nushell/nushell/pull/13415)
- IanManske [refactored `window`](https://github.com/nushell/nushell/pull/13401), [removed an unused field in `StateWorkingSet`](https://github.com/nushell/nushell/pull/13387), and [deprecated `group` in favor of `chunks`](https://github.com/nushell/nushell/pull/13377)
- 132ikl [made the default config more consistent](https://github.com/nushell/nushell/pull/13399)
- jcgruenhage [switched from `dirs_next` 2.0 to `dirs` 5.0](https://github.com/nushell/nushell/pull/13384) and [used directories for autoloading](https://github.com/nushell/nushell/pull/13382)
- zhiburt [fixed an issue when column headers are printed on the table border](https://github.com/nushell/nushell/pull/13389)
- weirdan [removed the `default` list-diving behavior](https://github.com/nushell/nushell/pull/13386)
- sholderbach [fixed a CI test failure on main (nu-json)](https://github.com/nushell/nushell/pull/13374) and [added top-level crate documentation/READMEs](https://github.com/nushell/nushell/pull/12907)
- drmason13 [updated the JSON format output to keep braces on the same line (issue #13326)](https://github.com/nushell/nushell/pull/13352)
- suimong [made minor updates to the documentation of `reduce`](https://github.com/nushell/nushell/pull/13408)

## Nu_Scripts

- NotTheDr01ds [bumped the `stdlib-candidate` `nupm` version](https://github.com/nushell/nu_scripts/pull/904), [removed the multi-line flag from regexes](https://github.com/nushell/nu_scripts/pull/903), [recovered non-lemnos themes](https://github.com/nushell/nu_scripts/pull/902), [simplified theme usage](https://github.com/nushell/nu_scripts/pull/896), and [introduced a new std-rfc command `str dedent` (a.k.a. unindent) to remove common indentation from a multiline string](https://github.com/nushell/nu_scripts/pull/894)
- Okdro [added Git completions for the restore subcommand](https://github.com/nushell/nu_scripts/pull/895)

