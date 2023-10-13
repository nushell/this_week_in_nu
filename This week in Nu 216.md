# This week in Nushell #216


## Nushell

- fdncred [changed Type::Float => SyntaxShape::Number to SyntaxShape::Float](https://github.com/nushell/nushell/pull/10689), and [changed a canonicalize test to use a more deeply rooted folder](https://github.com/nushell/nushell/pull/10685), and [renamed nushell's cp command to cp-old making coreutils the default cp](https://github.com/nushell/nushell/pull/10678)
- amtoine [added Ellie to the standard library](https://github.com/nushell/nushell/pull/10686), and [added Direnv to integrations](https://github.com/nushell/nushell/pull/10675), and [added examples with `..` and `/` to `path join`](https://github.com/nushell/nushell/pull/10620), and [removed `random decimal`](https://github.com/nushell/nushell/pull/10342), and [removed `into decimal`](https://github.com/nushell/nushell/pull/10341)
- kubouch [fixed parsing of signature inp/out types in predecls](https://github.com/nushell/nushell/pull/10642), and [fixed wrong parsing of signatures in predecl scan](https://github.com/nushell/nushell/pull/10637)
- sholderbach [added a stub `dfr` command](https://github.com/nushell/nushell/pull/10683), and [updated `polars` to `0.33`](https://github.com/nushell/nushell/pull/10672), and [relaxed type-check of key-less `table`/`record`](https://github.com/nushell/nushell/pull/10629), and [fixed output types of `math` commands to be narrower](https://github.com/nushell/nushell/pull/9740)
- Hofer-Julian [deprecated `to xml --pretty {int}` in favor of `--indent {int}`](https://github.com/nushell/nushell/pull/10660), and [added long options for formats](https://github.com/nushell/nushell/pull/10645), and [added long options for filters](https://github.com/nushell/nushell/pull/10641), and [let `run_in_login_mode` succeed even with broken local config](https://github.com/nushell/nushell/pull/10622)
- lavafroth [moved the `partial_from` function to the single place it is invoked](https://github.com/nushell/nushell/pull/10705), and [preserved relative paths for local files](https://github.com/nushell/nushell/pull/10658)
- quat1024 [updated string casing to use `heck` (again)](https://github.com/nushell/nushell/pull/10680)
- WindSoilder [fixed clippy](https://github.com/nushell/nushell/pull/10659)
- CAD97 [fixed clippy in registry_query.rs](https://github.com/nushell/nushell/pull/10652), and [fixed registry query flag validation](https://github.com/nushell/nushell/pull/10648)
- bobhy [fixed dirs to update current ring slot before leaving it](https://github.com/nushell/nushell/pull/10706)
- gaetschwartz [improved an error message](https://github.com/nushell/nushell/pull/10639)
- DanyPDev [added themes to help command when available #10318](https://github.com/nushell/nushell/pull/10623)
- brunerm99 [improved the error if required field of `url join` is invalid](https://github.com/nushell/nushell/pull/10589)
- zhiburt [fixed a truncation issue in the `explore` expanded view](https://github.com/nushell/nushell/pull/10580)

## Documentation

- joergsch created [repeat variable assignment](https://github.com/nushell/nushell.github.io/pull/1108), and [fix variable name](https://github.com/nushell/nushell.github.io/pull/1107), and [prevent same entry in $env.PATH](https://github.com/nushell/nushell.github.io/pull/1104), and [Update dataframes.md](https://github.com/nushell/nushell.github.io/pull/1102), and [Update table.md](https://github.com/nushell/nushell.github.io/pull/1101)
- KAAtheWiseGit created [book/overlays: fix tip div formatting](https://github.com/nushell/nushell.github.io/pull/1106), and [Fix a minor typo in `working_with_lists`](https://github.com/nushell/nushell.github.io/pull/1105)
- cptpiepmatz created [Added "Use hooks to export state via environment variables" Section in setup.md](https://github.com/nushell/nushell.github.io/pull/1100)
- petrisch created [Fixing #460 changing .html links to .md links](https://github.com/nushell/nushell.github.io/pull/1099)

## Nu_Scripts

- cptpiepmatz created [Use Existing Path Env Var for FNM](https://github.com/nushell/nu_scripts/pull/632)
- fj0r created [mask-completions](https://github.com/nushell/nu_scripts/pull/631)
