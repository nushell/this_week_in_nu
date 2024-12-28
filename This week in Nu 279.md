# This week in Nushell #279

## Nushell

- NotTheDr01ds [added "short" Welcome Banner option](https://github.com/nushell/nushell/pull/14638)
- cosineblast [made `ls` collect metadata in a separate thread](https://github.com/nushell/nushell/pull/14627), and [added streaming to `get` and `reject`](https://github.com/nushell/nushell/pull/14622)
- WindSoilder [made du streaming](https://github.com/nushell/nushell/pull/14665)
- fdncred [updated the startup banner to respect `use_ansi_colors`](https://github.com/nushell/nushell/pull/14684)
- cptpiepmatz [added `config use-colors` to get evaluated color setting](https://github.com/nushell/nushell/pull/14683), [replaced `std::time::Instant` with `web_time::Instant`](https://github.com/nushell/nushell/pull/14668), [added content type metadata to `config nu` commands](https://github.com/nushell/nushell/pull/14666), and [added `auto` option for `config.use_ansi_coloring`](https://github.com/nushell/nushell/pull/14647)
- sgvictorino [fixed an issue with `cp` in FreeBSD builds](https://github.com/nushell/nushell/pull/14677)
- hustcer [fixed Docker image tests](https://github.com/nushell/nushell/pull/14671)
- hjetmundsen [removed trailing slash from symlink completion (issue #13275)](https://github.com/nushell/nushell/pull/14667)
- sholderbach bumped Nu versions ([1](https://github.com/nushell/nushell/pull/14661), [2](https://github.com/nushell/nushell/pull/14631))
- devyn [made the `--no-newline` test use `--no-config-file` as well](https://github.com/nushell/nushell/pull/14654), and [changed how `and` and `or` operations are compiled to IR to support custom values](https://github.com/nushell/nushell/pull/14653)
- Bahex [added `bytes split` command](https://github.com/nushell/nushell/pull/14652), [added binary input support to `chunks`](https://github.com/nushell/nushell/pull/14649), and [ran ENV_CONVERSIONS whenever it's modified](https://github.com/nushell/nushell/pull/14591)
- ayax79 [added Polars AWS S3 support](https://github.com/nushell/nushell/pull/14648)
- rikukiix [switched from serde_yaml to serde_yml](https://github.com/nushell/nushell/pull/14630)
- RobbingDaHood fixed several parser issues with comments](https://github.com/nushell/nushell/pull/14616)
- zhiburt [bumped tabled to 0.17](https://github.com/nushell/nushell/pull/14415)

## Documentation

- NotTheDr01ds [reverted codeblock theme](https://github.com/nushell/nushell.github.io/pull/1715), [disabled PrismJS](https://github.com/nushell/nushell.github.io/pull/1714), [fixed `config nu` reference](https://github.com/nushell/nushell.github.io/pull/1712), [added additions from full-changelog for NotTheDr01ds and WindSoilder](https://github.com/nushell/nushell.github.io/pull/1701), [updated multi-line editing and other features](https://github.com/nushell/nushell.github.io/pull/1691), and [updated Config Preview](https://github.com/nushell/nushell.github.io/pull/1690)
- hustcer [upgraded vuepress plugins and shiki, added ansi lang](https://github.com/nushell/nushell.github.io/pull/1713), and [refreshed Nu command docs for v0.101](https://github.com/nushell/nushell.github.io/pull/1687)
- jesper-olsen [updated dataframes.md](https://github.com/nushell/nushell.github.io/pull/1709), and [updated custom_commands.md](https://github.com/nushell/nushell.github.io/pull/1696)
- sholderbach [added command doc lint ignore for autogen maintainer](https://github.com/nushell/nushell.github.io/pull/1708), [cleared up the automated comment](https://github.com/nushell/nushell.github.io/pull/1707), [ensured command doc workflow fails](https://github.com/nushell/nushell.github.io/pull/1706), [fixed command doc (newline stuff)](https://github.com/nushell/nushell.github.io/pull/1705), [attempted to get the command doc comment bot working](https://github.com/nushell/nushell.github.io/pull/1704), [fixed release note anchors](https://github.com/nushell/nushell.github.io/pull/1703), and [summarized Stefan's contributions](https://github.com/nushell/nushell.github.io/pull/1702)
- IanManske [continued 0.101.0 release notes](https://github.com/nushell/nushell.github.io/pull/1695), and [added release notes for `0.101.0`](https://github.com/nushell/nushell.github.io/pull/1645)
- HartBlanc [fixed minor errors in book](https://github.com/nushell/nushell.github.io/pull/1694)
- 0x4D5352 [updated Nushell Book with copy-able examples](https://github.com/nushell/nushell.github.io/pull/1692)

## Nu_Scripts

- fdncred [updated oh-my.nu to respect use_ansi_coloring config setting](https://github.com/nushell/nu_scripts/pull/1003)
- AucaCoyan [fixed some parser issues with type signatures](https://github.com/nushell/nu_scripts/pull/1001)
- sholderbach [fixed table of contents generation for release notes](https://github.com/nushell/nu_scripts/pull/1000), and [fixed input-output signatures](https://github.com/nushell/nu_scripts/pull/999)

