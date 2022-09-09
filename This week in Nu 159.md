# This week in Nushell #159

## Nushell


- CBenoit created [build: update `cpufeatures` crate](https://github.com/nushell/nushell/pull/6527)
- kubouch [required static path for `source-env`](https://github.com/nushell/nushell/pull/6526), and [Disable cyclical module imports](https://github.com/nushell/nushell/pull/6477), and [Fix overlays not preserving hidden env vars](https://github.com/nushell/nushell/pull/6475), and [Fix scoped `overlay use` not finding a module](https://github.com/nushell/nushell/pull/6474)
- sholderbach [improved wording around `all` and `any`](https://github.com/nushell/nushell/pull/6524), and [Pin reedline to 0.11.0 release](https://github.com/nushell/nushell/pull/6497), and [Terminate REPL if not connected to tty input](https://github.com/nushell/nushell/pull/6480)
- merelymyself [stopped panic when typing `module spam { export def-env`](https://github.com/nushell/nushell/pull/6523), and [remove panic from `lpad` and `rpad`, change truncation behaviour for `lpad`](https://github.com/nushell/nushell/pull/6495), and [let path split keeps 'C:\' together](https://github.com/nushell/nushell/pull/6485)
- Kangaxx-0 [fixed 6252 by remove unit tests](https://github.com/nushell/nushell/pull/6515)
- fdncred [updated register-plugins script to not use encoding](https://github.com/nushell/nushell/pull/6512)
- JayceFayne [fixed typo](https://github.com/nushell/nushell/pull/6508)
- hustcer [updated to nu v0.68 for release workflow](https://github.com/nushell/nushell/pull/6505), and [bump dev version to v0.68.1](https://github.com/nushell/nushell/pull/6504)
- jt [released 0.68](https://github.com/nushell/nushell/pull/6501), and [Revert "Make `$` on variable names optional" (just in case)](https://github.com/nushell/nushell/pull/6446)
- nibon7 [passed `TERM` environment var to clear](https://github.com/nushell/nushell/pull/6500)
- WindSoilder [removed `--encoding` argument during register plugin](https://github.com/nushell/nushell/pull/6486), and [Restrict plugin name starts with `nu_plugin_`](https://github.com/nushell/nushell/pull/6479), and [remove capnp relative file](https://github.com/nushell/nushell/pull/6472)
- unrelentingtech [avoided update_last_command_context "No command run" error](https://github.com/nushell/nushell/pull/6483)
- adamijak [renamed `all?`, `any?` and `empty?`](https://github.com/nushell/nushell/pull/6464)

## Documentation


- WindSoilder created [update plugin for newest changes](https://github.com/nushell/nushell.github.io/pull/600)
- hustcer created [update some zh-CN translations](https://github.com/nushell/nushell.github.io/pull/599), and [Refresh commands for v0.68](https://github.com/nushell/nushell.github.io/pull/595)
- kubouch created [Add missing signature parens to 0.68 blog](https://github.com/nushell/nushell.github.io/pull/596)
- rgwood created [Add Homebrew PATH documentation](https://github.com/nushell/nushell.github.io/pull/592)
- sholderbach created [Update i18n script to `is-empty` name change](https://github.com/nushell/nushell.github.io/pull/591), and [Update former question mark commands in docs](https://github.com/nushell/nushell.github.io/pull/590)
- chrjen created [Update types_of_data.md with missing values](https://github.com/nushell/nushell.github.io/pull/589)
- fdncred created [add 68 blog](https://github.com/nushell/nushell.github.io/pull/574)

## Nu_Scripts

- e2dk4r created [custom completions: scoop: fix getting environmental variables on nu v0.68.0](https://github.com/nushell/nu_scripts/pull/293), and [custom completions: scoop: fix list sub command](https://github.com/nushell/nu_scripts/pull/291)
- ehdevries created [Convert panache-git from script to module](https://github.com/nushell/nu_scripts/pull/292)
- dandavison created [Respond to upstream changes: empty? -> is-empty, TODO list](https://github.com/nushell/nu_scripts/pull/290), and [Async git prompt](https://github.com/nushell/nu_scripts/pull/288)
- Lightfire228 created [[WIP] Feature/auto venv](https://github.com/nushell/nu_scripts/pull/289)
- sholderbach created [Update old question mark commands `any?`/`all?`/`empty?` to `any`/`all`/`is-empty`](https://github.com/nushell/nu_scripts/pull/287)
- amtoine created [add a collection of colorschemes for `nushell`](https://github.com/nushell/nu_scripts/pull/286)

## reedline

- unrelentingtech created [Allow external manipulation of the command line buffer, fixes #423](https://github.com/nushell/reedline/pull/472), and [Add Reedline::has_last_command_context to allow checking if update_last_command_context will fail](https://github.com/nushell/reedline/pull/470)
- sholderbach created [Prepare 0.11.0 release](https://github.com/nushell/reedline/pull/471)

## Nana

- rgwood created [Upgrade Tauri (1.0.2 -> 1.0.5)](https://github.com/nushell/nana/pull/64), and [Add screenshot of Nana to README](https://github.com/nushell/nana/pull/63)

