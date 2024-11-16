# This week in Nushell #273

## Nushell

- musicinmybrain [updated rstest from 0.18 to 0.23 (the current version)](https://github.com/nushell/nushell/pull/14350)
- ayax79 [added support for converting polars decimal values to nushell values](https://github.com/nushell/nushell/pull/14343)
- NotTheDr01ds [added proper config defaults for hooks](https://github.com/nushell/nushell/pull/14341), [fixed a binary example and added one for text uploads](https://github.com/nushell/nushell/pull/14307), [fixed ignored `into datetime` test](https://github.com/nushell/nushell/pull/14302), [allowed duration to be added to date](https://github.com/nushell/nushell/pull/14295), and [fixed multipart/form-data post example](https://github.com/nushell/nushell/pull/14291)
- Bahex [added support for multiple groupers to `group-by`](https://github.com/nushell/nushell/pull/14337)
- userwiths [fixed inconsistency in `ls` sort-order](https://github.com/nushell/nushell/pull/13875)
- sholderbach [cut down unnecessary lint allows](https://github.com/nushell/nushell/pull/14335), and [pinned reedline to `0.37.0` release](https://github.com/nushell/nushell/pull/14317)
- hustcer [bumped to dev version 0.100.1](https://github.com/nushell/nushell/pull/14328), [downgraded softprops/action-gh-release to 2.0.5](https://github.com/nushell/nushell/pull/14327), and [bumped version to `0.100.0`](https://github.com/nushell/nushell/pull/14312)
- sgvictorino [made `ls` return "Permission denied" for CWD instead of empty results](https://github.com/nushell/nushell/pull/14310), and [skipped `test_iteration_errors` if `/root` is missing](https://github.com/nushell/nushell/pull/14299)
- fdncred [allowed nuscripts to be run again on windows with assoc/ftype](https://github.com/nushell/nushell/pull/14318), and [ignored without_timezone test for now](https://github.com/nushell/nushell/pull/14297)
- WindSoilder [added a test to ensure that functions can't use mutable variables](https://github.com/nushell/nushell/pull/14314)
- atahabaki [upgraded bracoxide to v0.1.4 (fixes #14290)](https://github.com/nushell/nushell/pull/14296)
- devyn [removed the `NU_DISABLE_IR` option](https://github.com/nushell/nushell/pull/14293)
- anomius [updated seq char to work on all characters](https://github.com/nushell/nushell/pull/14261)

## Documentation

- hustcer [upgraded shiki and vuepress plugins](https://github.com/nushell/nushell.github.io/pull/1633), [updated release note by scripts](https://github.com/nushell/nushell.github.io/pull/1628), and [refreshed Nu command docs for v0.100](https://github.com/nushell/nushell.github.io/pull/1625)
- NotTheDr01ds [provided more specific information about std/log use in modules](https://github.com/nushell/nushell.github.io/pull/1630)
- Jasha10 [updated direnv.md to use ENV_CONVERSIONS](https://github.com/nushell/nushell.github.io/pull/1629)
- IanManske [made release notes changes for 0.100.0](https://github.com/nushell/nushell.github.io/pull/1627), [started 0.100.0 release notes](https://github.com/nushell/nushell.github.io/pull/1626), and [added release notes for `0.100.0`](https://github.com/nushell/nushell.github.io/pull/1617)
- heinwol [fixed wrong link in working_with_records.md](https://github.com/nushell/nushell.github.io/pull/1624)

## Nu_Scripts

- chanmaoganda [added basic docker compose support: up down stop](https://github.com/nushell/nu_scripts/pull/979)

## reedline

- musicinmybrain [updated rstest to 0.23.0, the current version](https://github.com/nushell/reedline/pull/852)
- sholderbach [bumped version for `0.37.0` release](https://github.com/nushell/reedline/pull/851), and [fixed forgotten `Cargo.lock`](https://github.com/nushell/reedline/pull/850)

