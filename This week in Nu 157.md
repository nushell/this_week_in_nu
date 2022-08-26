# This week in Nushell #157


## Nushell


- fdncred [added the ast command to peek at the internals of nushell](https://github.com/nushell/nushell/pull/6423), and [convert string duration to named duration](https://github.com/nushell/nushell/pull/6406), and [add a plugin registration script](https://github.com/nushell/nushell/pull/6395), and [add another split words example](https://github.com/nushell/nushell/pull/6394), and [add edit distance/levenshtein command](https://github.com/nushell/nushell/pull/6383), and [add MessagePack as a plugin protocol](https://github.com/nushell/nushell/pull/6370), and [fix the way lists are rendered in markdown](https://github.com/nushell/nushell/pull/6369) 
- WindSoilder [tried to make argument with quotes for external command better](https://github.com/nushell/nushell/pull/6420), and [Plugin: Add benchmark for different encoding protocol](https://github.com/nushell/nushell/pull/6384), and [Rename overlay commands](https://github.com/nushell/nushell/pull/6375) 
- nibon7 [made run_external parameter required](https://github.com/nushell/nushell/pull/6418), and [Fix the span of "invalid time zone"](https://github.com/nushell/nushell/pull/6411), and [register-plugin.nu: refactor register plugin](https://github.com/nushell/nushell/pull/6409), and [register-plugin.nu: remove `.exe` extension match to simplify code](https://github.com/nushell/nushell/pull/6400), and [Add test cases for $nu.config-path change](https://github.com/nushell/nushell/pull/6385), and [Get `$nu.config-path` and `$nu.env-path` from `EngineState`](https://github.com/nushell/nushell/pull/6366) 
- herlon214 created [nu-command/filters: drop column check positive value](https://github.com/nushell/nushell/pull/6412), and [nu-cli: merge completions tests into one file](https://github.com/nushell/nushell/pull/6389), and [feat: external completions for commands/flags](https://github.com/nushell/nushell/pull/6295) 
- rgwood created [Always report errors in `cp`](https://github.com/nushell/nushell/pull/6404), and [Make `cp` errors more specific+accurate](https://github.com/nushell/nushell/pull/6396), and [Add pause and cls to cmd.exe exceptions](https://github.com/nushell/nushell/pull/6371) 
- sholderbach [fixed search terms for `str distance`](https://github.com/nushell/nushell/pull/6398), and [[Experiment] Reenable CI build cache for tests](https://github.com/nushell/nushell/pull/6390), and [Test command names and search terms for redundancy](https://github.com/nushell/nushell/pull/6380) 
- kubouch [allowed "export-env" parsing in modules](https://github.com/nushell/nushell/pull/6382), and [Allow parsing modules as scripts](https://github.com/nushell/nushell/pull/6357) 
- merelymyself [preserved space by letting `to nuon` only add quotes when necessary](https://github.com/nushell/nushell/pull/6379), and [let `to nuon` convert column names with spaces](https://github.com/nushell/nushell/pull/6376), and [default to file completion after first command, add `command` option for completions](https://github.com/nushell/nushell/pull/6257) 

## Documentation


- CAD97 created [Note status of calling CMD builtins from Nushell](https://github.com/nushell/nushell.github.io/pull/573), and [Note Windows caveat in Escaping to the System](https://github.com/nushell/nushell.github.io/pull/572), and [Mention coming_from_cmd in coming_to_nu](https://github.com/nushell/nushell.github.io/pull/571), and [Update coming_from_cmd.md for nu 0.77](https://github.com/nushell/nushell.github.io/pull/570) 
- amtoine created [FIX: `overlay remove` flags](https://github.com/nushell/nushell.github.io/pull/565) 

## Nu_Scripts


- Yethal created [Add function to remove diacritics from string](https://github.com/nushell/nu_scripts/pull/283) 
- fdncred created [remove engine-q references](https://github.com/nushell/nu_scripts/pull/282) 
- e2dk4r created [custom completions: scoop: add some missing command completions](https://github.com/nushell/nu_scripts/pull/281), and [custom completions: scoop: add some missing command completions](https://github.com/nushell/nu_scripts/pull/280) 

## reedline


- morzel85 created [README.md outline cleanup](https://github.com/nushell/reedline/pull/466) 
