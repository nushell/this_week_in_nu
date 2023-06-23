# This week in Nushell #200


## Nushell

- fdncred [cleaned up config by removing legacy options](https://github.com/nushell/nushell/pull/9496), and [made history.max_size bigger](https://github.com/nushell/nushell/pull/9494)
- sholderbach [moved the nightly issue template to a hidden place](https://github.com/nushell/nushell/pull/9495), and [Revert #8395 "Treat empty pipelines as pass-through"](https://github.com/nushell/nushell/pull/9472), and [Remove "Progress" section from README](https://github.com/nushell/nushell/pull/9471), and [Mention `clap_complete_nushell` in the officially supported section](https://github.com/nushell/nushell/pull/9468), and [Remove duplicated feature in `nu-cmd-dataframe` dep](https://github.com/nushell/nushell/pull/9461)
- hustcer [added Nushell language detection for linguist](https://github.com/nushell/nushell/pull/9491)
- nibon7 [bumped openssl to 0.10.55](https://github.com/nushell/nushell/pull/9488), and [Apply nightly clippy fixes](https://github.com/nushell/nushell/pull/9482)
- jntrnr [split $nu variable into scope commands and simpler $nu](https://github.com/nushell/nushell/pull/9487), and [revert: move to ahash](https://github.com/nushell/nushell/pull/9464), and [Treat empty pipelines as pass-through](https://github.com/nushell/nushell/pull/8395)
- zhiburt [fixed indexing issue for `table --expand`](https://github.com/nushell/nushell/pull/9484)
- stormasm [updated Contributing.md stating we can not accept PRs that are GPL](https://github.com/nushell/nushell/pull/9483)
- amtoine [made *dots* tests easier to read](https://github.com/nushell/nushell/pull/9467), and [move common tools from `nu-command` to `nu-cmd-base`](https://github.com/nushell/nushell/pull/9455), and [use `create_default_context` from `nu-cmd-lang`](https://github.com/nushell/nushell/pull/9454), and [toolkit: use `--features` instead of `--dataframe` and refactor a bit](https://github.com/nushell/nushell/pull/9425)
- FilipAndersson245 [removed some permutations of benchmarks for plugin encoding/decoding.](https://github.com/nushell/nushell/pull/9465)
- Sygmei [fixed input/suppress output on windows](https://github.com/nushell/nushell/pull/9459)
- michaeljohnalbers [fixed missing file names from rm errors](https://github.com/nushell/nushell/pull/9120)
- ahkrr [fixed 3 or more dots in file paths](https://github.com/nushell/nushell/pull/8544)

## Extension

- gaetschwartz created [fix go to definition on windows](https://github.com/nushell/vscode-nushell-lang/pull/141)
- glcraft created [Fix datetime parsing](https://github.com/nushell/vscode-nushell-lang/pull/140), and [Fix TextMate regex](https://github.com/nushell/vscode-nushell-lang/pull/137)

## Documentation

- hustcer created [Add Nushell Language detect for linguist](https://github.com/nushell/nushell.github.io/pull/955)
- EmilySeville7cfg created [fix(contributor-book): named args example](https://github.com/nushell/nushell.github.io/pull/954)

## Nu_Scripts

- ShinyZero0 created [complete manpages](https://github.com/nushell/nu_scripts/pull/534)
- stormasm created [add the new crate nu-cmd-base to the release](https://github.com/nushell/nu_scripts/pull/533)
- hustcer created [Add Nushell Language detect for linguist](https://github.com/nushell/nu_scripts/pull/532)
- jacobono created [`export env` is not in nushell](https://github.com/nushell/nu_scripts/pull/529)
- hyiltiz created [Convenience wrapper for venv creation](https://github.com/nushell/nu_scripts/pull/514)
