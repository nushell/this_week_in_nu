# This week in Nushell #268

## Nushell

- 132ikl [reworked sorting and added cell path and closure comparators to `sort-by`](https://github.com/nushell/nushell/pull/13154)
- Kither12 [made completions faster](https://github.com/nushell/nushell/pull/14004)
- sgvictorino [added support for filesize arguments in `random` `binary`/`chars`](https://github.com/nushell/nushell/pull/14068), and [fixed parsing for certain strings with equal signs](https://github.com/nushell/nushell/pull/14053)
- NotTheDr01ds [corrected some wording](https://github.com/nushell/nushell/pull/14066), [fixed `--header-row` description](https://github.com/nushell/nushell/pull/14065), [made `banner` respect `use_ansi_coloring` setting](https://github.com/nushell/nushell/pull/14049), [implemented virtual `std` module subdirectories](https://github.com/nushell/nushell/pull/14040), [fixed `dirs` removal warning](https://github.com/nushell/nushell/pull/14029), and [enabled loading env when importing with `use std *`](https://github.com/nushell/nushell/pull/14012)
- fdncred [made `FooterMode::Auto` work](https://github.com/nushell/nushell/pull/14063), [hard-coded selection color to be `reverse`](https://github.com/nushell/nushell/pull/14052), [fixed `format date` by getting the env vars properly](https://github.com/nushell/nushell/pull/14037), updated reedline ([1](https://github.com/nushell/nushell/pull/14034), [2](https://github.com/nushell/nushell/pull/14017)), and [added unicode-width to `str stats`](https://github.com/nushell/nushell/pull/14014)
- WindSoilder [fixed $env.FILE_PWD and $env.CURRENT_FILE inside `use`](https://github.com/nushell/nushell/pull/13958), [reverted that after a bug was found](https://github.com/nushell/nushell/pull/14057), and [improved nushell's handling of external args surrounded by backtick quotes](https://github.com/nushell/nushell/pull/13910)
- IanManske [removed the deprecated `group` command](https://github.com/nushell/nushell/pull/14056), [fixed `try` printing when it is not the last pipeline element](https://github.com/nushell/nushell/pull/13992), and [standardized how config is updated](https://github.com/nushell/nushell/pull/13802)
- qfel [reduced nesting in the history command code](https://github.com/nushell/nushell/pull/14069), and [reduced duplication in history path construction](https://github.com/nushell/nushell/pull/13475)
- ayax79 [removed the CustomValue portion of CustomValue type name strings](https://github.com/nushell/nushell/pull/14054)
- hustcer [created a Sha256sum file for each release binary](https://github.com/nushell/nushell/pull/14050), and [replaced the old `encode base64` and `decode base64` with new-base64 commands](https://github.com/nushell/nushell/pull/14018)
- quadristan [improved umkdir tests to get umask instead of assuming it](https://github.com/nushell/nushell/pull/14046), and [added an example for escaped regexes in `str replace`](https://github.com/nushell/nushell/pull/14038)
- 1256-bits [added ls colors to cjs and mjs files](https://github.com/nushell/nushell/pull/14028)
- JustForFun88 [improved keybinding parsing for Unicode support](https://github.com/nushell/nushell/pull/14020)
- sdmoralesma [fixed the example for hide-env](https://github.com/nushell/nushell/pull/14013)

## Documentation

- JustForFun88 [added changes to release notes for version 0.99.0 due to nushell/#14020](https://github.com/nushell/nushell.github.io/pull/1583)
- NotTheDr01ds [turned back on line-numbers](https://github.com/nushell/nushell.github.io/pull/1579), and [added std-lib breaking changes](https://github.com/nushell/nushell.github.io/pull/1578)
- LoicRiegel [added French translation [#1532]](https://github.com/nushell/nushell.github.io/pull/1559)

## Nu_Scripts

- HirschBerge [updated `ani-cli` completions](https://github.com/nushell/nu_scripts/pull/969)

## reedline

- blindFS [attempted to fix multiline prompt resize issue](https://github.com/nushell/reedline/pull/841)
- andylokandy [fixed external printer not printing until key press](https://github.com/nushell/reedline/pull/840)
- uek-1 [made can_partially_complete() only complete when suggesting more than the input](https://github.com/nushell/reedline/pull/834)

