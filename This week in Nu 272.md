# This week in Nushell #272

## Nushell

- IanManske [removed `as_i64` and `as_f64`](https://github.com/nushell/nushell/pull/14258), [made `to text` line endings consistent for list (streams)](https://github.com/nushell/nushell/pull/14166), and [overhauled div, mod, and floor div](https://github.com/nushell/nushell/pull/14157)
- aionescu [removed unneeded clones in `select`](https://github.com/nushell/nushell/pull/14283)
- fdncred [updated reedline to the latest commit](https://github.com/nushell/nushell/pull/14281), [updated human-date-parser conversion to use local timezone](https://github.com/nushell/nushell/pull/14266), and [allowed != for polars](https://github.com/nushell/nushell/pull/14263)
- WindSoilder [prevented IR from generating unnecessary instructions for `def` and `export def`](https://github.com/nushell/nushell/pull/14114), and [fixed $env.FILE_PWD and $env.CURRENT_FILE inside `use`](https://github.com/nushell/nushell/pull/14101)
- weirdan [fixed the order of preference for `VISUAL` and `EDITOR`](https://github.com/nushell/nushell/pull/14275)
- 132ikl [improved Nushell's handling of case-insensitive string handling](https://github.com/nushell/nushell/pull/14255)
- sholderbach [consolidated uses of `test-case` to `rstest`](https://github.com/nushell/nushell/pull/14250)
- CharlesTaylor7 [made empty rest args match an empty list](https://github.com/nushell/nushell/pull/14246)
- alex-kattathra-johnson [added tests for the `--max-age` arg in http commands](https://github.com/nushell/nushell/pull/14245), and [changed --max-time arg for http commands to use `Duration` type](https://github.com/nushell/nushell/pull/14237)
- NotTheDr01ds [stopped autoloading deprecated-dirs](https://github.com/nushell/nushell/pull/14242)
- Bahex [added table params support to `url join` and `url build-query`](https://github.com/nushell/nushell/pull/14239), and [implemented a new `url split-query` command](https://github.com/nushell/nushell/pull/14211)
- sgvictorino [excluded import path from args to aliased external commands](https://github.com/nushell/nushell/pull/14231), [correctly parsed table literals as lists](https://github.com/nushell/nushell/pull/14226), and [added support for binary input in `length`](https://github.com/nushell/nushell/pull/14224)
- Dorumin [removed a deref in `touch`](https://github.com/nushell/nushell/pull/14214)

## Documentation

- raphaelpra [fixed a typo in an example provided in custom_commands.md](https://github.com/nushell/nushell.github.io/pull/1622)
- weirdan [updated `VISUAL`/`EDITOR` order](https://github.com/nushell/nushell.github.io/pull/1621)
- NotTheDr01ds [made module chapter edits from review](https://github.com/nushell/nushell.github.io/pull/1620), and [fixed code-block line numbering](https://github.com/nushell/nushell.github.io/pull/1618)
- cablehead [added details on signal handling to the plugin protocol reference](https://github.com/nushell/nushell.github.io/pull/1619)
- vyadh [added Docker image usage](https://github.com/nushell/nushell.github.io/pull/1616)
- hustcer [upgraded shiki, vuepress and related plugins](https://github.com/nushell/nushell.github.io/pull/1615)
- rodvieirasilva [fixed prepend to append in coming_from_cmd.md](https://github.com/nushell/nushell.github.io/pull/1614)
- 132ikl [added documentation for sorting](https://github.com/nushell/nushell.github.io/pull/1568)

## Nu_Scripts

- bminer [fixed a bug where find_in globs were matching directories](https://github.com/nushell/nu_scripts/pull/980)

## reedline

- petricavalry [fixed wrong unit when splitting string](https://github.com/nushell/reedline/pull/839)

