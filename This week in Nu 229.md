# This week in Nushell #229


## Nushell

- NotLebedev [fixed incorrect handling of boolean flags for builtin commands](https://github.com/nushell/nushell/pull/11492), and [added a file attribute handling flag to cp](https://github.com/nushell/nushell/pull/11491)
- WindSoilder [added a type check during eval time](https://github.com/nushell/nushell/pull/11475)
- schrieveslaach [fixed a "Char index out of bounds" error](https://github.com/nushell/nushell/pull/11526)
- crides [fixed an edge case in `path exists`](https://github.com/nushell/nushell/pull/11515)
- abusch [improved closure captures to handle constants](https://github.com/nushell/nushell/pull/11493)
- ysthakur [fixed the only_buffer_difference completion menu setting](https://github.com/nushell/nushell/pull/11488)
- amtoine [removed `std clip`](https://github.com/nushell/nushell/pull/11131)
- fdncred pulled in reedline updates: [1](https://github.com/nushell/nushell/pull/11528), [2](https://github.com/nushell/nushell/pull/11520)
- kubouch did some version bumps: [1](https://github.com/nushell/nushell/pull/11513), [2](https://github.com/nushell/nushell/pull/11511), [3](https://github.com/nushell/nushell/pull/11510)

## Extension

- fdncred created [Prepare for release 180](https://github.com/nushell/vscode-nushell-lang/pull/170)

## Documentation

- TWSiO created [Adding range related info.](https://github.com/nushell/nushell.github.io/pull/1206), and [Updating cookbook intro page due to discord channel rename and other editing.](https://github.com/nushell/nushell.github.io/pull/1205), and [Adding warning to nu_plugin_formats commands](https://github.com/nushell/nushell.github.io/pull/1199)
- hustcer created [Refresh command docs for Nu v0.89](https://github.com/nushell/nushell.github.io/pull/1204)
- kubouch created [Add some notes](https://github.com/nushell/nushell.github.io/pull/1202), and [Add some notes](https://github.com/nushell/nushell.github.io/pull/1200)
- yukitomoda created [JA update installation.md](https://github.com/nushell/nushell.github.io/pull/1198), and [JA update shells_in_shells.md](https://github.com/nushell/nushell.github.io/pull/1197)
- YukiOnodera created [Updated ja documents to align with cfc7b0d](https://github.com/nushell/nushell.github.io/pull/1186)
- amtoine created [mark feature-gated commands more clearly](https://github.com/nushell/nushell.github.io/pull/1183), and [Release notes for `0.89.0`](https://github.com/nushell/nushell.github.io/pull/1174)

## Nu_Scripts

- TWSiO created [Adding some examples of how to treat a list like other data structures.](https://github.com/nushell/nu_scripts/pull/733), and [Adding http oneliner and changing reference to renamed Discord channel.](https://github.com/nushell/nu_scripts/pull/731)
- fdncred created [do not require stash in git stash drop](https://github.com/nushell/nu_scripts/pull/732)
- simba909 created [Fix gh status completion](https://github.com/nushell/nu_scripts/pull/730)
- fj0r created [upgrade to 0.89](https://github.com/nushell/nu_scripts/pull/729)

## reedline

- fdncred created [Revert "Fix move to line start in multi-line history entries"](https://github.com/nushell/reedline/pull/704)
- kubouch created [Bump version for 0.28 release](https://github.com/nushell/reedline/pull/702)
- ysthakur created [Print rest of line after cursor with large completion menu](https://github.com/nushell/reedline/pull/700), and [Don't slice line in DefaultCompleter](https://github.com/nushell/reedline/pull/695)
- ClementNerma created [Make `ReedlineErrorVariants` public](https://github.com/nushell/reedline/pull/679)
- boathouse2112 created [Fix move to line start in multi-line history entries](https://github.com/nushell/reedline/pull/584)
