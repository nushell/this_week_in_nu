# This week in Nushell #196


## Nushell

- fdncred [updated most dependencies except where deeper code changes are needed](https://github.com/nushell/nushell/pull/9296), and [if --no-config-file(-n) is passed, do not load config files with -c](https://github.com/nushell/nushell/pull/9286), and [some minor color fixups](https://github.com/nushell/nushell/pull/9270)
- amtoine [refactored the `lib.rs` of `nu-std` after the new virtual files PR](https://github.com/nushell/nushell/pull/9289), and [add a new `toolkit install` command with `--features` support](https://github.com/nushell/nushell/pull/9288), and [REFACTOR: build help pages instead of printing them](https://github.com/nushell/nushell/pull/9253), and [stdlib: fix the names of the `help` commands in `help.nu`](https://github.com/nushell/nushell/pull/9252), and [CI: disable `nu-coverage`](https://github.com/nushell/nushell/pull/9251), and [REFACTOR: clean the root of the repo](https://github.com/nushell/nushell/pull/9231)
- jntrnr [moveed over to reedline git version](https://github.com/nushell/nushell/pull/9283), and [Fix clippy warnings (upcoming)](https://github.com/nushell/nushell/pull/9282), and [Cut down on unnecessary parsing for SyntaxShape::Any](https://github.com/nushell/nushell/pull/9280)
- bobhy created [std dirs simply stays in sync with CD changes to  PWD](https://github.com/nushell/nushell/pull/9267)
- fnordpig  [fixed version to show build features after crateification](https://github.com/nushell/nushell/pull/9262)
- Tiggax created [throw an error instead of a panic if no input is provided to `inspect`](https://github.com/nushell/nushell/pull/9259)
- merelymyself created [upserting data of a cellpath that doesn't exist into a record creates the cellpath](https://github.com/nushell/nushell/pull/9257), and [allow `view-source` to read rest arguments](https://github.com/nushell/nushell/pull/9247)
- MariaSolOs [allowed duration defaults](https://github.com/nushell/nushell/pull/9249)
- kubouch [added a virtual path abstraction layer](https://github.com/nushell/nushell/pull/9245)
- melMass created [docs: 📝 "http get", add an example with more than one header](https://github.com/nushell/nushell/pull/9240), and [feat: ✨ (stdlib) add os record support to path add](https://github.com/nushell/nushell/pull/9238)
- WindSoilder [added a -u flag to cp, mv command](https://github.com/nushell/nushell/pull/9214)
- hustcer [added aarch64-pc-windows-msvc building target for nu binaries](https://github.com/nushell/nushell/pull/9162)
- Decodetalkers created [check if is homedir first when rm](https://github.com/nushell/nushell/pull/9117)

## Extension

- EmilySeville7cfg created [feat(snippets): support regex groups](https://github.com/nushell/vscode-nushell-lang/pull/130)

## Documentation

- avi-cenna created [Update table.md - Correct `table` examples](https://github.com/nushell/nushell.github.io/pull/934)
- github-actions[bot] created [Compressed Images](https://github.com/nushell/nushell.github.io/pull/933)
- hustcer created [Try to compress image on push to main](https://github.com/nushell/nushell.github.io/pull/932), and [Add a new image for compress test](https://github.com/nushell/nushell.github.io/pull/931), and [Try to add a new workflow to compress images on new pull request](https://github.com/nushell/nushell.github.io/pull/930), and [Lossless compression of image assets](https://github.com/nushell/nushell.github.io/pull/929), and [Remove unnecessary 0.59 binaries](https://github.com/nushell/nushell.github.io/pull/925)
- damiancarrillo created [Update types_of_data.md](https://github.com/nushell/nushell.github.io/pull/927)
- amtoine created [FIX: out of date external completion examples](https://github.com/nushell/nushell.github.io/pull/923), and [FIX: add `| table` to folded tables](https://github.com/nushell/nushell.github.io/pull/918)
- BrianLondon created [update plugins.md in contributor-book](https://github.com/nushell/nushell.github.io/pull/921)
- casually-blue created [Fix references to match in the "coming from" pages to reflect its current usage in Nu](https://github.com/nushell/nushell.github.io/pull/920)

## Nu_Scripts

- Tiggax created [Added missing ?](https://github.com/nushell/nu_scripts/pull/511), and [Added bookmark module](https://github.com/nushell/nu_scripts/pull/509)
- amtoine created [add completion for `toipe`](https://github.com/nushell/nu_scripts/pull/508)
- kubouch created [Add dataframe crate to the release](https://github.com/nushell/nu_scripts/pull/507)

## reedline

- fdncred created [update cargo.lock](https://github.com/nushell/reedline/pull/587), and [update dependencies](https://github.com/nushell/reedline/pull/586)
- jntrnr created [bump reedline version](https://github.com/nushell/reedline/pull/585)
- Banyc created [fix: prompt position on resize](https://github.com/nushell/reedline/pull/578)
