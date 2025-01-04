# This week in Nushell #280

## Nushell

- NotTheDr01ds worked on SHLVL ([1](https://github.com/nushell/nushell/pull/14732), [2](https://github.com/nushell/nushell/pull/14727)), [added a user-level autoload directory](https://github.com/nushell/nushell/pull/14669), [removed no-longer-needed `convert_env_values` calls](https://github.com/nushell/nushell/pull/14681), [improved `open` to assign `content_type` metadata for filetypes not handled with a `from` converter](https://github.com/nushell/nushell/pull/14670), and [added a comment on `nu_repl` usage](https://github.com/nushell/nushell/pull/14734)
- rikukiix [made exec command decrement SHLVL correctly & added a SHLVL related test](https://github.com/nushell/nushell/pull/14707)
- cptpiepmatz worked on boolean coercion ([1](https://github.com/nushell/nushell/pull/14731), [2](https://github.com/nushell/nushell/pull/14704))
- ayax79 [provided the ability to split strings in columns via `polars str-split`](https://github.com/nushell/nushell/pull/14723)
- ysthakur [made `utouch` the new `touch`](https://github.com/nushell/nushell/pull/14721) and [created a `nu_glob::is_glob` function](https://github.com/nushell/nushell/pull/14717)
- fdncred [improved error messages for "sum", "product", and "sum_of_squares"](https://github.com/nushell/nushell/pull/14711) and [replaced regex crate with fancy_regex](https://github.com/nushell/nushell/pull/14646)
- zhiburt [fixed a `tabled` panic](https://github.com/nushell/nushell/pull/14710)
- sholderbach [promoted a note about `internal_span` to doccomment](https://github.com/nushell/nushell/pull/14703)
- 132ikl [removed usages of `internal_span`](https://github.com/nushell/nushell/pull/14700)
- NiceGuyIT [fixed a command description](https://github.com/nushell/nushell/pull/14696)
- 0x4D5352 [improved example formatting in README.md](https://github.com/nushell/nushell/pull/14695)
- hjetmundsen [added glob support to `utouch`](https://github.com/nushell/nushell/pull/14674)
- tsukimizake [stopped multiline prompts from removing the last newline](https://github.com/nushell/nushell/pull/14590)

## Documentation

- jesper-olsen [updated loading_data.md](https://github.com/nushell/nushell.github.io/pull/1733) and [updated thinking_in_nu.md](https://github.com/nushell/nushell.github.io/pull/1731)
- ysthakur [used white foreground for copy code button](https://github.com/nushell/nushell.github.io/pull/1730), [documented custom completion options and styling](https://github.com/nushell/nushell.github.io/pull/1726), and [used dark-plus in code blocks for light mode also](https://github.com/nushell/nushell.github.io/pull/1723)
- alexandregv [fixed a broken link and a typo](https://github.com/nushell/nushell.github.io/pull/1725)
- 132ikl [updated example in working with lists to reflect changes to ++ operator](https://github.com/nushell/nushell.github.io/pull/1720)
- 0x4D5352 [added Japanese and Portuguese book](https://github.com/nushell/nushell.github.io/pull/1698) and [added Spanish and French book](https://github.com/nushell/nushell.github.io/pull/1697)

## Nu_Scripts

- NotTheDr01ds [removed some outdated comments](https://github.com/nushell/nu_scripts/pull/1008)
- fantasyzhjk [updated rbenv module](https://github.com/nushell/nu_scripts/pull/1007)
- kjelly [added support for nu 101 in argx module](https://github.com/nushell/nu_scripts/pull/1006)
- Bahex [fixed propagation of errors from aggregate operation closures](https://github.com/nushell/nu_scripts/pull/1005) and [added `aggregate` to stdlib-candidate](https://github.com/nushell/nu_scripts/pull/991)
- WindSoilder [added `path replace-extension` to stdlib-candidate](https://github.com/nushell/nu_scripts/pull/1002)

