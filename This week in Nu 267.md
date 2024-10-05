# This week in Nushell #267

## Nushell

- uek-1 [added operator completions](https://github.com/nushell/nushell/pull/13818)
- IanManske [made `get_env_var` return a reference to a `Value`](https://github.com/nushell/nushell/pull/13987), [fixed `LAST_EXIT_CODE` not being set for internal errors](https://github.com/nushell/nushell/pull/13954), and [fixed non-zero exit code errors in the middle of pipelines](https://github.com/nushell/nushell/pull/13899)
- fdncred [updated osc_633 string escaping](https://github.com/nushell/nushell/pull/14008), [allowed both slash and backslash for Windows paths](https://github.com/nushell/nushell/pull/13996), [enabled bools to be type checked with each other](https://github.com/nushell/nushell/pull/13968), [updated the human-date-parser crate](https://github.com/nushell/nushell/pull/13962), and [tried a potential fix for vt processing](https://github.com/nushell/nushell/pull/13961)
- NotTheDr01ds [removed superfluous separators from help](https://github.com/nushell/nushell/pull/14007), [updated warning messages for old dirs/shells](https://github.com/nushell/nushell/pull/13997), [updated the wrap example](https://github.com/nushell/nushell/pull/13986), [updated the merge example](https://github.com/nushell/nushell/pull/13985), and [improved startup time when using std-lib](https://github.com/nushell/nushell/pull/13842)
- akirabaruah [implemented consistent default key bindings for ide_completion_menu](https://github.com/nushell/nushell/pull/13955)
- zhiburt [fixed footer truncation in nu-table for head_on_border cases](https://github.com/nushell/nushell/pull/13998), [fixed :try table view in nu-explore](https://github.com/nushell/nushell/pull/13964), and [fixed coloring of file names in `ls | explore`](https://github.com/nushell/nushell/pull/13952)
- Lord-LightSpeed [updated `fill.rs` to fix the last example in help](https://github.com/nushell/nushell/pull/13993)
- Kither12 [added dollar sign escaping in tab completion](https://github.com/nushell/nushell/pull/13988)
- hustcer [fixed typos](https://github.com/nushell/nushell/pull/13980) and [simplified the Dockerfile](https://github.com/nushell/nushell/pull/13974)
- ayax79 [fixed `polars into-df` for structs](https://github.com/nushell/nushell/pull/13977)
- cptpiepmatz [made `SpanId` and `RegId` use the new ID struct](https://github.com/nushell/nushell/pull/13963) and [replaced raw usize IDs with new types](https://github.com/nushell/nushell/pull/13832)

## Documentation

- hustcer [upgraded dev dependencies and fixed some style issues](https://github.com/nushell/nushell.github.io/pull/1577)
- chapmanjacobd [added a Windows command_not_found example](https://github.com/nushell/nushell.github.io/pull/1576)
- NotTheDr01ds [fixed a broken link from Custom Commands update](https://github.com/nushell/nushell.github.io/pull/1570), [converted blockquotes to callouts](https://github.com/nushell/nushell.github.io/pull/1569), [updated the Custom Command chapter](https://github.com/nushell/nushell.github.io/pull/1565), and [added a one-liner for installing plugins with Cargo](https://github.com/nushell/nushell.github.io/pull/1564)
- 132ikl [highlighted the differences between scripts and modules](https://github.com/nushell/nushell.github.io/pull/1567)
- ghaaj [unified the language identifiers of code blocks to 'sh'](https://github.com/nushell/nushell.github.io/pull/1563)

## Nu_Scripts

- NotTheDr01ds [added table and list helper commands](https://github.com/nushell/nu_scripts/pull/967) and [removed an outdated logging module](https://github.com/nushell/nu_scripts/pull/966)
- Schweber [added nufetch.nu to the nix scripts](https://github.com/nushell/nu_scripts/pull/963)

