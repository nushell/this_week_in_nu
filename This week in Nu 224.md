# This week in Nushell #224


## Nushell

- sophiajt improved exit code handling: [Respect non-zero exit code in subexpressions and blocks](https://github.com/nushell/nushell/pull/8984)
- nibon7 improved error messages ([1](https://github.com/nushell/nushell/pull/11226), [2](https://github.com/nushell/nushell/pull/11214)), and implemented several bug fixes ([1](https://github.com/nushell/nushell/pull/11210), [2](https://github.com/nushell/nushell/pull/11207), [3](https://github.com/nushell/nushell/pull/11261))
- AucaCoyan [fixed markdown formatting on LSP hover](https://github.com/nushell/nushell/pull/11253)
- schrieveslaach [upgraded the lsp-server dependency](https://github.com/nushell/nushell/pull/11252)
- fdncred [added a default for nu lib dirs](https://github.com/nushell/nushell/pull/11248)
- amtoine [fixed the `nu-std` README](https://github.com/nushell/nushell/pull/11244), [deprecated `std testing`](https://github.com/nushell/nushell/pull/11151), and [added `list<string> -> string` functionality to `last`](https://github.com/nushell/nushell/pull/11137)
- ayax79 [upgraded to polars 0.35](https://github.com/nushell/nushell/pull/11241)
- IanManske [removed unnecessary boxing of `Stack::recursion_count`](https://github.com/nushell/nushell/pull/11238), and [fixed `get -i` ignoring errors for only the first cellpath](https://github.com/nushell/nushell/pull/11213)
- KAAtheWiseGit [fixed help for wrapped commands](https://github.com/nushell/nushell/pull/11235), [added a special error for calling `metadata` on $env and $nu](https://github.com/nushell/nushell/pull/11228), and [matched `++=` capabilities with `++`](https://github.com/nushell/nushell/pull/11130)
- drbrain made error message improvements: [1](https://github.com/nushell/nushell/pull/11230), [2](https://github.com/nushell/nushell/pull/11222)
- dtolnay [fixed `Option<&str> == Option<&String>` build error when using rust_decimal/rkyv feature](https://github.com/nushell/nushell/pull/11205)
- p00f [exposed argv[0] as `$env.PROCESS_PATH`](https://github.com/nushell/nushell/pull/11203)
- ysthakur [fixed highlighting of spread subexpressions in records](https://github.com/nushell/nushell/pull/11202), and [reduced code duplication in eval.rs and eval_const.rs](https://github.com/nushell/nushell/pull/11192)
- WindSoilder [added an error on `use path item1 item2`, if item1 is not a module](https://github.com/nushell/nushell/pull/11183)
- poliorcetics [added default docs for aliases, generated from the command they point to](https://github.com/nushell/nushell/pull/10825)

## Extension

- glcraft created [Textmate improvements](https://github.com/nushell/vscode-nushell-lang/pull/168), and [Improve type parsing in function def](https://github.com/nushell/vscode-nushell-lang/pull/167)

## Documentation

- dependabot[bot] created [Bump vite from 4.4.9 to 4.4.12](https://github.com/nushell/nushell.github.io/pull/1165)
- KAAtheWiseGit created [Fix append to mutable variable operator](https://github.com/nushell/nushell.github.io/pull/1164)
- Hofer-Julian created [Fix jq comparison](https://github.com/nushell/nushell.github.io/pull/1162)
- CAESIUS-TIM created [:memo: Replace `decimal` with `float`](https://github.com/nushell/nushell.github.io/pull/1161)

## Nu_Scripts

- AucaCoyan created [Add rustup completions](https://github.com/nushell/nu_scripts/pull/690), and [:sparkles: Add `rustup` completions](https://github.com/nushell/nu_scripts/pull/689)
- Euphrasiologist created [Adding the `A` case](https://github.com/nushell/nu_scripts/pull/688), and [Create basic-git.nu](https://github.com/nushell/nu_scripts/pull/687)
- fj0r created [container-create -w: mount $env.PWD as workdir](https://github.com/nushell/nu_scripts/pull/686), and [generate completions from tree-shaped data](https://github.com/nushell/nu_scripts/pull/683), and [nu-complete kube deploys and pods](https://github.com/nushell/nu_scripts/pull/682)
- RGBCube created [Fix typo in bat aliases](https://github.com/nushell/nu_scripts/pull/684)
- amtoine created [add missing tasks to the release note PR](https://github.com/nushell/nu_scripts/pull/665)
- sholderbach created [Change uses of `size` to `str stats`](https://github.com/nushell/nu_scripts/pull/647)

## reedline

- ClementNerma created [ Make history-related items (de-)serializable](https://github.com/nushell/reedline/pull/678), and [Allow to build HistoryItemId values from the outside](https://github.com/nushell/reedline/pull/677), and [Allow to construct ReedlineError values from the outside](https://github.com/nushell/reedline/pull/676)
- crides created [vi mode: map `cw`/`cW` to `ce`/`cE` by default](https://github.com/nushell/reedline/pull/668)
