# This week in Nushell #201


## Nushell

- fdncred [updated the ide-check help text](https://github.com/nushell/nushell/pull/9559), [added input_output type to `input list` to return string](https://github.com/nushell/nushell/pull/9557), and [updated sqlparser dep to 0.34](https://github.com/nushell/nushell/pull/9549), and [convert a string to a raw binary string of 0s and 1s](https://github.com/nushell/nushell/pull/9534)
- jntrnr [added a better error message if env var is used as var](https://github.com/nushell/nushell/pull/9522), and [improved type hovers](https://github.com/nushell/nushell/pull/9515)
- WindSoilder [fixed cd permissions when user belongs to folder group](https://github.com/nushell/nushell/pull/9531), and [`rename`: add -b flag to support closure input](https://github.com/nushell/nushell/pull/8948)
- nibon7 [fixed cargo-build-nu](https://github.com/nushell/nushell/pull/9571), and [refactored cargo-build-nu](https://github.com/nushell/nushell/pull/9554), and [fixed release workflows](https://github.com/nushell/nushell/pull/9542)
- zhiburt [fixed colours in table and table -e](https://github.com/nushell/nushell/pull/9552)
- sholderbach [bumped Nu to `0.82.1` dev version](https://github.com/nushell/nushell/pull/9543), and [pinned reedline to `0.21` for release](https://github.com/nushell/nushell/pull/9532), and [Bump version for `0.82.0` release](https://github.com/nushell/nushell/pull/9530), and [Skip `strum` in regular `nu-protocol` build](https://github.com/nushell/nushell/pull/9445)
- Yethal [pre-registered plugins inside docker container](https://github.com/nushell/nushell/pull/9533)
- stormasm [modified the bits command in nu-cmd-extra to improve visibility](https://github.com/nushell/nushell/pull/9516)
- Taywee added the ability to [format negative datetimes with rfc3339 (#9501)](https://github.com/nushell/nushell/pull/9502)
- atahabaki created [a new subcommand for str, str-expand.](https://github.com/nushell/nushell/pull/9290)
- TrMen added [tests for examples of `use`](https://github.com/nushell/nushell/pull/9032)

## Documentation

- waldyrious [fixed typo in 2023-06-27-nushell_0_82.md](https://github.com/nushell/nushell.github.io/pull/967)
- hustcer created [Refresh commands docs for Nu v0.82](https://github.com/nushell/nushell.github.io/pull/965)
- sholderbach created [Fix reference to latest release in the nightly section](https://github.com/nushell/nushell.github.io/pull/964), and [Fix blog post link](https://github.com/nushell/nushell.github.io/pull/963), and [Add blogpost planning towards 1.0 and slowing releases](https://github.com/nushell/nushell.github.io/pull/957), and [Release notes for `0.82.0` release](https://github.com/nushell/nushell.github.io/pull/945)
- tminich created [Flags with dashes](https://github.com/nushell/nushell.github.io/pull/962)
- eopb created [Remove reference to `build-string` from `working_with_strings.md`](https://github.com/nushell/nushell.github.io/pull/961)
- JoaquinTrinanes created [Fix custom completion scripts](https://github.com/nushell/nushell.github.io/pull/959)
- mh-trimble created [Update aliases.md and setup.md](https://github.com/nushell/nushell.github.io/pull/951)

## Nu_Scripts

- bobhy created [full line v2; with git status!](https://github.com/nushell/nu_scripts/pull/542)
- fj0r created [upgrade to 0.82](https://github.com/nushell/nu_scripts/pull/539)
- Neur1n created [fix: fix default fg and bg coloring for hl.nu](https://github.com/nushell/nu_scripts/pull/537)

## reedline

- nibon7 created [Remove unneeded features of chrono](https://github.com/nushell/reedline/pull/599)
- WindSoilder created [always disable bracketed paste after read_line](https://github.com/nushell/reedline/pull/598)
- sholderbach created [Bump version for `0.21.0` release](https://github.com/nushell/reedline/pull/596)
