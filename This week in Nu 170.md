# This week in Nushell #170


## Nushell


- kubouch [reordered export-env eval and allowed reloading an overlay](https://github.com/nushell/nushell/pull/7231)
- jntrnr created [New commands: `break`, `continue`, `return`, and `loop`](https://github.com/nushell/nushell/pull/7230), and [Remove And and Or pipeline elements](https://github.com/nushell/nushell/pull/7229), and [Add try/catch functionality](https://github.com/nushell/nushell/pull/7221), and [A set of fixes for stderr redirect](https://github.com/nushell/nushell/pull/7219), and [Don't redirect stdout when only redirecting stderr](https://github.com/nushell/nushell/pull/7206), and [Stdout/Stderr redirection](https://github.com/nushell/nushell/pull/7185), and [Move dataframe out of extra](https://github.com/nushell/nushell/pull/7180), and [Add auto-expanding table view to default config](https://github.com/nushell/nushell/pull/7172)
- rgwood [made catch block a closure w/ access to error](https://github.com/nushell/nushell/pull/7228), and [Feature cleanup](https://github.com/nushell/nushell/pull/7182)
- fdncred [pinned to a version of zstd that doesn't break dataframe compilation](https://github.com/nushell/nushell/pull/7227)
- dmatos2012 [fixed color_config crashing on nonstring data](https://github.com/nushell/nushell/pull/7215)
- sholderbach [removed the `samples/wasm` folder](https://github.com/nushell/nushell/pull/7214), and [Error on negative argument of `first`](https://github.com/nushell/nushell/pull/7186), and [Error on negative argument to `last`](https://github.com/nushell/nushell/pull/7184)
- webbedspace [fixed `fetch`/`post` not erroring on 4xx and 5xx statuses](https://github.com/nushell/nushell/pull/7213), and [Fix `sort-by`, `path join` and `size` error arrows](https://github.com/nushell/nushell/pull/7199), and [Change all `--insensitive` flags to `--ignore-case`](https://github.com/nushell/nushell/pull/7198), and [Fix `mv` error message issues (arrows, Windows paths)](https://github.com/nushell/nushell/pull/7197), and [Fix `glob` error arrows](https://github.com/nushell/nushell/pull/7194), and [Remove erroneous test introduced in #6994](https://github.com/nushell/nushell/pull/7179), and [Rename dataframe `describe` to `summary` so that the normal `describe` isn't overloaded](https://github.com/nushell/nushell/pull/7176), and [Bugfix: add table_index_mode check that was missing from #6983](https://github.com/nushell/nushell/pull/7170), and [Edit `rm` help messages](https://github.com/nushell/nushell/pull/7165), and [Improve CantFindColumn and ColumnAlreadyExists errors](https://github.com/nushell/nushell/pull/7164), and [Fix needs_quotes() in `to nuon` (closes #6989)](https://github.com/nushell/nushell/pull/7056), and [Allow iteration blocks to have an optional extra index parameter (alternative to `-n` flags)](https://github.com/nushell/nushell/pull/6994), and [Grouped config commands better (closes #6911)](https://github.com/nushell/nushell/pull/6983)
- michel-slm [added binstall metadata](https://github.com/nushell/nushell/pull/7212)
- raccmonteiro fixed [`uniq -i` does not convert to lowercase (#7192)](https://github.com/nushell/nushell/pull/7209), and [`uniq` code refactoring](https://github.com/nushell/nushell/pull/7188), and [new command `url parse` (#6854) and `url` subcommands tests](https://github.com/nushell/nushell/pull/7124)
- kamirr [fixed while ctrlc behavior](https://github.com/nushell/nushell/pull/7195), and [Fix `last` memory use](https://github.com/nushell/nushell/pull/7178)
- nibon7 [applied a clippy fix](https://github.com/nushell/nushell/pull/7193)
- WindSoilder [removde block input support from merge](https://github.com/nushell/nushell/pull/7177), and [Plugin: make friendly error message when python is not found](https://github.com/nushell/nushell/pull/7163), and [Make external command substitution works friendly(like fish shell, trailing ending newlines)](https://github.com/nushell/nushell/pull/7156), and [add signature information when get help on one command](https://github.com/nushell/nushell/pull/7079)
- nanoqsh [fixed JSON parsing](https://github.com/nushell/nushell/pull/7175)
- SUPERCILEX [restored original do -i behavior and add flags to break down shell vs program errors](https://github.com/nushell/nushell/pull/7122)
- Decodetalkers created [feat: Use Raw text to save if pipeline data is ExternalStream or String](https://github.com/nushell/nushell/pull/7082)
- Kixunil [made JSON require string and pass around metadata](https://github.com/nushell/nushell/pull/7010)

## Documentation

- WindSoilder [removed the `Subexpressions with external commands` section](https://github.com/nushell/nushell.github.io/pull/681)
- dmatos2012 [expanded the docs on using use with export-env](https://github.com/nushell/nushell.github.io/pull/680)
- webbedspace added [Release Notes: add note about `--ignore-case`](https://github.com/nushell/nushell.github.io/pull/678)
- raccmonteiro [documented the `url parse` command](https://github.com/nushell/nushell.github.io/pull/677)
- casidiablo [fixed a typo in advanced.md page](https://github.com/nushell/nushell.github.io/pull/676)
- remlse [fixed the variable path expression example](https://github.com/nushell/nushell.github.io/pull/674)

## Nu_Scripts


- Joxtacy [added zellij completions](https://github.com/nushell/nu_scripts/pull/317)
- Emilgardis [improved Cargo completions](https://github.com/nushell/nu_scripts/pull/316)


## reedline

- rgwood created [Fix example in CONTRIBUTING.md](https://github.com/nushell/reedline/pull/517)
