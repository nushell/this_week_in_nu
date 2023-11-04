# This week in Nushell #219


## Nushell

- schrieveslaach [implemented an early version of an integrated LSP Server](https://github.com/nushell/nushell/pull/10723)
- fdncred [removed unwraps in registry_query command](https://github.com/nushell/nushell/pull/10936), [allowed `compact` to also compact empty strings](https://github.com/nushell/nushell/pull/10912), and [allowed `sort-by` to work with records](https://github.com/nushell/nushell/pull/10870)
- KAAtheWiseGit [refactored `error make`](https://github.com/nushell/nushell/pull/10923), [changed `input list` to return null](https://github.com/nushell/nushell/pull/10913), [changed the category of scope commands to core](https://github.com/nushell/nushell/pull/10892), and [added a `umkdir` command that uses uutils](https://github.com/nushell/nushell/pull/10785)
- stfacc [added "shape_keyword" to default config](https://github.com/nushell/nushell/pull/10922)
- sholderbach [refactored to use new Record APIs in `nu-protocol`/`nu-engine`](https://github.com/nushell/nushell/pull/10917), [converted "pure" macros to pure fn in `config.rs`](https://github.com/nushell/nushell/pull/10893), [added `Record::remove`/`retain`/`retain_mut`](https://github.com/nushell/nushell/pull/10876), and [disallowed duplicated columns in table literals](https://github.com/nushell/nushell/pull/10875)
- IanManske [reduced element shifting in `Record::retain_mut`](https://github.com/nushell/nushell/pull/10915), [made `FromValue` take owned `Value`s](https://github.com/nushell/nushell/pull/10900), and [reused `Closure` type in `Value::Closure`](https://github.com/nushell/nushell/pull/10894)
- lavafroth implemented a few fixes for completions: [1](https://github.com/nushell/nushell/pull/10898), [2](https://github.com/nushell/nushell/pull/10831)
- WindSoilder [introduced a `gen_save_call` function to reduce duplicate code](https://github.com/nushell/nushell/pull/10852)

## Documentation

- stfacc created [Add instructions to change default shell for GNOME Console](https://github.com/nushell/nushell.github.io/pull/1134)
- amtoine created [put Starship integration forward in prompt chapter](https://github.com/nushell/nushell.github.io/pull/1131)

## Nu_Scripts

- fnuttens created [Fix git hard reset to origin branch alias (groh)](https://github.com/nushell/nu_scripts/pull/654)
- amtoine created [update the `nu-themes` readme](https://github.com/nushell/nu_scripts/pull/652)

## reedline

- sunfishcode created [Avoid consuming CPU when waiting for input.](https://github.com/nushell/reedline/pull/651)
- stfacc created [Split hinter tokens at Unicode word boundaries](https://github.com/nushell/reedline/pull/650)
