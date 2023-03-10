# This week in Nushell #185


## Nushell


- rgwood [removed `get -i` from default env file](https://github.com/nushell/nushell/pull/8390), and [Fix the SQLite feature name in `version`](https://github.com/nushell/nushell/pull/8381), and [Revert to notify v4](https://github.com/nushell/nushell/pull/8367), and [Fix `to json` for SQLite databases](https://github.com/nushell/nushell/pull/8343), and [Remove body parameters from `http get`](https://github.com/nushell/nushell/pull/8336), and [Put a lock around `cargo build` invocations for plugin tests](https://github.com/nushell/nushell/pull/8333), and [Add SSL tests for `http get`](https://github.com/nushell/nushell/pull/8327)
- fdncred [updated a test to use testbin versus external echo](https://github.com/nushell/nushell/pull/8387), and [fixed an error message that popped up after landing](https://github.com/nushell/nushell/pull/8356), and [point nushell at latest reedline and nu-ansi-term main](https://github.com/nushell/nushell/pull/8342)
- klementievdmitry [reworked `help aliases`](https://github.com/nushell/nushell/pull/8372)
- NotLebedev created [Hide 7925](https://github.com/nushell/nushell/pull/8359)
- amtoine created [FEATURE: add the startup time to `$nu`](https://github.com/nushell/nushell/pull/8353), and [FIX: redirect to `encode base64` as `hash bash64` is deprecated](https://github.com/nushell/nushell/pull/8351), and [FEATURE: add the example results to the scope](https://github.com/nushell/nushell/pull/8319), and [FEATURE: add a `path add` to the standard library](https://github.com/nushell/nushell/pull/8303)
- sholderbach created [Document and critically review `ShellError` variants - Ep. 3](https://github.com/nushell/nushell/pull/8340), and [Document and critically review `ShellError` variants - Ep. 2](https://github.com/nushell/nushell/pull/8326)
- bobhy [fixed 8244 -- store timestamps with nanosecond resolution (consistently)](https://github.com/nushell/nushell/pull/8337)
- stormasm created [Cratification: Test Infrastructure Support Part One](https://github.com/nushell/nushell/pull/8335)
- dependabot[bot] created [Bump scraper from 0.14.0 to 0.15.0](https://github.com/nushell/nushell/pull/8331), and [Bump rust-embed from 6.4.1 to 6.6.0](https://github.com/nushell/nushell/pull/8330), and [Bump tempfile from 3.3.0 to 3.4.0](https://github.com/nushell/nushell/pull/8329), and [Bump rayon from 1.6.1 to 1.7.0](https://github.com/nushell/nushell/pull/8328)
- FilipAndersson245 [changed Reqwest to Ureq.](https://github.com/nushell/nushell/pull/8320)
- StevenDoesStuffs [added is-interactive and is-login to NuVariable and allow running scripts with -i](https://github.com/nushell/nushell/pull/8306)
- dmatos2012 created [Error out when config.nu has no editor configured](https://github.com/nushell/nushell/pull/8282)

## Documentation


- samrland created [Update externs.md](https://github.com/nushell/nushell.github.io/pull/813)
- amtoine created [FIX: remove ANSI escape sequences when the output is a `string`](https://github.com/nushell/nushell.github.io/pull/812), and [add the example results to the documentation pages](https://github.com/nushell/nushell.github.io/pull/807), and [REFACTOR: add documentation to and clean up the `make_docs.nu` script](https://github.com/nushell/nushell.github.io/pull/803)
- fdncred created [add fish_completer example](https://github.com/nushell/nushell.github.io/pull/811)
- presidento created [Book: add links to commands](https://github.com/nushell/nushell.github.io/pull/810)
- bobhy created [release notes for #8244; don't merge till the fix itself is merged](https://github.com/nushell/nushell.github.io/pull/809)
- kejadlen created [Remove more references to `--numbered`](https://github.com/nushell/nushell.github.io/pull/806)

## Nu_Scripts


- visr created [conda activate base if env_name not given](https://github.com/nushell/nu_scripts/pull/400)
- dedebenui created [`conda.nu` : changed `insert` to `merge`](https://github.com/nushell/nu_scripts/pull/399)
- chtenb created [Make commands optional](https://github.com/nushell/nu_scripts/pull/398)
