# This week in Nushell #248


## Nushell

- YizhePKU [rewrote `run_external.rs`](https://github.com/nushell/nushell/pull/12921) and [removed `std::env::set_current_dir()` call from `EngineState::merge_env()`](https://github.com/nushell/nushell/pull/12922).
- IanManske [allowed byte streams with unknown type to be compatible with binary](https://github.com/nushell/nushell/pull/12959), [stopped propagating glob creation error for external args](https://github.com/nushell/nushell/pull/12955), [used `cwd` in `grid`](https://github.com/nushell/nushell/pull/12947), [removed list support in `with-env`](https://github.com/nushell/nushell/pull/12939), [took owned `Read` and `Write`](https://github.com/nushell/nushell/pull/12909), [made `get_full_help` take `&dyn Command`](https://github.com/nushell/nushell/pull/12903), [cleared environment for child `Command`s](https://github.com/nushell/nushell/pull/12901), and [removed the dataframes crate and feature](https://github.com/nushell/nushell/pull/12889).
- devyn [made `from json --objects` streaming](https://github.com/nushell/nushell/pull/12949), [updated mimalloc to 0.1.42](https://github.com/nushell/nushell/pull/12919), [implemented streaming I/O for CSV and TSV commands](https://github.com/nushell/nushell/pull/12918), [added string/binary type color to `ByteStream`](https://github.com/nushell/nushell/pull/12897), and [added support for the `ps` command on FreeBSD, NetBSD, and OpenBSD](https://github.com/nushell/nushell/pull/12892).
- fdncred [made the polars plugin use mimalloc](https://github.com/nushell/nushell/pull/12967) and [added `math min` and `math max` to the `bench` command](https://github.com/nushell/nushell/pull/12913).
- WindSoilder [fixed `std help`](https://github.com/nushell/nushell/pull/12943), [added some completion tests](https://github.com/nushell/nushell/pull/12908), and [fixed range semantic in detect_columns, str substring, str index-of](https://github.com/nushell/nushell/pull/12894).
- rgwood did a bunch of refactoring+simplification for `explore`: [1](https://github.com/nushell/nushell/pull/12940), [2](https://github.com/nushell/nushell/pull/12920), [3](https://github.com/nushell/nushell/pull/12915).
- kubouch [fixed a wrong column name](https://github.com/nushell/nushell/pull/12937) and [made small improvements to `debug profile`](https://github.com/nushell/nushell/pull/12930).
- NotTheDr01ds [added a completer for std help](https://github.com/nushell/nushell/pull/12929).
- sholderbach [removed unused dependencies](https://github.com/nushell/nushell/pull/12917).

## Documentation

- jaudiger [resolved a few typos](https://github.com/nushell/nushell.github.io/pull/1410), [updated export alias in overlays.md](https://github.com/nushell/nushell.github.io/pull/1409), and [corrected the link pointing to the command reduce](https://github.com/nushell/nushell.github.io/pull/1408).

## Nu_Scripts

- 39555 [ported `before_v0.60/progress_bar`, `before_v0.60/weather`, `before_v0.60/webscrapping`](https://github.com/nushell/nu_scripts/pull/846) and [ported `before_v0.60/math`, `before_v0.60/parsing`, `before_v0.60/git`](https://github.com/nushell/nu_scripts/pull/844).
- bobhy [fixed regressions noted in 0.93.1 from 0.83:](https://github.com/nushell/nu_scripts/pull/843).
- OJarrisonn [added `bend` completions](https://github.com/nushell/nu_scripts/pull/842).
- ptazithos [completed runnables(bin & scripts) for yarn](https://github.com/nushell/nu_scripts/pull/841).
- nekowinston [adjusted for nushell `commandline` syntax deprecation](https://github.com/nushell/nu_scripts/pull/840).
- WindSoilder [updated conda.nu to use (sys host) instead of (sys).host](https://github.com/nushell/nu_scripts/pull/839).
