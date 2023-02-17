# This week in Nushell #182

## Nushell

- fdncred created [update colors in dark theme](https://github.com/nushell/nushell/pull/8090), and [fix rename when it is passed an empty column list to rename](https://github.com/nushell/nushell/pull/8086), and [allow date grouping in group-by](https://github.com/nushell/nushell/pull/8084), and [move ast command to the debug group](https://github.com/nushell/nushell/pull/8077), and [relocate debug commands](https://github.com/nushell/nushell/pull/8071), and [update cargo wix to 0.3.4](https://github.com/nushell/nushell/pull/8048), and [add benchmark to deprecated commands](https://github.com/nushell/nushell/pull/8046), and [add a new inspect command for more debugging](https://github.com/nushell/nushell/pull/8028), and [rename benchmark to timeit](https://github.com/nushell/nushell/pull/8018)
- stormasm created [remove spurious use from default_context.rs](https://github.com/nushell/nushell/pull/8073)
- sholderbach created [Make patch coverage check informational only](https://github.com/nushell/nushell/pull/8069), and [Add a `codecov.yml` configuration](https://github.com/nushell/nushell/pull/8059), and [Disable auto-benchmark harness for crates](https://github.com/nushell/nushell/pull/8057), and [Minor clippy: inline format string](https://github.com/nushell/nushell/pull/8043), and [Another shot at trying to setup codecov](https://github.com/nushell/nushell/pull/7948)
- jntrnr created [Bare word improvements](https://github.com/nushell/nushell/pull/8066)
- dependabot[bot] created [Bump roxmltree from 0.17.0 to 0.18.0](https://github.com/nushell/nushell/pull/8065), and [Bump rstest from 0.15.0 to 0.16.0](https://github.com/nushell/nushell/pull/8064), and [Bump proptest from 1.0.0 to 1.1.0](https://github.com/nushell/nushell/pull/8063)
- WindSoilder created [support multiplication operation on string and list values](https://github.com/nushell/nushell/pull/8061), and [Move some `from xxx` commands to plugin](https://github.com/nushell/nushell/pull/7942)
- kubouch created [Fix hidden env vars not being hidden in closures](https://github.com/nushell/nushell/pull/8055), and [Benchmark each pipeline element](https://github.com/nushell/nushell/pull/7854)
- bobhy created [Improve error when regex rejects pattern.  Resolution of #8037](https://github.com/nushell/nushell/pull/8050), and [Syntax errors for string and int](https://github.com/nushell/nushell/pull/7952)
- ryand67 created [#8027 Hide implementation details in invalid cd call](https://github.com/nushell/nushell/pull/8049)
- zhiburt created [nu-table/ Fix table --expand issue when table with no header involved ](https://github.com/nushell/nushell/pull/8045), and [nu-table/ table --collapse style fix](https://github.com/nushell/nushell/pull/8041)
- amtoine created [remove the `--encoding` option from `register` in the examples](https://github.com/nushell/nushell/pull/8038)
- dmatos2012 created [Support URLs in `start` command](https://github.com/nushell/nushell/pull/7799)

## Extension

- glcraft created [Fix `use` syntax ](https://github.com/nushell/vscode-nushell-lang/pull/79)

## Documentation

- hustcer created [fix #768 for zh-CN translation](https://github.com/nushell/nushell.github.io/pull/787), and [fix `all` and `any` usage examples, close #758](https://github.com/nushell/nushell.github.io/pull/786), and [fix #781 and update some node modules](https://github.com/nushell/nushell.github.io/pull/783)
- Hofer-Julian created [Move `book/commands` to `commands/commands`](https://github.com/nushell/nushell.github.io/pull/785), and [Move command reference to navbar](https://github.com/nushell/nushell.github.io/pull/782)
- msmart created [Fix typos in plugins.md](https://github.com/nushell/nushell.github.io/pull/780)
- kubouch created [Add `profile` note and screenshot](https://github.com/nushell/nushell.github.io/pull/778)
- bobhy created [release notes for #7952](https://github.com/nushell/nushell.github.io/pull/777)
- das-g created [[pt-BR] fix statement about `lines` output type ("tabela"→"lista")](https://github.com/nushell/nushell.github.io/pull/766), and [[es] fix statement about `lines` output type ("tabla"→"lista")](https://github.com/nushell/nushell.github.io/pull/765)

## Nu_Scripts

- fdncred created [just a base64 encoder written for fun](https://github.com/nushell/nu_scripts/pull/380)
- hyiltiz created [Fix space-in-path issue and extra / at root](https://github.com/nushell/nu_scripts/pull/379), and [Fix abbrev logic](https://github.com/nushell/nu_scripts/pull/375)
- maxim-uvarov created [add a current session history menu](https://github.com/nushell/nu_scripts/pull/378)
- Tiggax created [Updated the temp.nu for 0.60.0+](https://github.com/nushell/nu_scripts/pull/377), and [Update Check-if-env-exsists to use the envs_dirs from conda info](https://github.com/nushell/nu_scripts/pull/376)

## reedline


- rgwood created [VACUUM after deleting SQLite data](https://github.com/nushell/reedline/pull/538)
