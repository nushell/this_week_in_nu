# This week in Nushell #206


## Nushell

- jntrnr [re-aligned how prompt indicators work](https://github.com/nushell/nushell/pull/9907), and [simplified default style and match Rust code to config](https://github.com/nushell/nushell/pull/9900), and [reverted 9693 to prevent CPU hangs](https://github.com/nushell/nushell/pull/9893), and [reverted "Add an option to move header on borders"](https://github.com/nushell/nushell/pull/9908)
- IanManske [replaced `&Span` with `Span` since `Span` is `Copy`](https://github.com/nushell/nushell/pull/9770)
- fdncred [removed `vectorize_over_list` from python plugin](https://github.com/nushell/nushell/pull/9905), and [updated the `format` signature to allow `record` to be passed in](https://github.com/nushell/nushell/pull/9898), and [updated the `items` signature to allow `any` output](https://github.com/nushell/nushell/pull/9896), and [updated the `char` signature with `Table`](https://github.com/nushell/nushell/pull/9895), and [updated to current reedline](https://github.com/nushell/nushell/pull/9877), and [bumped to dev version 0.83.2](https://github.com/nushell/nushell/pull/9866)
- WindSoilder [renamed `date format` to `format date`](https://github.com/nushell/nushell/pull/9902), and [Module: support defining const and use const variables inside of function](https://github.com/nushell/nushell/pull/9773)
- ayax79 cleaned up some dataframe commands: [merged overloaded commands](https://github.com/nushell/nushell/pull/9860), and [merging into one `dfr into-nu` command](https://github.com/nushell/nushell/pull/9858)
- atahabaki created [str-expand: add path flag](https://github.com/nushell/nushell/pull/9856), and [str-expand: Add Escaping Example](https://github.com/nushell/nushell/pull/9841)
- ghost [made URLs clickable in error documentation](https://github.com/nushell/nushell/pull/9854)
- mengsuenyan [fixed a bug where `~ | path type` returned an empty string](https://github.com/nushell/nushell/pull/9853), and [fixed a panic when type a statement similar to `let f = 'f' $` in the nushell](https://github.com/nushell/nushell/pull/9851)
- sholderbach [updated `unicode-linebreak` to `0.1.5`](https://github.com/nushell/nushell/pull/9814), and [added `format duration` to replace `into duration --convert`](https://github.com/nushell/nushell/pull/9788)
- zhiburt [added an option to move header on borders](https://github.com/nushell/nushell/pull/9796)
- jflics6460 created [Accept records for http subcommand headers (-H)](https://github.com/nushell/nushell/pull/9771)

## Documentation

- LeoniePhiline created [fix(docs): Fix link to "setting environment variables"](https://github.com/nushell/nushell.github.io/pull/996), and [fix(docs): Link to Command Reference led to HTTP 404](https://github.com/nushell/nushell.github.io/pull/993)
- hustcer created [Upgrade some dependencies, and fix some broken assets import](https://github.com/nushell/nushell.github.io/pull/995)
- amtoine created [patch: release notes for 0.83.1](https://github.com/nushell/nushell.github.io/pull/994)
- gregokent created [tweak `overlay new` tip](https://github.com/nushell/nushell.github.io/pull/992)

## Nu_Scripts

- amtoine created [rename `date format` to `format date`](https://github.com/nushell/nu_scripts/pull/571), and [fix the date schedule in the release scripts](https://github.com/nushell/nu_scripts/pull/561)
- fdncred created [update `date format` to `format date` in oh-my.nu](https://github.com/nushell/nu_scripts/pull/570), and [delete codeowners file](https://github.com/nushell/nu_scripts/pull/568)
- e2dk4r created [custom-completions: scoop: fix getting environmental variables](https://github.com/nushell/nu_scripts/pull/567)
- kjelly created [Add descriptions for the docker module.](https://github.com/nushell/nu_scripts/pull/549)

## reedline

- fdncred created [turn off default prompt styling (bold) to prevent leakage](https://github.com/nushell/reedline/pull/615)
