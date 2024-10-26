# This week in Nushell #270

## Nushell

- fdncred [added `command_type` to help](https://github.com/nushell/nushell/pull/14165), [added `name` to `$env.config.keybindings`](https://github.com/nushell/nushell/pull/14159), [made adding newlines with `to text` more consistent and opt-out-able](https://github.com/nushell/nushell/pull/14158), [updated reedline](https://github.com/nushell/nushell/pull/14146), [added metadata on `open --raw` with bytestreams](https://github.com/nushell/nushell/pull/14141), [tried to fix osc633 escaping yet again](https://github.com/nushell/nushell/pull/14140), [added `start_time` to `ps -l` on macos](https://github.com/nushell/nushell/pull/14127), and [added is_const to `help commands` and `scope commands`](https://github.com/nushell/nushell/pull/14125)
- sholderbach [bumped `brotli` to 6.0.0](https://github.com/nushell/nushell/pull/14161), [made the contributor image wider](https://github.com/nushell/nushell/pull/14138), [bumped the version to 0.99.2](https://github.com/nushell/nushell/pull/14136), and [added slice as a search term on `range`](https://github.com/nushell/nushell/pull/14128)
- ayax79 [upgraded to polars 0.43](https://github.com/nushell/nushell/pull/14148)
- hustcer [added a GitHub action to CI to add milestones automatically](https://github.com/nushell/nushell/pull/14131)
- sgvictorino [fixed a bug when exporting constants with type signatures in modules](https://github.com/nushell/nushell/pull/14118), and [added a error when closure param lists aren't terminated by `|`](https://github.com/nushell/nushell/pull/14095)
- PhotonBursted [implemented defensive handling of errors when transposing](https://github.com/nushell/nushell/pull/14096)
- adaschma [let `url build_query` accept records with lists of strings](https://github.com/nushell/nushell/pull/14073)
- zhiburt [introduced footer_inheritance option to table rendering](https://github.com/nushell/nushell/pull/14070)
- Kither12 [fixed a panic if tokens are placed after a redirection](https://github.com/nushell/nushell/pull/14035)
- JoaquinTrinanes [fixed a bug in `range contains`](https://github.com/nushell/nushell/pull/14011)

## Documentation

- IanManske [added release notes for `0.99.1`](https://github.com/nushell/nushell.github.io/pull/1591)

## Nu_Scripts

- AntoineSebert [removed now unnecessary `-b` flag](https://github.com/nushell/nu_scripts/pull/977)

## reedline

- YizhePKU [reduced typing latency caused by `POLL_WAIT`](https://github.com/nushell/reedline/pull/846)

