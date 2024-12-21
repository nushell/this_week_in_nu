# This week in Nushell #278

## Nushell

- 132ikl [added a `merge deep` command for merging nested data](https://github.com/nushell/nushell/pull/14525)
- fdncred added a `config flatten` command ([1](https://github.com/nushell/nushell/pull/14621) [2](https://github.com/nushell/nushell/pull/14639), [3](https://github.com/nushell/nushell/pull/14635)), [added a `view blocks` command for debugging Nu](https://github.com/nushell/nushell/pull/14610), [tweaked polars join for better cross joins](https://github.com/nushell/nushell/pull/14586), improved `view source` ([1](https://github.com/nushell/nushell/pull/14609), [2](https://github.com/nushell/nushell/pull/14624)), and reverted a few PRs ([1](https://github.com/nushell/nushell/pull/14598), [2](https://github.com/nushell/nushell/pull/14606))
- sholderbach [removed `pub` on some command internals](https://github.com/nushell/nushell/pull/14636) and [removed unused `sample_login.nu` file](https://github.com/nushell/nushell/pull/14632) 
- NotTheDr01ds [set `split-by` doc category to "deprecated"](https://github.com/nushell/nushell/pull/14633), [added shape_garbage](https://github.com/nushell/nushell/pull/14626), [added version info to startup banner](https://github.com/nushell/nushell/pull/14625), [removed duplicate version line](https://github.com/nushell/nushell/pull/14611), [fixed doc files](https://github.com/nushell/nushell/pull/14608), [added missing color_config settings](https://github.com/nushell/nushell/pull/14603), and [moved additional env vars out of default_env and updated some transient prompt vars](https://github.com/nushell/nushell/pull/14579)
- WindSoilder [removed `-a/-all` flag in du](https://github.com/nushell/nushell/pull/14618) and [updated shadow-rs to 0.37](https://github.com/nushell/nushell/pull/14617)
- Bahex [added tests for `path self`](https://github.com/nushell/nushell/pull/14607), [removed `content_type` metadata from pipeline after `from ...` commands](https://github.com/nushell/nushell/pull/14602), [changed closure signature in `std/iter scan` to be consistent with `reduce`](https://github.com/nushell/nushell/pull/14596), [removed the deprecated index argument from filter commands' closure signature](https://github.com/nushell/nushell/pull/14594), and [added an example demonstrating accumulator as pipeline input in `reduce` docs](https://github.com/nushell/nushell/pull/14593)
- PerchunPak [fixed issues in the example configs](https://github.com/nushell/nushell/pull/14601)
- ayax79 [improved handling of columns with null values](https://github.com/nushell/nushell/pull/14588) and [added flag --coalesce-columns to allow columns to be coalesced on full joins](https://github.com/nushell/nushell/pull/14578)
- cptpiepmatz [fixed `commands::network::http::*::*_timeout` tests on non-English systems](https://github.com/nushell/nushell/pull/14640)
- hustcer [fixed a CI error for `polars profile`](https://github.com/nushell/nushell/pull/14642)

## Documentation

- Bahex [added release notes for Bahex PRs](https://github.com/nushell/nushell.github.io/pull/1689)
- 0x4D5352 [fixed outdated commands in `coming_from_bash.md`](https://github.com/nushell/nushell.github.io/pull/1688)
- SOF3 [updated documentation on internal nushell commands using structured data](https://github.com/nushell/nushell.github.io/pull/1686)
- RobbingDaHood [fixed some examples for Command Output in Nushell](https://github.com/nushell/nushell.github.io/pull/1683)
- hustcer [upgraded shiki, vuepress and vuepress plugins](https://github.com/nushell/nushell.github.io/pull/1682)
- PerchunPak [fixed typo in moving_around.md](https://github.com/nushell/nushell.github.io/pull/1681)
- IanManske [started release notes for 0.101.0](https://github.com/nushell/nushell.github.io/pull/1680)
- prx0 [updated creating_errors.md to use $span variable directly in example](https://github.com/nushell/nushell.github.io/pull/1679)
- NotTheDr01ds [added "return value" topics to "Thinking in Nu"](https://github.com/nushell/nushell.github.io/pull/1677) and [added release notes for NotTheDr01ds PRs](https://github.com/nushell/nushell.github.io/pull/1673)

## Nu_Scripts

- WindSoilder [made conda activate expand $env.PATH to a connection of absolute paths](https://github.com/nushell/nu_scripts/pull/998)
- DualHappiness [fixed `delete-session` no auto target](https://github.com/nushell/nu_scripts/pull/997) and [updated zellij completions](https://github.com/nushell/nu_scripts/pull/994)
- NotTheDr01ds [fixed invalid type signature](https://github.com/nushell/nu_scripts/pull/996) and [added and updated new config files](https://github.com/nushell/nu_scripts/pull/995)

## reedline

- sholderbach [fixed clippy lints](https://github.com/nushell/reedline/pull/861)

