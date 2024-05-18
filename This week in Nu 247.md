# This week in Nushell #247


## Nushell

- IanManske made a huge internal change, replacing `ExternalStream` with a new `ByteStream` type ([1](https://github.com/nushell/nushell/pull/12774), [2](https://github.com/nushell/nushell/pull/12887), [3](https://github.com/nushell/nushell/pull/12886)). Also lots of other improvements: [removed usages of `Call::positional_nth`](https://github.com/nushell/nushell/pull/12871), [fixed a `char` panic](https://github.com/nushell/nushell/pull/12867), [removed stack debug assert](https://github.com/nushell/nushell/pull/12861), [preserved metadata in more places](https://github.com/nushell/nushell/pull/12848), [fixed a `sys` panic](https://github.com/nushell/nushell/pull/12846), [updated the PR template](https://github.com/nushell/nushell/pull/12838), [fixed custom converters with `save`](https://github.com/nushell/nushell/pull/12833),  and [added `Span` merging functions](https://github.com/nushell/nushell/pull/12511).
- devyn [excluded polars from ensure_plugins_built() for performance reasons](https://github.com/nushell/nushell/pull/12896), [fixed the way the output of `table` is printed in `print()`](https://github.com/nushell/nushell/pull/12895), and [modified `collect` to not require a closure](https://github.com/nushell/nushell/pull/12788).
- WindSoilder [allowed defining `it` as a variable inside closures](https://github.com/nushell/nushell/pull/12888), [enabled passing float values to custom commands](https://github.com/nushell/nushell/pull/12879), and [improved messages for incomplete string errors](https://github.com/nushell/nushell/pull/12868).
- francesco-gaglione [merged tests to produce a single binary](https://github.com/nushell/nushell/pull/12826).
- fdncred [synced up with reedline changes](https://github.com/nushell/nushell/pull/12881) and [made it clearer what is being loaded with --log-level info](https://github.com/nushell/nushell/pull/12875).
- ayax79 [fixed syntax shape requirements for --quantiles option for polars summary](https://github.com/nushell/nushell/pull/12878) and [allowed custom value operations to work on eager and lazy dataframes interchangeably](https://github.com/nushell/nushell/pull/12819).
- NotTheDr01ds [fixed a small error in the help examples for the get command](https://github.com/nushell/nushell/pull/12877), [improved help for `each while`](https://github.com/nushell/nushell/pull/12876), [added search terms for the `compact` command](https://github.com/nushell/nushell/pull/12864), and [added an example and search term for 'repeat' to the `fill` command](https://github.com/nushell/nushell/pull/12844).
- cablehead [added a passing test for interactivity on slow pipelines](https://github.com/nushell/nushell/pull/12865).
- ExaltedBagel [fixed a panic when exploring an empty dictionary](https://github.com/nushell/nushell/pull/12860) and [fixed improperly escaped strings in `stor insert`](https://github.com/nushell/nushell/pull/12820).
- cptpiepmatz [added `Stack::stdout_file` and `Stack::stderr_file` to capture stdout/-err of external commands](https://github.com/nushell/nushell/pull/12857).

## Documentation

- suimong [changed usages of `$nu.scope` to the `scope` command](https://github.com/nushell/nushell.github.io/pull/1406).
- abusch [updated 2024-05-15-top-nushell-hacks.md](https://github.com/nushell/nushell.github.io/pull/1405).
- NotTheDr01ds [refactored the language guide](https://github.com/nushell/nushell.github.io/pull/1403).
- fdncred [authored a bashism blog entry](https://github.com/nushell/nushell.github.io/pull/1402) and [compiled the top 5 nushell hacks](https://github.com/nushell/nushell.github.io/pull/1400).
- github-actions[bot] [compressed images](https://github.com/nushell/nushell.github.io/pull/1401).
- shenjiangqiu [noted that users should use ...$spans instead of $spans in carapace completer](https://github.com/nushell/nushell.github.io/pull/1399).
- volcaxiao [[fixed]: corrected syntax error in zh-CN/README.md #1395](https://github.com/nushell/nushell.github.io/pull/1397).
- finnala [fixed a Russian link in the configuration file](https://github.com/nushell/nushell.github.io/pull/1396).

## Nu_Scripts

- CarrotManMatt [added more detailed poetry completions](https://github.com/nushell/nu_scripts/pull/838).
- 39555 [ported root `before_v0.60/*.nu` scripts (issue #221)](https://github.com/nushell/nu_scripts/pull/837), [ported `before_v0.60/coloring` folder (issue #221)](https://github.com/nushell/nu_scripts/pull/836), [ported `before_v0.60/fun` folder (issue #221)](https://github.com/nushell/nu_scripts/pull/835), [ported `before_v0.60/cool_oneliners` folder](https://github.com/nushell/nu_scripts/pull/831), and [ported `before_v0.60/make_release` folder](https://github.com/nushell/nu_scripts/pull/830).

## reedline

- fdncred [fixed some new clippy warnings](https://github.com/nushell/reedline/pull/790).
