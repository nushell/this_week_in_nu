# This week in Nushell #194


## Nushell

- jntrnr [removed a few unnecessary allocations](https://github.com/nushell/nushell/pull/9176)
- fdncred [added dataframe support to toolkit](https://github.com/nushell/nushell/pull/9173), [updated default_env.nu to work with windows](https://github.com/nushell/nushell/pull/9172), and [add a negation glob option to the glob command](https://github.com/nushell/nushell/pull/9153), and [resolve standard library before ide commands](https://github.com/nushell/nushell/pull/9126), and [update nu-glob based on latest glob 0.3.1 changes](https://github.com/nushell/nushell/pull/9099)
- juanPabloMiceli [fixed the find -v command on tables (issue #9043)](https://github.com/nushell/nushell/pull/9159)
- michaeljohnalbers [ensured consistent map ordering when reading YAML](https://github.com/nushell/nushell/pull/9155)
- bobhy [added parameter defaults to $nu.scope.commands](https://github.com/nushell/nushell/pull/9152)
- Hofer-Julian [upgraded to polars 0.29](https://github.com/nushell/nushell/pull/9145), and [upgraded polars to 0.28](https://github.com/nushell/nushell/pull/9136)
- tesla232 added [span fixes during duration conversion](https://github.com/nushell/nushell/pull/9143)
- zhiburt made fixes to `explore`: [nu-explore: Fix repeated char issue in cmdline](https://github.com/nushell/nushell/pull/9139), and [nu-explore: Fix pipeline rendering](https://github.com/nushell/nushell/pull/9137)
- amtoine [swapped the date and the log level in the `std log` format](https://github.com/nushell/nushell/pull/9138), and [FEATURE: add a `main` command to `toolkit.nu`](https://github.com/nushell/nushell/pull/9135), and [REFACTOR: make `input list` a tiny bit tighter](https://github.com/nushell/nushell/pull/9115), and [FIX: have consistent errors between `std help` and `std help ...`](https://github.com/nushell/nushell/pull/9101), and [REFACTOR: fix typos and simplify external `std help`](https://github.com/nushell/nushell/pull/9100), and [FIX: add a space after the default left prompt](https://github.com/nushell/nushell/pull/9074), and [REFACTOR: move the banner from the `rust` source to the standard library](https://github.com/nushell/nushell/pull/8406)
- 1Kinoti [added more commands to `std iter`](https://github.com/nushell/nushell/pull/9129), and [improve error when name and parameters are not space-separated](https://github.com/nushell/nushell/pull/8958)
- kubouch made lots of module fixes: [Reuse parsed modules](https://github.com/nushell/nushell/pull/9125), and [Fix exported module not found](https://github.com/nushell/nushell/pull/9121), and [Allow creating modules from directories](https://github.com/nushell/nushell/pull/9066)
- melMass [enabled setup-git-hooks on windows](https://github.com/nushell/nushell/pull/9097)
- EmilySeville7cfg created [FEATURE: format `std log` and add `--short` option](https://github.com/nushell/nushell/pull/9091)
- stevenxxiu added a fix: [use `buffer.len()` instead of `cursor_pos`, so the `.expect()` isn't useless](https://github.com/nushell/nushell/pull/9053)

## Extension

- EmilySeville7cfg [added snippet completions](https://github.com/nushell/vscode-nushell-lang/pull/126)

## Documentation

- VuiMuich fixed a [small typo in `dataframes.md`](https://github.com/nushell/nushell.github.io/pull/905)
- amtoine [addded a bunch of interesting PR links](https://github.com/nushell/nushell.github.io/pull/903)

## Nu_Scripts

- fj0r created [clean up kubernetes.nu](https://github.com/nushell/nu_scripts/pull/486), and [improve kconf import](https://github.com/nushell/nu_scripts/pull/481), and [rename registry list to registry show](https://github.com/nushell/nu_scripts/pull/480)
- zsehanovic [fixed git aliases](https://github.com/nushell/nu_scripts/pull/485)
- EmilySeville7cfg created [Feature: clean-up completion directory](https://github.com/nushell/nu_scripts/pull/484), and [feat(nano): add completions](https://github.com/nushell/nu_scripts/pull/479)
- dschrempf [made some fixes to ultimate_extractor](https://github.com/nushell/nu_scripts/pull/482)
- maxim-uvarov [added the function to display bars of given percentage from given width](https://github.com/nushell/nu_scripts/pull/478)
