# This week in Nushell #264

## Nushell

- Ancient77 [expanded multiple dots in path completions](https://github.com/nushell/nushell/pull/13725)
- fdncred [allowed tab characters to be retained with `find`](https://github.com/nushell/nushell/pull/13848), and [bumped rust version to 1.79.0](https://github.com/nushell/nushell/pull/13809)
- hustcer updated the release workflow: [bumped the Nu version](https://github.com/nushell/nushell/pull/13840),  [added `aarch64-unknown-linux-musl` and `armv7-unknown-linux-musleabihf` targets](https://github.com/nushell/nushell/pull/13800)
- devyn [fixed `try`: Added `set_last_error()` to `prepare_error_handler()` for IR eval](https://github.com/nushell/nushell/pull/13838), and [fixed remaining mismatch for env handling in IR](https://github.com/nushell/nushell/pull/13796)
- ayax79 [made `polars save` return an empty pipeline](https://github.com/nushell/nushell/pull/13833), [migrated polars commands away from macros, removed custom DataFrame comparison](https://github.com/nushell/nushell/pull/13829), and [added documentation explanation explaining how to select all columns with `polars col`](https://github.com/nushell/nushell/pull/13806)
- nome [added a --number flag to `split column`](https://github.com/nushell/nushell/pull/13831)
- T3sT3ro [changed `clear` to clear scrollback by default](https://github.com/nushell/nushell/pull/13821)
- IanManske [fixed IR for `try`](https://github.com/nushell/nushell/pull/13811)
- zhiburt [fixed a padding issue with header_on_border tables](https://github.com/nushell/nushell/pull/13808)
- WindSoilder [changed ctrl-k to `cuttolineend` event in Config](https://github.com/nushell/nushell/pull/13801), and [fixed `path exists` on a non-directory file](https://github.com/nushell/nushell/pull/13763)
- Bahex [added a new `metadata access` command for debugging](https://github.com/nushell/nushell/pull/13785)

## Documentation

- sgvictorino [fixed some broken anchor links](https://github.com/nushell/nushell.github.io/pull/1548)
- NotTheDr01ds [added `std` doc page](https://github.com/nushell/nushell.github.io/pull/1546), and [added `wrap` as a cast for table and record](https://github.com/nushell/nushell.github.io/pull/1545)

## Nu_Scripts

- OJarrisonn [fixed: `cargo clippy` linting flags need to accept strings](https://github.com/nushell/nu_scripts/pull/947)
- reinno [fixed(aws): Fixed select-aws-profile script functionality and style](https://github.com/nushell/nu_scripts/pull/946)

## reedline

- DenisGorbachev [fixed a typo](https://github.com/nushell/reedline/pull/827)

