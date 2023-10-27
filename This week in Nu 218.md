# This week in Nushell #218


## Nushell

- fdncred [updated the NU_LIB_DIRS delimiter for command line](https://github.com/nushell/nushell/pull/10837), and [fixed `main` not building due to errors later found in describe](https://github.com/nushell/nushell/pull/10821)
- gaetschwartz [fixed `describe -d` for lazy records](https://github.com/nushell/nushell/pull/10836), [added a `detailed` flag for `describe`](https://github.com/nushell/nushell/pull/10795), and [made debug info lazy](https://github.com/nushell/nushell/pull/10728)
- WindSoilder fixed redirection bugs: [1](https://github.com/nushell/nushell/pull/10835), [2](https://github.com/nushell/nushell/pull/10816)
- tertsdiepraam [implemented whoami using uutils](https://github.com/nushell/nushell/pull/10488)
- hudclark [extended pattern matching to support `null` literals](https://github.com/nushell/nushell/pull/10829), and [improved the `--flexible` flag on `from tsv` and `from csv`](https://github.com/nushell/nushell/pull/10814)
- ayax79 [added dataframe support for small int types](https://github.com/nushell/nushell/pull/10828)
- ludwig-austermann created [readded the `--update` flag to `cp`](https://github.com/nushell/nushell/pull/10824)
- sholderbach [reverted "Bump regex from 1.9.6 to 1.10.2"](https://github.com/nushell/nushell/pull/10818)
- amtoine [updated `str downcase` to use `to_lowercase`](https://github.com/nushell/nushell/pull/10850), and [deprecated `glob --not` in favor of `glob --exclude`](https://github.com/nushell/nushell/pull/10827), and [expand paths and split PATH in `std path add`](https://github.com/nushell/nushell/pull/10710), and [synced `$env.config.filesize.metric`](https://github.com/nushell/nushell/pull/10277)
- kubouch [finished removing the `profile` command and related data](https://github.com/nushell/nushell/pull/10807)
- CAD97 [improved `registry value` return types](https://github.com/nushell/nushell/pull/10806), and [removed the registry clean_string hack](https://github.com/nushell/nushell/pull/10804)
- hustcer [moved `ansi link` from extra to default feature](https://github.com/nushell/nushell/pull/10801), [renamed `str size` to `str stats`](https://github.com/nushell/nushell/pull/10798), [updated Nushell version to v0.86 for release script](https://github.com/nushell/nushell/pull/10797)
- stfacc [fixed theming to not use white text in the default light theme](https://github.com/nushell/nushell/pull/10796)


## Extension

- Yakiyo created [automatically publish extension to open vsx registry on release](https://github.com/nushell/vscode-nushell-lang/pull/161)

## Documentation

- xBLACKICEx created [zh-CN translation update dataframes](https://github.com/nushell/nushell.github.io/pull/1129)
- Roba1993 created [Book scripts with sub-commands](https://github.com/nushell/nushell.github.io/pull/1128)
- CBenoit created [Add a note on theming Reedline’s menus](https://github.com/nushell/nushell.github.io/pull/1127)
- sholderbach created [Update list of "types" i.e. syntax shapes for `def`s](https://github.com/nushell/nushell.github.io/pull/1124)
- rukai created [add translation for bash "command 2>&1 | less"](https://github.com/nushell/nushell.github.io/pull/1123)
- Stromberg90 created [Fixed typo.](https://github.com/nushell/nushell.github.io/pull/1121)
- hustcer created [Update shiki, vuepress plugins and Nushell grammar](https://github.com/nushell/nushell.github.io/pull/1118)
- hatunike created [Update types_of_data.md with "into float"](https://github.com/nushell/nushell.github.io/pull/1117)

## Nu_Scripts

- fdncred created [fix conflicts between git-completions.nu and git-aliases.nu](https://github.com/nushell/nu_scripts/pull/651)
- amtoine created [make hooks a module](https://github.com/nushell/nu_scripts/pull/650), and [make the themes a module](https://github.com/nushell/nu_scripts/pull/648)
- Hullabaloo-and-Howdy-Do created [null-stream.nu as stdlib-candidate](https://github.com/nushell/nu_scripts/pull/649)
