# This week in Nushell #188


## Nushell


- fdncred [fixed test_default_config_path test after pr 8653](https://github.com/nushell/nushell/pull/8690), and [fully deprecate str collect](https://github.com/nushell/nushell/pull/8680), and [add a `threads` parameter to `par_each`](https://github.com/nushell/nushell/pull/8679), and [fix `inspect` panic with large tables](https://github.com/nushell/nushell/pull/8673), and [auto-expand paths in the `$nu` variable](https://github.com/nushell/nushell/pull/8653)
- sholderbach [removed `proptest`s for nuon writing/parsing](https://github.com/nushell/nushell/pull/8688)
- jt [added rest and ignore-rest patterns](https://github.com/nushell/nushell/pull/8681), and [Remove CI coverage until we can figure out why it's broken](https://github.com/nushell/nushell/pull/8677), and [move 'str substring' to only use ranges](https://github.com/nushell/nushell/pull/8660), and [Improve inferred record types and type compat](https://github.com/nushell/nushell/pull/8649), and [Improve number-like error if expecting a string](https://github.com/nushell/nushell/pull/8645), and [Require that values that look like numbers parse as numberlike](https://github.com/nushell/nushell/pull/8635), and [Add or-patterns, fix var binding scope](https://github.com/nushell/nushell/pull/8633), and [Remove autoprinting of loop block values](https://github.com/nushell/nushell/pull/8618)
- zhiburt [fixed of a fix of #8671](https://github.com/nushell/nushell/pull/8675)
- Benjamin-L created [Support passing an empty list to sort, uniq, sort-by, and uniq-by (issue #5957)](https://github.com/nushell/nushell/pull/8669)
- amtoine create [REFACTOR: remove the redundant `path expand` from the tests of the standard library](https://github.com/nushell/nushell/pull/8666), and [stdlib: fix the `assert equal` tests](https://github.com/nushell/nushell/pull/8650), and [feature: add the standard library tests to the PR template and the toolkit](https://github.com/nushell/nushell/pull/8629), and [stdlib: optimize test search and add better errors](https://github.com/nushell/nushell/pull/8626), and [remove `match` from the standard library](https://github.com/nushell/nushell/pull/8625)
- rgwood [fixed record-to-JSON conversion for HTTP commands](https://github.com/nushell/nushell/pull/8663), and [Fix `select` on empty lists](https://github.com/nushell/nushell/pull/8651)
- stormasm created [one more try on readme](https://github.com/nushell/nushell/pull/8659), and [Add the showcase repo to Readme.md to give it more exposure to our developers](https://github.com/nushell/nushell/pull/8658)
- kks110 [allowed parsing of mu (µ) character for durations (issue #8614)](https://github.com/nushell/nushell/pull/8647)
- presidento created [stdlib: Add back recursive lookup for tests](https://github.com/nushell/nushell/pull/8632)
- 1Kinoti [fixed unhelpful error message with '@' custom completion](https://github.com/nushell/nushell/pull/8620), and [fix unhelpful error message with extra characters in list annotations](https://github.com/nushell/nushell/pull/8619)
- WindSoilder created [When running external command, expand tilde when pass back-quoted word](https://github.com/nushell/nushell/pull/8561)

## Nu_Scripts


- fdncred created [update to new nushell syntax](https://github.com/nushell/nu_scripts/pull/430), and [update script syntax to match the latest nushell](https://github.com/nushell/nu_scripts/pull/429), and [Update CODEOWNERS](https://github.com/nushell/nu_scripts/pull/428)
- spitfire05 created [Add gpsup, glo, git_current_branch](https://github.com/nushell/nu_scripts/pull/426), and [Add `gmom` alias; add missing `git_main_branch` function](https://github.com/nushell/nu_scripts/pull/425)
- WindSoilder created [fix conda script](https://github.com/nushell/nu_scripts/pull/424)
- sgasse created [custom-completions: git: Include remote branches](https://github.com/nushell/nu_scripts/pull/407)

