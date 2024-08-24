# This week in Nushell #261

## Nushell

- KAAtheWiseGit [fixed some encode/decode todo's](https://github.com/nushell/nushell/pull/13683), [removed the unused `same-file` workspace dependency](https://github.com/nushell/nushell/pull/13678), and added [`encode`/`decode` for multiple alphabets](https://github.com/nushell/nushell/pull/13428)
- sholderbach [fixed `bits ror`/`bits rol` implementation](https://github.com/nushell/nushell/pull/13673), [bumped version to 0.97.2](https://github.com/nushell/nushell/pull/13666), [fixed bugs and UB in bit shifting ops](https://github.com/nushell/nushell/pull/13663), and [changed the usage misnomer to "description"](https://github.com/nushell/nushell/pull/13598)
- devyn [bumped version to `0.97.1`](https://github.com/nushell/nushell/pull/13659), and [changed behavior of `into record` on lists to be more useful](https://github.com/nushell/nushell/pull/13637)
- ysthakur [fixed a range typechecking bug introduced by #13595](https://github.com/nushell/nushell/pull/13658)
- ayax79 [bumped version number to 0.97](https://github.com/nushell/nushell/pull/13655)
- fdncred [added more granularity for into record with dates](https://github.com/nushell/nushell/pull/13650)
- cptpiepmatz [changed expected type for derived `FromValue` implementations via attribute](https://github.com/nushell/nushell/pull/13647), and [improved working with `IntoValue` and `FromValue` for byte collections](https://github.com/nushell/nushell/pull/13641)
- IanManske [made `reduce` args and input explicit](https://github.com/nushell/nushell/pull/13646), and [fixed clippy lints](https://github.com/nushell/nushell/pull/13645)
- poliorcetics [fixed broken doc links](https://github.com/nushell/nushell/pull/13644)
- gwenya [improved help output for scripts](https://github.com/nushell/nushell/pull/13445)
- zhiburt [checked fix for emoji, wrap issues](https://github.com/nushell/nushell/pull/13430)

## Documentation

- ayax79 [updated dataframes documentation](https://github.com/nushell/nushell.github.io/pull/1522)
- evpeople [fixed a typo in doc](https://github.com/nushell/nushell.github.io/pull/1521)
- hustcer [refreshed command docs for Nu 0.97.1](https://github.com/nushell/nushell.github.io/pull/1520)
- NotTheDr01ds [generated plugin banner for all plugin commands](https://github.com/nushell/nushell.github.io/pull/1519), [made docs: Run in different Nu with plugins](https://github.com/nushell/nushell.github.io/pull/1518), [replaced `inc` in pipelines example](https://github.com/nushell/nushell.github.io/pull/1513), [updated and fixed CONTRIBUTING](https://github.com/nushell/nushell.github.io/pull/1512), and [fixed 13541 description](https://github.com/nushell/nushell.github.io/pull/1511)
- IanManske [started 0.97.0 release notes](https://github.com/nushell/nushell.github.io/pull/1510), and [added release notes for `0.97.1`](https://github.com/nushell/nushell.github.io/pull/1509)

## Nu_Scripts

- sylvainOL [made op completion work with latest nushell](https://github.com/nushell/nu_scripts/pull/936)
- A1c0 [added catppuccin macchiato theme](https://github.com/nushell/nu_scripts/pull/935)
- TechWatching [updated direnv config](https://github.com/nushell/nu_scripts/pull/934)

## reedline

- ayax79 [bumped version number to 0.34](https://github.com/nushell/reedline/pull/818)
- sholderbach [bumped crossterm to `0.28.1`](https://github.com/nushell/reedline/pull/817)

