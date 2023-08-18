# This week in Nushell #208


## Nushell

- fdncred [allowed ints as a cellpath for `select`](https://github.com/nushell/nushell/pull/10048), and [allowed `select` to take a $variable with a list of columns](https://github.com/nushell/nushell/pull/9987)
- kubouch [removed dead code from tests](https://github.com/nushell/nushell/pull/10040), and [sorted entries in `scope` commands; Fix usage of externs](https://github.com/nushell/nushell/pull/10039), and [changed `str replace` to match substring by default](https://github.com/nushell/nushell/pull/10038), and [refactored `scope` commands](https://github.com/nushell/nushell/pull/10023), and [fixed example for `extern-wrapped`](https://github.com/nushell/nushell/pull/10004)
- sitiom [changed the winget releaser job to `ubuntu-latest`](https://github.com/nushell/nushell/pull/10032)
- ineu [made `http -f` display the request headers](https://github.com/nushell/nushell/pull/10022)
- amtoine created [deprecate `--format` and `--list` in `into datetime`](https://github.com/nushell/nushell/pull/10017)
- ayax79 [exposed polars avro support](https://github.com/nushell/nushell/pull/10019), and [Nushell table list columns -> dataframe list columns. Explode / Flatten dataframe support.](https://github.com/nushell/nushell/pull/9951)
- 3lvir4 [removed a potential panic from path join](https://github.com/nushell/nushell/pull/10012)
- zhiburt [fixed padding 0 width issues in nu-table](https://github.com/nushell/nushell/pull/10011)
- meskill [fixed nu-parser to not update plugin.nu file on nu startup](https://github.com/nushell/nushell/pull/10007), and [test: clear parent envs to prevent leakage to tests](https://github.com/nushell/nushell/pull/9976)
- sholderbach [renamed misused "deprecation" to removal](https://github.com/nushell/nushell/pull/10000), and [improved I/O types of `into decimal`(/float)](https://github.com/nushell/nushell/pull/9998), and [Add search terms to `reject`](https://github.com/nushell/nushell/pull/9996)
- rgwood [fixed `watch` not handling all file changes](https://github.com/nushell/nushell/pull/9990)
- nibon7 [fixed a crash when moving the cursor after accepting a suggestion from the help menu](https://github.com/nushell/nushell/pull/9784)

## Extension

- balupton created [readmde: close #148 - link extension page](https://github.com/nushell/vscode-nushell-lang/pull/149)

## Documentation

- conqp created [Update command to list aliases](https://github.com/nushell/nushell.github.io/pull/1006)
- hustcer created [Finish `let-env` removal in Chinese translation](https://github.com/nushell/nushell.github.io/pull/1005)
- sholderbach created [Finish `let-env` removal in German translation](https://github.com/nushell/nushell.github.io/pull/1004)
- BrewingWeasel created [Remove unused empty column](https://github.com/nushell/nushell.github.io/pull/1003)
- amtoine created [remove last mentions to `let-env`](https://github.com/nushell/nushell.github.io/pull/999)

## Nu_Scripts

- fdncred created [update prompts scripts with new `str replace` syntax](https://github.com/nushell/nu_scripts/pull/579)
- EmilySeville7cfg created [Simple json schema generator](https://github.com/nushell/nu_scripts/pull/577)
- Neur1n created [minor changes to nu_conda.nu and nu_msvs.nu](https://github.com/nushell/nu_scripts/pull/576)
- WindSoilder created [Update python-venv.nu so we can enter subdirectory without an error](https://github.com/nushell/nu_scripts/pull/574)
