# This week in Nushell #174


## Nushell


- webbedspace [created a new `values` command (see #7166)](https://github.com/nushell/nushell/pull/7583), and [fixed signatures of commands which accept records also](https://github.com/nushell/nushell/pull/7582), and [Change other instances of `$nothing` to `null`](https://github.com/nushell/nushell/pull/7569), and [Fix #7551 record support in `color_config`](https://github.com/nushell/nushell/pull/7567), and [Remove preview.rs](https://github.com/nushell/nushell/pull/7555), and [Fix `encode base64` type signature and examples](https://github.com/nushell/nushell/pull/7515), and [Make `$in` work in `catch` closures](https://github.com/nushell/nushell/pull/7458), and [Make `config.filesize_format`/`config.filesize_metric` conflict resolution consistent](https://github.com/nushell/nushell/pull/7410), and [Standardise the use of ShellError::UnsupportedInput and ShellError::TypeMismatch and add spans to every instance of the former](https://github.com/nushell/nushell/pull/7217), and [color_config now accepts closures as color values](https://github.com/nushell/nushell/pull/7141)
- zhiburt [fixed nu-explore configuration issues](https://github.com/nushell/nushell/pull/7520), and [Patch explore 4](https://github.com/nushell/nushell/pull/7517), and [Patch after fix after fix 7380](https://github.com/nushell/nushell/pull/7501)
- rgwood [made `to text` stream ListStreams](https://github.com/nushell/nushell/pull/7577), and [added some cell path tests](https://github.com/nushell/nushell/pull/7563), and [added cross-rs config](https://github.com/nushell/nushell/pull/7559), and [Clarify `--stdin` flag](https://github.com/nushell/nushell/pull/7541), and [`explore` tweaks Round 1](https://github.com/nushell/nushell/pull/7511), and [`table`: Check stream timeout on every item](https://github.com/nushell/nushell/pull/7509), and [Fix cell path when getting columns of non-records](https://github.com/nushell/nushell/pull/7508)
- kubouch  [added "fall-through" signatures](https://github.com/nushell/nushell/pull/7527),and  [Remove shape-directed import pattern parsing](https://github.com/nushell/nushell/pull/7570), and [Small parser refactors](https://github.com/nushell/nushell/pull/7568), and [Initial support for parse-time constants](https://github.com/nushell/nushell/pull/7436)
- sholderbach  [added more input/output type annotations](https://github.com/nushell/nushell/pull/7532), and [Fix `&&` quotation in `to nuon` after proptest fail](https://github.com/nushell/nushell/pull/7564), and [Bump to new development version `0.73.1`](https://github.com/nushell/nushell/pull/7544), and [Remove unused deps or move to devdeps](https://github.com/nushell/nushell/pull/7537)
- swarnimarun created [chore: make the config setup messages consistent](https://github.com/nushell/nushell/pull/7560)
- fdncred created [fix the wix file to overwrite with save -f](https://github.com/nushell/nushell/pull/7545), and [add xterm color names to `ansi --list`](https://github.com/nushell/nushell/pull/7513)
- jntrnr [bumped to 0.73](https://github.com/nushell/nushell/pull/7542), and [Turn off `cd` abbreviations by default](https://github.com/nushell/nushell/pull/7536)
- merelymyself [let case_insensitive option work for variable completion as well](https://github.com/nushell/nushell/pull/7539), and [prevent panic with format command](https://github.com/nushell/nushell/pull/7522), and [tighter restrictions on `alias` and `def` names](https://github.com/nushell/nushell/pull/7392)
- WindSoilder [fixed a panic when using from nuon](https://github.com/nushell/nushell/pull/7533)
- pinjeff [replaced lazy_static with once_cell](https://github.com/nushell/nushell/pull/7502)
- raccmonteiro [added some filesystem command signatures](https://github.com/nushell/nushell/pull/7464)

## Documentation

- Tengs-Penkwe created [Add section "Output result to external commands"](https://github.com/nushell/nushell.github.io/pull/713)
- sschneider-ihre-pvs created [Update help.md](https://github.com/nushell/nushell.github.io/pull/712)
- merelymyself created [clarify columns and rows](https://github.com/nushell/nushell.github.io/pull/711)
- rgwood created [Mention breaking save change](https://github.com/nushell/nushell.github.io/pull/710)
- sholderbach created [Add explore mode screenshot](https://github.com/nushell/nushell.github.io/pull/709), and [[WIP] Release notes for `0.73`](https://github.com/nushell/nushell.github.io/pull/690)
- WindSoilder created [add breaking change for fetch](https://github.com/nushell/nushell.github.io/pull/708)
- webbedspace created [[release-notes-0.73] Add color closures and deeply mutable data structure features](https://github.com/nushell/nushell.github.io/pull/707)
- rsteube created [custom completion: added external_completer](https://github.com/nushell/nushell.github.io/pull/706)
- zhiburt created [Add a description file for `explore` command](https://github.com/nushell/nushell.github.io/pull/704)
- hustcer created [Update book/make_docs.nu for nu v0.72.1+](https://github.com/nushell/nushell.github.io/pull/699)


## Nu_Scripts

- maxim-uvarov created [Function to format nicely big numbers: number-format.nu](https://github.com/nushell/nu_scripts/pull/332)
- fdncred made [just a couple tweaks to scripts](https://github.com/nushell/nu_scripts/pull/331)
- jntrnr created [Since last release script](https://github.com/nushell/nu_scripts/pull/330)

## reedline

- sholderbach [fix the Github actions badge](https://github.com/nushell/reedline/pull/523)
- CozyPenguin [made reedline handling cursor shapes more configurable](https://github.com/nushell/reedline/pull/515)
