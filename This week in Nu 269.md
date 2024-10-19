# This week in Nushell #269

## Nushell

- fdncred [allowed `group-by` and `split-by` to work with other values](https://github.com/nushell/nushell/pull/14086), [added rendered and json error messages in try/catch](https://github.com/nushell/nushell/pull/14082), [reverted "Add the `history import` command"](https://github.com/nushell/nushell/pull/14077), and [added `like` and `not-like` operators as synonyms for the regex operators `=~` and `!~`](https://github.com/nushell/nushell/pull/14072)
- IanManske [fixed an issue with the last exit code not being set](https://github.com/nushell/nushell/pull/14120), and [fixed keybinding parsing](https://github.com/nushell/nushell/pull/14081)
- 132ikl [added count to uniq search terms](https://github.com/nushell/nushell/pull/14108) and [rate-limited save command progress bar updates](https://github.com/nushell/nushell/pull/14075)
- ayax79 [updated to rust 1.80.1](https://github.com/nushell/nushell/pull/14106), [implemented `polars unnest`](https://github.com/nushell/nushell/pull/14104), and [bumped reedline to version 0.36](https://github.com/nushell/nushell/pull/14093)
- YizhePKU [reduced duplicate dependencies on the `windows` crate](https://github.com/nushell/nushell/pull/14105)
- devyn [made `plugin list` read state from plugin registry file as well](https://github.com/nushell/nushell/pull/14085)
- hustcer [added a workflow to set milestone for a merged PR automatically](https://github.com/nushell/nushell/pull/14084)
- sgvictorino [ran ensure_flag_arg_type for short flag values](https://github.com/nushell/nushell/pull/14074)
- WindSoilder [prevented `use` command from creating a variable with empty record if it doesn't define any constants](https://github.com/nushell/nushell/pull/14051) and [changed display_error.exit_code to false by default](https://github.com/nushell/nushell/pull/13873)

## Documentation

- chuckwondo [fixed dataframe python example](https://github.com/nushell/nushell.github.io/pull/1593)
- IanManske [added 0.99.1 release notes](https://github.com/nushell/nushell.github.io/pull/1592), [finished 0.99.0 release notes](https://github.com/nushell/nushell.github.io/pull/1588), [started 0.99.0 release notes](https://github.com/nushell/nushell.github.io/pull/1586), and [added release notes for `0.99.0`](https://github.com/nushell/nushell.github.io/pull/1566)
- vyadh [updated Coming from Bash for reading a secret](https://github.com/nushell/nushell.github.io/pull/1590)
- hustcer [refreshed Nu command docs for v0.99](https://github.com/nushell/nushell.github.io/pull/1587)
- NotTheDr01ds [updated Standard Library for 0.99](https://github.com/nushell/nushell.github.io/pull/1585)

## Nu_Scripts

- louiss0 [fixed errors with yadm command file](https://github.com/nushell/nu_scripts/pull/976) and [rewrote the yadm module](https://github.com/nushell/nu_scripts/pull/975)
- bminer [added find_in command to search files](https://github.com/nushell/nu_scripts/pull/972)

## reedline

- ayax79 [bumped version](https://github.com/nushell/reedline/pull/845) and [implemented VI mode change inside and delete inside functionality](https://github.com/nushell/reedline/pull/844)

