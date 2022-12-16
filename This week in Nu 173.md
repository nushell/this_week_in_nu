# This week in Nushell #173


## Nushell


- merelymyself [ensured that `get` doesn't delve too deep in nested lists](https://github.com/nushell/nushell/pull/7497), and [let `UnknownFlag` error list out available flags](https://github.com/nushell/nushell/pull/7443), and [add interact-once switch to `rm`](https://github.com/nushell/nushell/pull/7432)
- fdncred [added a `--long` flag to `history` command for sqlite history](https://github.com/nushell/nushell/pull/7480), and [add missing shapes to default_config](https://github.com/nushell/nushell/pull/7472), and [sort enums add missing items to parse_shape_name](https://github.com/nushell/nushell/pull/7450), and [remove example missed from an earlier refactor](https://github.com/nushell/nushell/pull/7419), and [add new plugins to script](https://github.com/nushell/nushell/pull/7493)
- andrasio [fixed up register-plugins.nu](https://github.com/nushell/nushell/pull/7492), and [(nu_plugin_python): Send back the signature required fields.](https://github.com/nushell/nushell/pull/7489)
- rgwood [removed unnecessary `echo` uses from examples](https://github.com/nushell/nushell/pull/7500), and [Add helper method to check whether ctrl+c was pressed, adopt it](https://github.com/nushell/nushell/pull/7482), and [Handle ctrl-c in `uniq` and `uniq-by`](https://github.com/nushell/nushell/pull/7478), and [Fix streaming page missing newline](https://github.com/nushell/nushell/pull/7466), and [Make hook execution stream instead of collecting](https://github.com/nushell/nushell/pull/7440)
- sholderbach created [Use `nu-path` correctly in `nu!` test macro to make dev-dependency transitive](https://github.com/nushell/nushell/pull/7488), and [Add example showing first class closure to `do`](https://github.com/nushell/nushell/pull/7473)
- zhiburt [fixed #7486](https://github.com/nushell/nushell/pull/7487), and [Try to fix #7380](https://github.com/nushell/nushell/pull/7446), and [nu-explore/ A few things](https://github.com/nushell/nushell/pull/7339)
- WindSoilder [refactored Nu to introduce is_external_failed to PipelineData, and simplify try logic](https://github.com/nushell/nushell/pull/7476), and [break `for`, `loop`, `while` execution when external command runs to failed](https://github.com/nushell/nushell/pull/7475), and [remove output, append, bin flag from fetch command](https://github.com/nushell/nushell/pull/7468), and [in for, loop, while, auto print final value in each iteration](https://github.com/nushell/nushell/pull/7433), and [make split row works like python and rust ways](https://github.com/nushell/nushell/pull/7413)
- webbedspace [improved help messages: edit various instances of "block" to "closure"](https://github.com/nushell/nushell/pull/7470), and [Fix `du` error message](https://github.com/nushell/nushell/pull/7460), and [Tweak "Cannot convert {x} to a string argument" error in run_external](https://github.com/nushell/nushell/pull/7434), and [`$env.config` now always holds a record with only valid values](https://github.com/nushell/nushell/pull/7309)
- hustcer [added a riscv64 binary release target](https://github.com/nushell/nushell/pull/7469), and [add input_output_types() to benchmark,cd and config reset](https://github.com/nushell/nushell/pull/7455)
- raccmonteiro [changed `mkdir`'s change flag `-s` to `-v`](https://github.com/nushell/nushell/pull/7462)
- jntrnr [reverted "Add pipeline operators to help"](https://github.com/nushell/nushell/pull/7454), and [Revert "Pipeline operators: `&&` and `||`"](https://github.com/nushell/nushell/pull/7452), and [Add pipeline operators to help](https://github.com/nushell/nushell/pull/7449), and [Pipeline operators: `&&` and `||`](https://github.com/nushell/nushell/pull/7448)
- Kangaxx-0 [added config mutation tests](https://github.com/nushell/nushell/pull/7437), and [into cellpath command](https://github.com/nushell/nushell/pull/7417)
- kubouch [replaced row conditions with closures in commands](https://github.com/nushell/nushell/pull/7428), and [Simplify FILE_PWD setting in 'overlay use'](https://github.com/nushell/nushell/pull/7425), and [Add FILE_PWD environment variable when running 'nu script.nu'](https://github.com/nushell/nushell/pull/7424), and [Make env-related tests more resilient](https://github.com/nushell/nushell/pull/7423), and [Move 'where' to parser keywords; Add 'filter' command](https://github.com/nushell/nushell/pull/7365)
- metacoma [fixed the Docker build](https://github.com/nushell/nushell/pull/7422)
- gavinfoley [fixed escaping backslashes in interpolated strings (fixes #6737)](https://github.com/nushell/nushell/pull/7119)

## Extension

- fdncred [added `and` and `or` so they highlight properly](https://github.com/nushell/vscode-nushell-lang/pull/72)

## Documentation


- Tengs-Penkwe [corrected a bare word example](https://github.com/nushell/nushell.github.io/pull/703), and [Correct command examples](https://github.com/nushell/nushell.github.io/pull/702)
- raccmonteiro updated [`mkdir` `--show-created-paths` flag replaced](https://github.com/nushell/nushell.github.io/pull/701)
- sin [fixed an error in `book/dataframes.md`](https://github.com/nushell/nushell.github.io/pull/700)
- hustcer [optimized the make_docs script for better performance](https://github.com/nushell/nushell.github.io/pull/697), and [chore: Upgrade some outdated dependencies](https://github.com/nushell/nushell.github.io/pull/694)
- WindSoilder [documented a breaking change for split row](https://github.com/nushell/nushell.github.io/pull/696)
- thara [fixed dead links](https://github.com/nushell/nushell.github.io/pull/695)


## Nu_Scripts


- jntrnr [fixed the TWiN script](https://github.com/nushell/nu_scripts/pull/328)
- xlittlerag [fixed get-weather celsius loop](https://github.com/nushell/nu_scripts/pull/326)
- 1Kinoti [fixed `up` command for v0.72.0](https://github.com/nushell/nu_scripts/pull/325)
- WindSoilder [fixed custom completions arg names](https://github.com/nushell/nu_scripts/pull/324)
- fdncred [changed `for` to `each` in oh-my.nu](https://github.com/nushell/nu_scripts/pull/323)
