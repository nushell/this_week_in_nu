# This week in Nushell #178


## Nushell

- WindSoilder [made `save` stream on list stream data](https://github.com/nushell/nushell/pull/7675)
- webbedspace [updated `help <cmd>` to not list deprecated subcommands](https://github.com/nushell/nushell/pull/7798), and [`str length`, `str substring`, `str index-of`, `split words` and `split chars` now use graphemes instead of UTF-8 bytes](https://github.com/nushell/nushell/pull/7752)
- merelymyself created [let `find` take linebreaks into account in `Value::String`](https://github.com/nushell/nushell/pull/7789)
- fdncred [fixed signature display in help commands](https://github.com/nushell/nushell/pull/7802), and [update sqlparser dependency](https://github.com/nushell/nushell/pull/7772), and [update semver dep](https://github.com/nushell/nushell/pull/7771)
- zschaffer [added magenta to ansi command as synonym for purple](https://github.com/nushell/nushell/pull/7785)
- 1Kinoti [added dedicated `const in pipeline`, `const builtin var` errors](https://github.com/nushell/nushell/pull/7784), and [Allow underscores in integers and floats](https://github.com/nushell/nushell/pull/7759)
- Xoffio [fixed Issue 7648 which crashes nushell and happens when an alias name is shorter than the alias command and the alias command is an external command.](https://github.com/nushell/nushell/pull/7779), and [Add test for fix of issue #7754](https://github.com/nushell/nushell/pull/7756)
- DaRacci updated `cd` to [check all user groups](https://github.com/nushell/nushell/pull/7775)
- hustcer [fixed some typos](https://github.com/nushell/nushell/pull/7773)
- afetisov [fixed typos and used more idiomatic assertions](https://github.com/nushell/nushell/pull/7755)
- NotLebedev created a new [ansi link](https://github.com/nushell/nushell/pull/7751) command
- VincenzoCarlino [renamed the `to url` command to `url build-query`](https://github.com/nushell/nushell/pull/7702)
- rgwood created [LazyRecord](https://github.com/nushell/nushell/pull/7619) to speed up startup

## Documentation

- amtoine created [link to default config file in the "explore" page](https://github.com/nushell/nushell.github.io/pull/745), and [remove a broken link in "Introducing nushell" # "Plugins"](https://github.com/nushell/nushell.github.io/pull/744), and [fix a typo on "language", was spelled "langauge"](https://github.com/nushell/nushell.github.io/pull/743)
- waldyrious created [Add two style tweaks to improve tables in code blocks](https://github.com/nushell/nushell.github.io/pull/738)
- hbt created [fix deprecated cmd](https://github.com/nushell/nushell.github.io/pull/667)

## Nu_Scripts

- zoechi created [Change "list of values" to "list of records" with value and description](https://github.com/nushell/nu_scripts/pull/354), and [Export command to make it use-able](https://github.com/nushell/nu_scripts/pull/353), and [Add completions for Bitwarden CLI client](https://github.com/nushell/nu_scripts/pull/350)
- fdncred created [fix ohmy.nu path handling on windows](https://github.com/nushell/nu_scripts/pull/351), and [add timed_weather that checks the weather at timed intervals](https://github.com/nushell/nu_scripts/pull/349), and [fixed a type-o in the weather script](https://github.com/nushell/nu_scripts/pull/348)
- fj0r created [K8s](https://github.com/nushell/nu_scripts/pull/347), and [ssh kubernetes docker git just nvim](https://github.com/nushell/nu_scripts/pull/327)
- fitzypop created [add git_branch_cleanup.nu script and readme](https://github.com/nushell/nu_scripts/pull/346)
- bobhy created [prompt/full-line.nu -- full width prompt](https://github.com/nushell/nu_scripts/pull/345)
- TornaxO7 created [adding git aliases](https://github.com/nushell/nu_scripts/pull/337)
- DrakeTDL created [feat(custom-completions): add reflector completions](https://github.com/nushell/nu_scripts/pull/329)
- ldsands created [Add files needed for Poetry custom-completions](https://github.com/nushell/nu_scripts/pull/319)
