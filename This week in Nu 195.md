# This week in Nushell #195


## Nushell

- Dorumin added [Feature: Userland LazyRecords](https://github.com/nushell/nushell/pull/8332)
- stormasm [moved dataframe commands to nu-cmd-dataframe](https://github.com/nushell/nushell/pull/9241), and [documented how to run dataframe tests as well](https://github.com/nushell/nushell/pull/9188)
- skelly37 [added `assert not` command (assertion that the value/expression is `false`)](https://github.com/nushell/nushell/pull/9235)
- fdncred  [removed unused dependencies](https://github.com/nushell/nushell/pull/9230), [added cargo.lock file](https://github.com/nushell/nushell/pull/9223), and [bump nushell from release version to development version](https://github.com/nushell/nushell/pull/9215)
- maxim-uvarov [added the `no-strip` flag to the clip command](https://github.com/nushell/nushell/pull/9216)
- sholderbach [bumped version for 0.80.0 release](https://github.com/nushell/nushell/pull/9212), and [Pin reedline to `0.19.1` for 0.80 release](https://github.com/nushell/nushell/pull/9211)
- melMass [fixed: 🐛 handle windows Path casing](https://github.com/nushell/nushell/pull/9210)
- WindSoilder  [fixed clippy warning on clippy 0.1.69](https://github.com/nushell/nushell/pull/9204), and [Avoid blocking when `o+e>` redirects too much stderr message](https://github.com/nushell/nushell/pull/8784)
- nicolb2305 [removed unnecessary cwd and pipeline from various tests  ](https://github.com/nushell/nushell/pull/9202)
- bobhy [fixed spurious 'item not found' error in `std help`](https://github.com/nushell/nushell/pull/9197)
- 1Kinoti [improved parsing of values with units](https://github.com/nushell/nushell/pull/9190)
- Mehrbod2002 created [Fmt f64](https://github.com/nushell/nushell/pull/9142)
- rgwood [changed group-by to accept cell paths](https://github.com/nushell/nushell/pull/9020)
- amtoine created [REFACTOR: remove the shell commands](https://github.com/nushell/nushell/pull/8415)


## Extension

- EmilySeville7cfg created [feat(snippets): use H3 headers](https://github.com/nushell/vscode-nushell-lang/pull/128), and [feat(snippets): markdown doc sections](https://github.com/nushell/vscode-nushell-lang/pull/127)

## Documentation

- amtoine created [refactor minor things in the modules chapter](https://github.com/nushell/nushell.github.io/pull/915)
- mrkkrp created [Minor improvements to the installation chapter](https://github.com/nushell/nushell.github.io/pull/914)
- kubouch created [Try to fix tooltip in Modules (2nd attempt)](https://github.com/nushell/nushell.github.io/pull/913), and [Try to fix tipbox in Modules](https://github.com/nushell/nushell.github.io/pull/912), and [Update modules chapter](https://github.com/nushell/nushell.github.io/pull/908)
- hustcer created [Fix heading for ebook building](https://github.com/nushell/nushell.github.io/pull/911), and [Refresh docs for nu v0.80](https://github.com/nushell/nushell.github.io/pull/909)
- daniel-vainsencher created [Tiny typo fixes in 2023-05-16-nushell_0_80.md](https://github.com/nushell/nushell.github.io/pull/910)
- sholderbach created [Release notes for `0.80`](https://github.com/nushell/nushell.github.io/pull/890)

## Nu_Scripts

- fj0r created [refactor: introduce `spr` and `sprb` for spread](https://github.com/nushell/nu_scripts/pull/504), and [merge ktpa into ktp(-a), rename ktn to ktno](https://github.com/nushell/nu_scripts/pull/497), and [refactor `git-v2#agree` with `input list`](https://github.com/nushell/nu_scripts/pull/496), and [Experimental multi-taskrunner support for `jx` (npm for example)](https://github.com/nushell/nu_scripts/pull/492), and [gp: run `git fetch` before `git push` or `git pull`](https://github.com/nushell/nu_scripts/pull/490), and [kubernetes completion of jsonpath](https://github.com/nushell/nu_scripts/pull/487)
- amtoine created [add a package file in NUON](https://github.com/nushell/nu_scripts/pull/503), and [FEATURE: add the preview script for the themes](https://github.com/nushell/nu_scripts/pull/501), and [FEATURE: add `term-dark` and `term-light` themes from main `nushell`](https://github.com/nushell/nu_scripts/pull/500), and [FEATURE: allow to run themes/make script from anywhere](https://github.com/nushell/nu_scripts/pull/499), and [REFACTOR: make the indentation in the themes more consistent](https://github.com/nushell/nu_scripts/pull/498)
- Tiggax created [Fixed the completion of `--flamegraph`](https://github.com/nushell/nu_scripts/pull/502), and [Added typst completion script.](https://github.com/nushell/nu_scripts/pull/494)
- EmilySeville7cfg created [Fix: remaining aliases](https://github.com/nushell/nu_scripts/pull/495), and [feat(aliases): reformat and use long options](https://github.com/nushell/nu_scripts/pull/489), and [feat(module): add random-list](https://github.com/nushell/nu_scripts/pull/488)
- nullishamy created [fix: just completions](https://github.com/nushell/nu_scripts/pull/491)
