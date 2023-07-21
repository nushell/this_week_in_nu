# This week in Nushell #204


## Nushell

- WindSoilder made redirection improvements: [make `o>`, `e>`, `o+e>`'s target support variables and string interpolation](https://github.com/nushell/nushell/pull/9747)
- jntrnr [fixed capture logic for inner closures](https://github.com/nushell/nushell/pull/9754), and [fixed the input signature of let/mut](https://github.com/nushell/nushell/pull/9695), and [reverted "Fix SIGTTIN handling"](https://github.com/nushell/nushell/pull/9694)
- 1Kinoti added [match guards](https://github.com/nushell/nushell/pull/9621)
- atahabaki updated [str-expand: new capability, empty collection item](https://github.com/nushell/nushell/pull/9750)
- fdncred set [history_isolation to false](https://github.com/nushell/nushell/pull/9763), and [changed the default of history.isolation](https://github.com/nushell/nushell/pull/9762), and [handle sqlite tables better by surrounding with brackets](https://github.com/nushell/nushell/pull/9752), and [add range input to par-each](https://github.com/nushell/nushell/pull/9749), and [normalize default_config/env formatting](https://github.com/nushell/nushell/pull/9731), and [allow range as a input_output_type on filter](https://github.com/nushell/nushell/pull/9707)
- stormasm [added a Readme for the crate nu-cmd-extra](https://github.com/nushell/nushell/pull/9745)
- amtoine [added `any -> record` to `metadata`](https://github.com/nushell/nushell/pull/9755), and [allowed `into filesize` to take tables as input / output](https://github.com/nushell/nushell/pull/9706), and [synced default config / env with default behaviour without any configuration](https://github.com/nushell/nushell/pull/9676), and [changed the output of `which` to be more explicit](https://github.com/nushell/nushell/pull/9646)
- IanManske added [functions for each `Value` case](https://github.com/nushell/nushell/pull/9736), and fixed [nushell should be non-interactive if `--testbin` is supplied](https://github.com/nushell/nushell/pull/9730), and fixed [Do not attempt to take control of terminal in non-interactive mode](https://github.com/nushell/nushell/pull/9693)
- sholderbach [removed underused devdep `getset`](https://github.com/nushell/nushell/pull/9727), and [cleaned up tests containing unnecessary `cwd:` tokens](https://github.com/nushell/nushell/pull/9692)
- dmatos2012 [disallowed empty record with empty key,value pairs on ini format](https://github.com/nushell/nushell/pull/9722)
- cramt fixed [removing symlinks on windows](https://github.com/nushell/nushell/pull/9704)
- mengsuenyan fixed [`detect columns` with the flag `-c`](https://github.com/nushell/nushell/pull/9667)
- nibon7 removed [the `is-root` crate](https://github.com/nushell/nushell/pull/9615)
- hexavik [removed unnecessary `r#"..."#`](https://github.com/nushell/nushell/pull/9764)

## Documentation

- Heidar-An created [Update nushell_map_imperative.md](https://github.com/nushell/nushell.github.io/pull/986)
- JoaquinTrinanes created [Add external completers cookbook entry to sidebar](https://github.com/nushell/nushell.github.io/pull/985), and [Expand external completer docs](https://github.com/nushell/nushell.github.io/pull/984)
- amtoine created [refactor `ssh-agent` cookbook example](https://github.com/nushell/nushell.github.io/pull/982), and [remove all `| table` from the book](https://github.com/nushell/nushell.github.io/pull/976)

## Nu_Scripts

- jntrnr created [Update some benchmarks. Re-port the gradient benchmark](https://github.com/nushell/nu_scripts/pull/558)
- amtoine created [make the release note TODOs HTML comments](https://github.com/nushell/nu_scripts/pull/557), and [move the extra menus of Nushell into `custom-menus/extra/`](https://github.com/nushell/nu_scripts/pull/550)
- JalonWong created [Add a git prompt](https://github.com/nushell/nu_scripts/pull/555)
- fj0r created [ssh complete cache use whitelist](https://github.com/nushell/nu_scripts/pull/553)

## reedline

- sholderbach created [Update the `Cargo.lock` for tests and demo](https://github.com/nushell/reedline/pull/611), and [Fix clippy lint for DoubleEndedIterator](https://github.com/nushell/reedline/pull/610)
- nibon7 created [Fix big_word_left_index](https://github.com/nushell/reedline/pull/609)
