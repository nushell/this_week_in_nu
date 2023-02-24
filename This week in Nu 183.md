# This week in Nushell #183


## Nushell


- alextremblay created [move `hash md5` and `hash sha256` commands to the hash category](https://github.com/nushell/nushell/pull/8196)
- Hofer-Julian created [Force install in `install-all` scripts](https://github.com/nushell/nushell/pull/8194), and [Update polars to 0.27.2](https://github.com/nushell/nushell/pull/8154)
- ryand67 created [remove links to `ShellError` and `ParseError` docs - #8167](https://github.com/nushell/nushell/pull/8193), and [interrupt `input` command with Ctrl + C](https://github.com/nushell/nushell/pull/8159), and [files and directory completions now use ascending ordering rather than Levenshtein. #8023](https://github.com/nushell/nushell/pull/8085)
- fdncred created [fix ansi example so it is tested](https://github.com/nushell/nushell/pull/8192), and [update the manual msi generation instructions for winget](https://github.com/nushell/nushell/pull/8178), and [remove old winget manual release ci](https://github.com/nushell/nushell/pull/8177), and [allow different types of lists to be appended](https://github.com/nushell/nushell/pull/8157), and [update code coversage script to work better with windows](https://github.com/nushell/nushell/pull/8141), and [show more informaiton when there are toml errors](https://github.com/nushell/nushell/pull/8140), and [update link to command reference](https://github.com/nushell/nushell/pull/8111), and [fixes a def parsing bug with a default list](https://github.com/nushell/nushell/pull/8096)
- sholderbach created [Add links to the remaining README badges](https://github.com/nushell/nushell/pull/8191), and [Disable Windows coverage tracking for now](https://github.com/nushell/nushell/pull/8190), and [Update to `0.76.1` version for development](https://github.com/nushell/nushell/pull/8161), and [Fix `Cargo.toml` of `nu_plugin_formats`](https://github.com/nushell/nushell/pull/8160), and [Pin `reedline` to `0.16.0`](https://github.com/nushell/nushell/pull/8142), and [Add a script to generate coverage locally](https://github.com/nushell/nushell/pull/8125), and [Bump version for `0.76.0` release](https://github.com/nushell/nushell/pull/8121)
- stormasm created [Cratification: Break out nu_cmd_lang into a separate crate](https://github.com/nushell/nushell/pull/8181)
- SUPERCILEX created [Compress $HOME into ~ in prompt](https://github.com/nushell/nushell/pull/8173)
- zhiburt created [table --collapse dont do truncation return message instead](https://github.com/nushell/nushell/pull/8172), and [Add colors in `table --collapse`](https://github.com/nushell/nushell/pull/8120), and [nu-table/ Fix --collapse wrap/truncate [WIP]](https://github.com/nushell/nushell/pull/8042)
- Yethal created [Added examples to query web plugin](https://github.com/nushell/nushell/pull/8171)
- MangoIV created [chore: add a couple of direnv specific files to the gitignore](https://github.com/nushell/nushell/pull/8165), and [fix: fix lexing of comments, such that a#b becomes a coherent Item](https://github.com/nushell/nushell/pull/8151)
- WindSoilder created [check external failed in let assignment](https://github.com/nushell/nushell/pull/8164), and [simplify `parse_expression` function code.](https://github.com/nushell/nushell/pull/8149), and [add usage for plugin commands](https://github.com/nushell/nushell/pull/8138), and [Dependency update: update notify version to v5](https://github.com/nushell/nushell/pull/8114), and [update nu_plugin_python due to signature changes](https://github.com/nushell/nushell/pull/8107), and [remove git completion in default config](https://github.com/nushell/nushell/pull/8087)
- webbedspace created [Fix one error message in `into string`](https://github.com/nushell/nushell/pull/8163), and [Add `select` extra_usage explaining relationship to `get`](https://github.com/nushell/nushell/pull/8146)
- amtoine created [TEST: add the output to the new `with-env` example](https://github.com/nushell/nushell/pull/8148), and [DOCUMENTATION: add a new "key-value" example to `with-env`](https://github.com/nushell/nushell/pull/8119)
- jaudiger created [HTTP HEAD / PATCH / PUT / DELETE commands](https://github.com/nushell/nushell/pull/8144), and [Final rework for the HTTP commands](https://github.com/nushell/nushell/pull/8135)
- bobhy created [`string | fill` counts  clusters, not graphemes; and doesn't count ANSI escape codes](https://github.com/nushell/nushell/pull/8134)
- dependabot[bot] created [Bump actions-rust-lang/setup-rust-toolchain from 1.3.7 to 1.4.2](https://github.com/nushell/nushell/pull/8133), and [Bump sysinfo from 0.27.7 to 0.28.0](https://github.com/nushell/nushell/pull/8132), and [Bump errno from 0.2.8 to 0.3.0](https://github.com/nushell/nushell/pull/8131), and [Bump uuid from 1.2.2 to 1.3.0](https://github.com/nushell/nushell/pull/8130), and [Bump winreg from 0.10.1 to 0.11.0](https://github.com/nushell/nushell/pull/8128)
- kubouch created [Revert #7779 (enables back subcommand completions)](https://github.com/nushell/nushell/pull/8102)
- sitiom created [use winget releaser action for manifest submission](https://github.com/nushell/nushell/pull/8070)
- Xoffio created [`cp` progress bar implementation](https://github.com/nushell/nushell/pull/8012)
- NotLebedev created [Display empty records and lists](https://github.com/nushell/nushell/pull/7925)

## Documentation

- hustcer created [Add short flags to command docs, fix #509](https://github.com/nushell/nushell.github.io/pull/795), and [Add registry query doc for Windows](https://github.com/nushell/nushell.github.io/pull/794), and [Refresh docs for v0.76](https://github.com/nushell/nushell.github.io/pull/791)
- Hofer-Julian created [Generate categories](https://github.com/nushell/nushell.github.io/pull/793), and [Fix typo](https://github.com/nushell/nushell.github.io/pull/792), and [Prepare for generation of categories](https://github.com/nushell/nushell.github.io/pull/789)
- WindSoilder created [Add breaking change](https://github.com/nushell/nushell.github.io/pull/790)
- sholderbach created [Release notes for `0.76`](https://github.com/nushell/nushell.github.io/pull/770)


## Nu_Scripts


- Kinchkun created [job.nu: update view source usage](https://github.com/nushell/nu_scripts/pull/392)
- baehyunsol created [make `up.nu` much simpler](https://github.com/nushell/nu_scripts/pull/391), and [remove `build-string`, which is deprecated](https://github.com/nushell/nu_scripts/pull/390)
- fdncred created [updates for new dfr names](https://github.com/nushell/nu_scripts/pull/389), and [rename misc folder](https://github.com/nushell/nu_scripts/pull/388), and [fix text where comments don't have spaces](https://github.com/nushell/nu_scripts/pull/387)
- Yethal created [Create to-ini.nu](https://github.com/nushell/nu_scripts/pull/386)
- sholderbach created [Update release script to `nu_plugin_formats`](https://github.com/nushell/nu_scripts/pull/384)
- amtoine created [FEATURE: export all the math functions to use them in `nushell`](https://github.com/nushell/nu_scripts/pull/382), and [FIX: the math functions can not be `use`d](https://github.com/nushell/nu_scripts/pull/381)

## reedline

- sholderbach created [Bump version for `0.16.0` release.](https://github.com/nushell/reedline/pull/542), and [Bump `rstest` to 0.16](https://github.com/nushell/reedline/pull/541)

## Nana


- jaudiger created [Update to latest Nushell / Reedline.](https://github.com/nushell/nana/pull/76), and [Update Cargo and Yarn dependencies](https://github.com/nushell/nana/pull/75)
