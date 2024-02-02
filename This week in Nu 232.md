# This week in Nushell #232


## Nushell

- WindSoilder made several improvements to globbing ([1](https://github.com/nushell/nushell/pull/11692), [2](https://github.com/nushell/nushell/pull/11664), [3](https://github.com/nushell/nushell/pull/11656)) and [fixed a bug with CTRL-C exit handling when running a script](https://github.com/nushell/nushell/pull/11466)
- Geox644 [improved highlights for `find`](https://github.com/nushell/nushell/pull/11509)
- richardwesthaver [improved 'url join' to print usernames without passwords](https://github.com/nushell/nushell/pull/11697)
- IanManske [refactored and sped up the `lines` command](https://github.com/nushell/nushell/pull/11685), and [added optional strict JSON parsing to `from json`](https://github.com/nushell/nushell/pull/11592)
- ayax79 made improvements to dataframe handling ([1](https://github.com/nushell/nushell/pull/11676), [2](https://github.com/nushell/nushell/pull/11634))
- ysthakur [fixed a parsing bug with the spread operator](https://github.com/nushell/nushell/pull/11674)
- sophiajt [fixed the precedence of the 'not' operator](https://github.com/nushell/nushell/pull/11672)
- maxomatic458 created [add match-text style + config setting for ide menu](https://github.com/nushell/nushell/pull/11670)
- KAAtheWiseGit [fix the error message for passing raw streams into `into record`](https://github.com/nushell/nushell/pull/11668)
- rtpg [tidied up the REPL main loop](https://github.com/nushell/nushell/pull/11655)
- amtoine [added `$.extra_usage` to modules](https://github.com/nushell/nushell/pull/11649)
- davehorner [did a small `ls` refactor](https://github.com/nushell/nushell/pull/11642)
- fdncred [updated the query web wiki example](https://github.com/nushell/nushell/pull/11709), [changed `update cells` column param from Table to List](https://github.com/nushell/nushell/pull/11691), [made the `ansi` command `const`](https://github.com/nushell/nushell/pull/11682), and did some dependency version tweaks ([1](https://github.com/nushell/nushell/pull/11673), [2](https://github.com/nushell/nushell/pull/11695))
- hustcer [disabled the RISCV64 build target temporarily](https://github.com/nushell/nushell/pull/11700)
- nibon7 [bumped the Wayland crate](https://github.com/nushell/nushell/pull/11694)
- stormasm updated Reedline ([1](https://github.com/nushell/nushell/pull/11658), [2](https://github.com/nushell/nushell/pull/11647))

## Documentation

- amtoine created [add the forgotten section to the TOC of 0.89](https://github.com/nushell/nushell.github.io/pull/1234)
- hustcer created [Upgrade shiki syntax highlighter](https://github.com/nushell/nushell.github.io/pull/1233)
- mmastrocinque created [Update custom_completions.md to use new spread operator in carapace example](https://github.com/nushell/nushell.github.io/pull/1232)
- fdncred created [add language guide](https://github.com/nushell/nushell.github.io/pull/1230)
- Blezz-tech created [Add basic config and pages for Russian language](https://github.com/nushell/nushell.github.io/pull/1228)

## reedline

- crides created [revert overdeleted `c-a` binding from #715](https://github.com/nushell/reedline/pull/734)
- nibon7 created [Fix quick completion](https://github.com/nushell/reedline/pull/732)
- maxomatic458 created [add builder functions](https://github.com/nushell/reedline/pull/731), and [Typed text style](https://github.com/nushell/reedline/pull/730), and [menu refactor](https://github.com/nushell/reedline/pull/723)
- ysthakur created [Print foreground color for indicator and right prompt in large buffers](https://github.com/nushell/reedline/pull/728)
