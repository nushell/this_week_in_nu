# This week in Nushell #215


## Nushell

- Hofer-Julian added long options to several commands: [1](https://github.com/nushell/nushell/pull/10621), [2](https://github.com/nushell/nushell/pull/10619), [3](https://github.com/nushell/nushell/pull/10602), [4](https://github.com/nushell/nushell/pull/10601), [5](https://github.com/nushell/nushell/pull/10596)
- lpchaim [added a `url decode` command](https://github.com/nushell/nushell/pull/10611)
- dmatos2012 fixed an issue in `ucp`: ["Change error when directory is specified but not recursive"](https://github.com/nushell/nushell/pull/10609)
- fdncred [removed underline from std NU_LOG_FORMAT](https://github.com/nushell/nushell/pull/10604), and [added a few more grid icons](https://github.com/nushell/nushell/pull/10583)
- gaetschwartz updated `std log` to [allow specifying a custom date format](https://github.com/nushell/nushell/pull/10603)
- lavafroth fixed a bug with [path completions surrounded by quotes or backticks](https://github.com/nushell/nushell/pull/10600), and added [Fish-like completions for nested directories](https://github.com/nushell/nushell/pull/10543)
- jntrnr made improvements to `cd`: [removed cd w/ abbreviations](https://github.com/nushell/nushell/pull/10588), and [allowed auto-cd on trailing slash](https://github.com/nushell/nushell/pull/10585)
- hudclark added a [new `unfold` command](https://github.com/nushell/nushell/pull/10489)
- sholderbach made some parsing+type improvements: [Parse custom completer annotation only in args](https://github.com/nushell/nushell/pull/10581), and [Use `int` type name consistently](https://github.com/nushell/nushell/pull/10579), and [Move `SyntaxShape` specifier parsing into own file](https://github.com/nushell/nushell/pull/10448)
- joergsch fixed [line folding in `from ics`/`from vcf`](https://github.com/nushell/nushell/pull/10577)
- ClipplerBlood [added a `--env` flag to the `do` command](https://github.com/nushell/nushell/pull/10572)
- rgwood did some work to simplify `explore`: [1](https://github.com/nushell/nushell/pull/10570), [2](https://github.com/nushell/nushell/pull/10562), [3](https://github.com/nushell/nushell/pull/10559)
- amtoine [made "can't follow stream paths" error a bit better](https://github.com/nushell/nushell/pull/10569), and [improved assertion error messages in `std assert`](https://github.com/nushell/nushell/pull/10551), and [added `to ndjson` and `to jsonl` to the standard library](https://github.com/nushell/nushell/pull/10519)
- kubouch [added `--env` and `--wrapped` flags to `def`](https://github.com/nushell/nushell/pull/10566)
- brunerm99 [added a warning to `url join` when input key is not supported (#10506)](https://github.com/nushell/nushell/pull/10565)
- hustcer [update build flags for riscv64gc and armv7 targets](https://github.com/nushell/nushell/pull/10564)
- Yethal [reduced test file parsing overhead in the stdlib](https://github.com/nushell/nushell/pull/10545)
- WindSoilder [changed the SyntaxShape of `-c` flag from list to record](https://github.com/nushell/nushell/pull/10526)
- vedaRadev [added a 'help escapes' command for quick reference of nushell string escapes](https://github.com/nushell/nushell/pull/10522)
- stormasm tweaked [eval.rs to remove pub from fn eval_element_with_input](https://github.com/nushell/nushell/pull/10587)


## Documentation

- dedebenui created [fixed alias normalization](https://github.com/nushell/nushell.github.io/pull/1097)
- Hofer-Julian created [Improve command docs](https://github.com/nushell/nushell.github.io/pull/1096), and [make_docs: Parallelize command generation](https://github.com/nushell/nushell.github.io/pull/1095)
- hustcer created [Update CONTRIBUTING.md and lefthook module](https://github.com/nushell/nushell.github.io/pull/1092), and [Update syntax highlighting for Nu](https://github.com/nushell/nushell.github.io/pull/1090), and [Update syntax highlighting for some blog docs](https://github.com/nushell/nushell.github.io/pull/1089), and [Update syntax highlighting for commands docs from shell to nu](https://github.com/nushell/nushell.github.io/pull/1088), and [Add real Nushell syntax highlighting support](https://github.com/nushell/nushell.github.io/pull/1078)
- savente93 created [finish sentence in pattern matching.md](https://github.com/nushell/nushell.github.io/pull/1087), and [Expand `append` examples and add `match` example](https://github.com/nushell/nushell.github.io/pull/1083)
- amtoine created [add the "style guide" page to the sidebar](https://github.com/nushell/nushell.github.io/pull/1086)
- EmilyGraceSeville7cf created [Write best practices and style guide](https://github.com/nushell/nushell.github.io/pull/904)

## Nu_Scripts

- amtoine created [update the `direnv` hook](https://github.com/nushell/nu_scripts/pull/628), and [Add cartesian product to math module](https://github.com/nushell/nu_scripts/pull/624)
- savente93 created [add tests to str.nu](https://github.com/nushell/nu_scripts/pull/627), and [Add `str append`  to stdlib-candidate](https://github.com/nushell/nu_scripts/pull/626), and [Add gnu wc wrapper](https://github.com/nushell/nu_scripts/pull/625)
