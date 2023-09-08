# This week in Nushell #211


## Nushell

- fdncred [added more `ps` columns in Windows](https://github.com/nushell/nushell/pull/10275), and [changed the right prompt to respect a users locale](https://github.com/nushell/nushell/pull/10273), and [updated format date when using %x %X %r](https://github.com/nushell/nushell/pull/10272), and [allowed `--login` to be used with nu's `--commands` parameter](https://github.com/nushell/nushell/pull/10253), and [restored NU_LIB_DIRS and NU_PLUGIN_DIRS defaults](https://github.com/nushell/nushell/pull/10252), and [added plugin path when there are no signatures](https://github.com/nushell/nushell/pull/10201)
- dmatos2012 [started using uutils/coreutils cp command in place of nushell's cp command](https://github.com/nushell/nushell/pull/10097)
- jntrnr [moved Value to helpers, separate span call](https://github.com/nushell/nushell/pull/10121)
- sholderbach [moved spellcheck config into `.github` folder](https://github.com/nushell/nushell/pull/10267), and [removed codecov.io setup](https://github.com/nushell/nushell/pull/10266), and [documented that `open` looks up `from` subcommands](https://github.com/nushell/nushell/pull/10255), and [tweaked the contributor image to include more users](https://github.com/nushell/nushell/pull/10238), and [updated `crossterm`/`ratatui`/dev-`reedline`](https://github.com/nushell/nushell/pull/10137)
- IanManske made sure we [restore initial foreground process group on exit](https://github.com/nushell/nushell/pull/10021)
- brunerm99 [added search terms for use, while, and range (#5093)](https://github.com/nushell/nushell/pull/10265)
- balupton updated the readme to [add dorothy to supported by](https://github.com/nushell/nushell/pull/10262)
- stormasm [changed LOG_FORMAT to NU_LOG_FORMAT in nu-std library](https://github.com/nushell/nushell/pull/10254)
- zhiburt [made some UI improvements to `explore`](https://github.com/nushell/nushell/pull/10247)
- rgwood started tidying up `explore` in preparation for bigger changes: [1](https://github.com/nushell/nushell/pull/10270), [2](https://github.com/nushell/nushell/pull/10259), [3](https://github.com/nushell/nushell/pull/10258), [4](https://github.com/nushell/nushell/pull/10257)
- amtoine [fixed default after an empty where](https://github.com/nushell/nushell/pull/10240), and [added support for tab completion cycling](https://github.com/nushell/nushell/pull/10199), and [renamed the types with spaces in them to use `-`](https://github.com/nushell/nushell/pull/9929), and [moved math constants to standard library](https://github.com/nushell/nushell/pull/9678)
- WindSoilder made a change to [return an error when user break sleep by ctrl-c](https://github.com/nushell/nushell/pull/10234)
- nanoqsh [made `append`/`prepend` consistent for ranges](https://github.com/nushell/nushell/pull/10231)
- dead10ck [cleaned up trash support on Android](https://github.com/nushell/nushell/pull/10225), and [fixed unit tests on Android](https://github.com/nushell/nushell/pull/10224), and [upgrade nix to 0.27](https://github.com/nushell/nushell/pull/10223)
- ofek [fixed example history command pipeline](https://github.com/nushell/nushell/pull/10220)
- nibon7 [auto-formatted let-else blocks](https://github.com/nushell/nushell/pull/10214), and [fixed panics when encountering parsing errors](https://github.com/nushell/nushell/pull/10213)
- horasal [allowed operators in constants](https://github.com/nushell/nushell/pull/10212), and [treat path contains '?' as pattern](https://github.com/nushell/nushell/pull/10142), and [prevent crash when use redirection with let/mut](https://github.com/nushell/nushell/pull/10139)
- alsuren [updated keybindings help to point to the book's reedline chapter](https://github.com/nushell/nushell/pull/10193)
- MasterMach50 [changed default env file to use $nu.home_path to find home](https://github.com/nushell/nushell/pull/10192)
- utouto97 [refactored the input command](https://github.com/nushell/nushell/pull/10150)

## Extension

- adamcstephens created [fix shebang/firstLine detection](https://github.com/nushell/vscode-nushell-lang/pull/151)

## Documentation

- JoaquinTrinanes created [Simplify external completer](https://github.com/nushell/nushell.github.io/pull/1049)
- sholderbach created [Document that `open` looks up `from`s in scope](https://github.com/nushell/nushell.github.io/pull/1048)
- stormasm created [add a link to the contributor book at the end of the plugins chapter](https://github.com/nushell/nushell.github.io/pull/1045)
- alsuren created [Point out where command docs should be edited](https://github.com/nushell/nushell.github.io/pull/1042)

## Nu_Scripts

- amtoine created [add the `random-bytes` benchmark](https://github.com/nushell/nu_scripts/pull/595)
- selfagency created [Add support for fnm](https://github.com/nushell/nu_scripts/pull/593)
- fnuttens created [Replace exa by eza aliases](https://github.com/nushell/nu_scripts/pull/591)
