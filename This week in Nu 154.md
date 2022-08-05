# This week in Nushell #154


## Nushell


- nibon7 [exported `get_shells` and `get_current_shell`](https://github.com/nushell/nushell/pull/6236), and [Fix color parsing](https://github.com/nushell/nushell/pull/6234), and [Return error early if seconds part of timestamp is invalid](https://github.com/nushell/nushell/pull/6193), and [Fix path_contains_hidden_folder](https://github.com/nushell/nushell/pull/6173) 
- hustcer [upgraded chrono to v0.4.20](https://github.com/nushell/nushell/pull/6235), and [Some code refactor for shells related commands](https://github.com/nushell/nushell/pull/6226), and [add `bits ror` and `bits rol` commands](https://github.com/nushell/nushell/pull/6224), and [Add `bits shl` and `bits shr` command](https://github.com/nushell/nushell/pull/6202) 
- fdncred [pointed to the latest main branch for lscolors](https://github.com/nushell/nushell/pull/6230), and [remove the nana filename string, add some exclusions to gitignore](https://github.com/nushell/nushell/pull/6228), and [replace the regex crate with the fancy-regex crate](https://github.com/nushell/nushell/pull/6227), and [allow uppercase chars to be captured during suppressed input](https://github.com/nushell/nushell/pull/6199) 
- merelymyself [made `cd`, `cp`, `ls`, `mv`, `open` and `rm` automatically strip ansi codes](https://github.com/nushell/nushell/pull/6220), and [allow `-h` flags for `export` subcommands](https://github.com/nushell/nushell/pull/6189), and [adds a `config reset` command](https://github.com/nushell/nushell/pull/6149) 
- elferherrera created [sqlite query without collect](https://github.com/nushell/nushell/pull/6217), and [use `from table` to remove into-db command](https://github.com/nushell/nushell/pull/6205) 
- sholderbach [Reduced dev-deps by narrowing `rstest` features](https://github.com/nushell/nushell/pull/6215), and [Make `open` test independent of locale](https://github.com/nushell/nushell/pull/6211), and [Patch `lscolors` to not blink](https://github.com/nushell/nushell/pull/6210) 
- WindSoilder created [In unix like system, set foreground process while running external command](https://github.com/nushell/nushell/pull/6206) 
- rgwood created [Faster SQLite reads](https://github.com/nushell/nushell/pull/6204), and [Change `query` command to `query db`](https://github.com/nushell/nushell/pull/6200), and [Add $OLDPWD example for cd](https://github.com/nushell/nushell/pull/6194) 
- Kangaxx-0 [tweaked how nu identifies custom command](https://github.com/nushell/nushell/pull/6187) 

## Documentation


- amtoine created [FIX: update the links to the default config files](https://github.com/nushell/nushell.github.io/pull/552) 
- jeremiahpslewis created [Update links to config template](https://github.com/nushell/nushell.github.io/pull/550) 
- rgwood created [Document SQLite data loading](https://github.com/nushell/nushell.github.io/pull/549) 
- petrisch created [DE Translation for Coloring and Theming ](https://github.com/nushell/nushell.github.io/pull/548) 

## Nu_Scripts


- fdncred created [update some scripts from dash to underscore, add 20k_club script](https://github.com/nushell/nu_scripts/pull/271) 
- WindSoilder created [Migrate some scripts to fit new variable and arguments naming style](https://github.com/nushell/nu_scripts/pull/268) 

## reedline

- bnprks created [Vi mode add support for d0, d^, c0, and c^](https://github.com/nushell/reedline/pull/459) 
- sholderbach created [Reduce dev-deps by narrowing `rstest` features](https://github.com/nushell/reedline/pull/458), and [Export the crossterm key types](https://github.com/nushell/reedline/pull/457) 

