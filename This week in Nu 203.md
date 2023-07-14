# This week in Nushell #203


## Nushell

- jt [changed input/output types in help to a table](https://github.com/nushell/nushell/pull/9686), and [Input output checking](https://github.com/nushell/nushell/pull/9680), and [Remove broken compile-time overload system](https://github.com/nushell/nushell/pull/9677), and [allow mut to take pipelines](https://github.com/nushell/nushell/pull/9658)
- fdncred [added more input_output_types found from breaking scripts](https://github.com/nushell/nushell/pull/9683), and [add kind and state to other key presses](https://github.com/nushell/nushell/pull/9669)
- IanManske [fixed SIGTTIN handling](https://github.com/nushell/nushell/pull/9681)
- kubouch [fixed broken constants in scopes](https://github.com/nushell/nushell/pull/9679)
- stormasm [removed warning: unused import pipeline](https://github.com/nushell/nushell/pull/9675), and [cratification: part III of the math commands to nu-cmd-extra](https://github.com/nushell/nushell/pull/9674), and [cratification: part II of the math commands to nu-cmd-extra](https://github.com/nushell/nushell/pull/9657), and [cratification: start moving over the math commands to nu-cmd-extra](https://github.com/nushell/nushell/pull/9647)
- amtoine [simplified the test for `let` core command](https://github.com/nushell/nushell/pull/9671), and [fix the `std` test commands calls in dev documents](https://github.com/nushell/nushell/pull/9535)
- sholderbach created [Use `is-terminal` crate for now](https://github.com/nushell/nushell/pull/9670), and [Bump deps to transitively use hashbrown 0.14](https://github.com/nushell/nushell/pull/9668), and [Apply nightly clippy lints](https://github.com/nushell/nushell/pull/9654), and [Update reedline dev version lock](https://github.com/nushell/nushell/pull/9644), and [Bump `indexmap` to 2.0](https://github.com/nushell/nushell/pull/9643), and [Remove duplicated dependency on `ansi-str 0.7`](https://github.com/nushell/nushell/pull/9641)
- zhiburt created [nu-explore/ Add handlers for HOME/END keys](https://github.com/nushell/nushell/pull/9666)
- mengsuenyan [fixed the command `cp -u src dst`/`mv -u src dst` doesn't work when the…](https://github.com/nushell/nushell/pull/9662)
- WindSoilder [supported env assignment and mutable variable assignment with `if` block and `match` guard](https://github.com/nushell/nushell/pull/9650)
- hanjunghyuk [removed unnecessary `cwd`, `pipeline()`, `r#` from various tests](https://github.com/nushell/nushell/pull/9645)
- dependabot[bot] created [Bump libproc from 0.13.0 to 0.14.0](https://github.com/nushell/nushell/pull/9640), and [Bump strum from 0.24.1 to 0.25.0](https://github.com/nushell/nushell/pull/9639), and [Bump scraper from 0.16.0 to 0.17.1](https://github.com/nushell/nushell/pull/9638)

## Extension

- fdncred created [forgot to merge changes for 1.60](https://github.com/nushell/vscode-nushell-lang/pull/145)

## Documentation

- fachammer created [Fix link](https://github.com/nushell/nushell.github.io/pull/981), and [Fix typo](https://github.com/nushell/nushell.github.io/pull/980), and [Fix typo](https://github.com/nushell/nushell.github.io/pull/979)
- hustcer created [Use lefthook instead of husky and lint-staged for git hooks](https://github.com/nushell/nushell.github.io/pull/978)

## Nu_Scripts

- fdncred created [fix error background color in oh-my.nu script](https://github.com/nushell/nu_scripts/pull/551)
- maxim-uvarov created [conda fix](https://github.com/nushell/nu_scripts/pull/547)

## reedline

- NotLebedev created [Replace crossterm ScrollUp with universal workaround](https://github.com/nushell/reedline/pull/601)
- sholderbach created [Update (dev-)deps strum/pretty-assertions,rstest](https://github.com/nushell/reedline/pull/600)
