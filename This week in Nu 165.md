# This week in Nushell #165


## Nushell

- dandavison [improved tab completions](https://github.com/nushell/nushell/pull/6802), and [reduced allocations in the pipeline data loop](https://github.com/nushell/nushell/pull/6790), and [renamed `query dfr` to `query df`](https://github.com/nushell/nushell/pull/6777), and [added a documentation requirement to PR template](https://github.com/nushell/nushell/pull/6749)
- WindSoilder [allowed saving captured stderr to a file](https://github.com/nushell/nushell/pull/6793), and [avoided a freeze when external command generates too much stdout output ](https://github.com/nushell/nushell/pull/6715)
- zhiburt fixed [table paging indexing](https://github.com/nushell/nushell/pull/6850), and [`table -e` align key to 2nd line](https://github.com/nushell/nushell/pull/6842), and [nu-table: Check perf improvements](https://github.com/nushell/nushell/pull/6710)
- hustcer [updated CI workflow actions](https://github.com/nushell/nushell/pull/6841)
- nibon7 [added missing `shape_directory` to default_config.nu](https://github.com/nushell/nushell/pull/6836), and fixed issues in `rm` ([1](https://github.com/nushell/nushell/pull/6815), [2](https://github.com/nushell/nushell/pull/6837))
- rgwood did some [diagnostics logging streamlining+tweaks](https://github.com/nushell/nushell/pull/6834) and [added command help in the `from`+`to` commands](https://github.com/nushell/nushell/pull/6856)
- fdncred [added a filesize_metric comment](https://github.com/nushell/nushell/pull/6760)
- jntrnr [fixed let-env in the startup banner](https://github.com/nushell/nushell/pull/6795)

- sholderbach [pinned Reedline to the 0.13.0 release](https://github.com/nushell/nushell/pull/6789), and [upgraded Reedline to the latest dev version](https://github.com/nushell/nushell/pull/6778)
- JEndler [updated README.md](https://github.com/nushell/nushell/pull/6782)
- valpackett wrote a fix to [tolerate more tty acquisition failures in non-interactive mode](https://github.com/nushell/nushell/pull/6779)
- merelymyself [made the `++` operator append lists](https://github.com/nushell/nushell/pull/6766), and [improved errors of `config nu` and `config env`](https://github.com/nushell/nushell/pull/6730)
- rjfc [added search terms to roll commands](https://github.com/nushell/nushell/pull/6761)
- Dorumin created [window --remainder](https://github.com/nushell/nushell/pull/6738)
- howardjohn created [Delete out.log](https://github.com/nushell/nushell/pull/6731)
- HannahZhuSWE [added search terms to arg dataframe commands](https://github.com/nushell/nushell/pull/6724)
- KyleRAnderson [filtered out empty glob patterns to "glob" command](https://github.com/nushell/nushell/pull/6707)


## Documentation


- jmoore34 [added documentation for completions with descriptions](https://github.com/nushell/nushell.github.io/pull/642)
- zephaniahong [updated working_with_lists.md](https://github.com/nushell/nushell.github.io/pull/638) ([twice](https://github.com/nushell/nushell.github.io/pull/637)), and [working_with_strings.md](https://github.com/nushell/nushell.github.io/pull/636)
- WindSoilder [added a note about subexpressions with external commands](https://github.com/nushell/nushell.github.io/pull/641)
- sholderbach created [release notes for Nu 0.70](https://github.com/nushell/nushell.github.io/pull/614)
- hustcer [refreshed command docs for Nu v0.70](https://github.com/nushell/nushell.github.io/pull/644)


## Nu_Scripts

- dandavison created a new [`sockets` command](https://github.com/nushell/nu_scripts/pull/306)


## reedline

- sholderbach fixed [a completion example in README/lib.rs](https://github.com/nushell/reedline/pull/497), [examples in README based on lib.rs](https://github.com/nushell/reedline/pull/496), and [prepared the 0.13 release](https://github.com/nushell/reedline/pull/495)
- CozyPenguin added a feature to [change cursor shape depending on edit mode](https://github.com/nushell/reedline/pull/494)
- perlindgren [updated examples](https://github.com/nushell/reedline/pull/493)
- nibon7 made a change to [render right prompt on the last line of the left prompt](https://github.com/nushell/reedline/pull/492)
- tailhook [added `Submit` and `SubmitOrNewline` editor events](https://github.com/nushell/reedline/pull/490)

## Nana

- tanishqkancharla created [a `useShortcut()` helper](https://github.com/nushell/nana/pull/72)

