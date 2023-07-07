# This week in Nushell #202


## Nushell

- jntrnr [changed how `let` works with pipelines](https://github.com/nushell/nushell/pull/9589), [moved to using a safer shell integration default setting](https://github.com/nushell/nushell/pull/9600), and [disallowed blocks as first-class values](https://github.com/nushell/nushell/pull/9587), and [use an easier-to-read date format in prompt](https://github.com/nushell/nushell/pull/9585), and [fix a few clippy issues](https://github.com/nushell/nushell/pull/9578)
- 1Kinoti [improved subtyping](https://github.com/nushell/nushell/pull/9614), and [allowed tables to have annotations](https://github.com/nushell/nushell/pull/9613)
- Yethal made lots of test-runner improvements: [test-runner: Performance improvements + regex match for test include/exclude](https://github.com/nushell/nushell/pull/9622), and [test-runner: Add option to exclude single test and module](https://github.com/nushell/nushell/pull/9611), and [Implement annotations support in test runner](https://github.com/nushell/nushell/pull/9406)
- WindSoilder updated `watch` to [use notify-debouncer-full(based on notify v6) instead of notify v4](https://github.com/nushell/nushell/pull/9606), and [Bracketed paste refactor](https://github.com/nushell/nushell/pull/9547)
- NotLebedev created [a command to get individual keys](https://github.com/nushell/nushell/pull/9453)
- sholderbach [updated `proc-macro2` lock to fix the nightly build](https://github.com/nushell/nushell/pull/9618), and [excluded deprecated commands from completions](https://github.com/nushell/nushell/pull/9612), and [documented `fn pipeline()` used with `nu!` tests](https://github.com/nushell/nushell/pull/9609), and [removed unnecessary parentheses](https://github.com/nushell/nushell/pull/9605)
- hanjunghyuk [fixed `explore` crashes on `{}`](https://github.com/nushell/nushell/pull/9623)
- YassineHaouzane [fixed update engine_state when history.isolation is true (#9268)](https://github.com/nushell/nushell/pull/9616)
- nibon7 [replaced `users` with `nix` crate](https://github.com/nushell/nushell/pull/9610)
- amtoine [simplified the `nu!` tests for `last` and `first` commands](https://github.com/nushell/nushell/pull/9608), and [REFACTOR: move the 0% commands to `nu-cmd-extra`](https://github.com/nushell/nushell/pull/9404)
- Hofer-Julian [added a `pwd` command to stdlib](https://github.com/nushell/nushell/pull/9607)
- IanManske [fixed the `headers` command handling of missing values](https://github.com/nushell/nushell/pull/9603)
- rusty-jules created [Fix: return all headers with the same name from `http <method>`](https://github.com/nushell/nushell/pull/9594)
- baehyunsol [made the behaviours of `last` and `first` more consistent](https://github.com/nushell/nushell/pull/9582)
- fdncred [fixed the right prompt in the default_env.nu](https://github.com/nushell/nushell/pull/9581), and [fix typo in deprecated message: `$nu` should be `$env`](https://github.com/nushell/nushell/pull/9579)
- bgmort [added a useful example to `http options` documentation](https://github.com/nushell/nushell/pull/9576)


## Documentation

- Equationzhao created [fix a broken link in plugins page in zh-CN](https://github.com/nushell/nushell.github.io/pull/975)
- Hofer-Julian created [Remove `&&` and `||`](https://github.com/nushell/nushell.github.io/pull/974)
- amtoine created [add a more complete example to persist aliases in `config.nu`](https://github.com/nushell/nushell.github.io/pull/973)
- jarrodu created [Fix typo](https://github.com/nushell/nushell.github.io/pull/971)
- sholderbach created [Automate response to PRs trying to update commands](https://github.com/nushell/nushell.github.io/pull/969)

## Nu_Scripts

- trantor created [Update README.md: typo](https://github.com/nushell/nu_scripts/pull/545)
- dedebenui created [fix pass-completion as `let` cannot be used at module level](https://github.com/nushell/nu_scripts/pull/544)
- amtoine created [use `$env.` instead of `let-env `](https://github.com/nushell/nu_scripts/pull/543), and [update the `make_release/Readme.md` with the whole process](https://github.com/nushell/nu_scripts/pull/541), and [fix the release note scripts](https://github.com/nushell/nu_scripts/pull/538)
