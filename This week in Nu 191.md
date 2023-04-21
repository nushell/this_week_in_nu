# This week in Nushell #191


## Nushell

- fdncred [used record separator `\x1e` for `include_path`](https://github.com/nushell/nushell/pull/8961), and [allow `find` command to look in specified columns only](https://github.com/nushell/nushell/pull/8937), and [fix reedline breaking changes due to PR562](https://github.com/nushell/nushell/pull/8921), and [fix bug with include_path -I parameter](https://github.com/nushell/nushell/pull/8915), and [allow custom commands to show up in `$nu.scope.commands` better](https://github.com/nushell/nushell/pull/8910), and [remove debug print bug](https://github.com/nushell/nushell/pull/8909), and [Update issue templates](https://github.com/nushell/nushell/pull/8901)
- pingiun [set override locale in toolkit](https://github.com/nushell/nushell/pull/8957), and [Set env in exec command](https://github.com/nushell/nushell/pull/8917)
- jt [reused the cached parse results of parsed files](https://github.com/nushell/nushell/pull/8949), and [Hopefully speedup startup](https://github.com/nushell/nushell/pull/8913), and [Allocate less when doing a capture discovery](https://github.com/nushell/nushell/pull/8903)
- 1Kinoti [unified the `*-BuiltinVar` parser errors](https://github.com/nushell/nushell/pull/8944), and [add `filter-map` command to `std iter`](https://github.com/nushell/nushell/pull/8926), and [add `iter` module to standard library](https://github.com/nushell/nushell/pull/8899), and [rename toolkit's `set-git-hooks` to `setup-git-hooks`](https://github.com/nushell/nushell/pull/8897)
- presidento [fixed `into decimal` command category](https://github.com/nushell/nushell/pull/8932)
- amtoine [refactored the `CONTRIBUTING.md` guidelines for `nu-std`](https://github.com/nushell/nushell/pull/8912), and [stdlib: fix the `clip` command with integer values](https://github.com/nushell/nushell/pull/8898)
- vaishaag [fixed strange error on unbalanced curly braces](https://github.com/nushell/nushell/pull/8906)
- rgwood [upgraded `open` crate to fix WSL bug](https://github.com/nushell/nushell/pull/8905)
- bobhy created [`std run-tests`: Rename --command switch to --test; and likewise in --list output](https://github.com/nushell/nushell/pull/8895), and [Replace #8824: CONTRIBUTING.md for standard library](https://github.com/nushell/nushell/pull/8894)

## Extension

- fdncred created [change the `:` separator to a record separator `\x1e`](https://github.com/nushell/vscode-nushell-lang/pull/113), and [add folding regions](https://github.com/nushell/vscode-nushell-lang/pull/111), and [rename to match readme](https://github.com/nushell/vscode-nushell-lang/pull/110), and [update readme](https://github.com/nushell/vscode-nushell-lang/pull/109), and [update example generation script and examples](https://github.com/nushell/vscode-nushell-lang/pull/107), and [add a throttle timeout so that we don't update to frequently](https://github.com/nushell/vscode-nushell-lang/pull/106), and [add timing to more server functions](https://github.com/nushell/vscode-nushell-lang/pull/105)
- glcraft created [Add underscore separator in numbers](https://github.com/nushell/vscode-nushell-lang/pull/108)

## Documentation

- presidento created [Dataframes](https://github.com/nushell/nushell.github.io/pull/876), and [Update testing chapter](https://github.com/nushell/nushell.github.io/pull/868)
- maxim-uvarov created [fixing typo in 2023-04-04-nushell_0_78.md](https://github.com/nushell/nushell.github.io/pull/875)
- D3V1LC0D3R created [Update working_with_tables.md to include reject](https://github.com/nushell/nushell.github.io/pull/874)
- Kissaki created [Improve misleading text format on note](https://github.com/nushell/nushell.github.io/pull/873)
- uselesspseudo created [Fix old keybding for help menu](https://github.com/nushell/nushell.github.io/pull/871)

## Nu_Scripts

- fdncred created [update sg.nu to print again](https://github.com/nushell/nu_scripts/pull/456), and [some fun iterm2 drawing](https://github.com/nushell/nu_scripts/pull/449), and [update range syntax in str substring usage](https://github.com/nushell/nu_scripts/pull/448)
- nils-degroot created [Added completions for pass](https://github.com/nushell/nu_scripts/pull/454)
- D3V1LC0D3R created [Update nuschiit.nu (used deprecated fetch)](https://github.com/nushell/nu_scripts/pull/453), and [a small query web showcase with unscramble.me](https://github.com/nushell/nu_scripts/pull/452)
- TuffenDuffen created [Fix issue with open in yarn completions](https://github.com/nushell/nu_scripts/pull/451)

## reedline

- xiuxiu62 created [re-export crossterm::style::Color for custom prompt implementations](https://github.com/nushell/reedline/pull/569)
- fdncred created [Allow history searching via session id](https://github.com/nushell/reedline/pull/562)
