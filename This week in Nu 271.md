# This week in Nushell #271

## Nushell

- Kissaki [improved comment wording in run_external.rs](https://github.com/nushell/nushell/pull/14230), and [fixed comment typos in run_external.rs](https://github.com/nushell/nushell/pull/14229)
- vyadh [added tests for new Alpine and Debian image builds](https://github.com/nushell/nushell/pull/14225), and [added a Debian Dockerfile](https://github.com/nushell/nushell/pull/14193)
- WindSoilder [prevented subcommand execution when surrounded with backtick quotes](https://github.com/nushell/nushell/pull/14210)
- hustcer [added a RELEASE_QUERY_API build arg for Dockerfiles](https://github.com/nushell/nushell/pull/14209), and [updated the dockerfile for Alpine](https://github.com/nushell/nushell/pull/14191)
- hacker-DOM [allowed using function keys F21-F35 for keybindings](https://github.com/nushell/nushell/pull/14201)
- aionescu [dropped `once_cell` dependency](https://github.com/nushell/nushell/pull/14198), [improved `CellPath` display output](https://github.com/nushell/nushell/pull/14197), [fixed quoting in `to nuon` and refactored quoting functions](https://github.com/nushell/nushell/pull/14180), and [added `?` for optional entries when displaying `CellPath`s](https://github.com/nushell/nushell/pull/14042)
- NotTheDr01ds did a bunch of work related to escape sequences: [added previews of attributes to `ansi -l` (e.g., bold, dimmed, blink, etc.)](https://github.com/nushell/nushell/pull/14196), [fixed the name for `ansi clear_entire_screen_plus_buffer`](https://github.com/nushell/nushell/pull/14184), and [sent both 2J and 3J on clear](https://github.com/nushell/nushell/pull/14181)
- ofek [ensured default config files end with a new line](https://github.com/nushell/nushell/pull/14192)
- sgvictorino [added support for table literal syntax in `join` right-table argument](https://github.com/nushell/nushell/pull/14190)
- fdncred [allowed OEM code pages to be used to decode text](https://github.com/nushell/nushell/pull/14187)
- friaes [updated `stor insert` to accept lists](https://github.com/nushell/nushell/pull/14175)
- Bahex [provided a common implementation for query string conversions in `url join` and `url build-query`](https://github.com/nushell/nushell/pull/14173)
- qfel [added the history import command (again)](https://github.com/nushell/nushell/pull/14083)
- blindFS [fixed LSP non-ASCII character offset issues](https://github.com/nushell/nushell/pull/14002)

## Documentation

- NotTheDr01ds [changed "local environment" example (yet again!)](https://github.com/nushell/nushell.github.io/pull/1612), [fixed Creating Modules code example (a bit further)](https://github.com/nushell/nushell.github.io/pull/1610), [updated "Working with Tables" - added info on "index renaming" and the table command](https://github.com/nushell/nushell.github.io/pull/1600), [fixed type signatures on custom commands](https://github.com/nushell/nushell.github.io/pull/1598), and [rewrote Module chapter](https://github.com/nushell/nushell.github.io/pull/1597)
- Kissaki [fixed 'Creating Modules' code examples](https://github.com/nushell/nushell.github.io/pull/1609), [improved Nerd Fonts docs](https://github.com/nushell/nushell.github.io/pull/1607), and [fixed typo in code example](https://github.com/nushell/nushell.github.io/pull/1606)
- vyadh [added candidate naming convention to the style guide](https://github.com/nushell/nushell.github.io/pull/1601), and [added example showing discovery and running of test commands](https://github.com/nushell/nushell.github.io/pull/1594)
- amkhlv [wrapped script in "def main [] {...}"](https://github.com/nushell/nushell.github.io/pull/1599)
- kubouch [removed unsupported syntax from type signatures](https://github.com/nushell/nushell.github.io/pull/1596)
- victorhck [updated spanish Readme translation](https://github.com/nushell/nushell.github.io/pull/1589)

## Nu_Scripts

- lizclipse [fixed network/sockets command](https://github.com/nushell/nu_scripts/pull/978)

