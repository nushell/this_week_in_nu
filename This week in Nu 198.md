# This week in Nushell #198


## Nushell

- hustcer [trid to add a nightly-build workflow](https://github.com/nushell/nushell/pull/9385)
- sholderbach [applied nightly clippy fixes](https://github.com/nushell/nushell/pull/9381), and [Bump to 0.81.1 as development version](https://github.com/nushell/nushell/pull/9379), and [Fix internal module reexports](https://github.com/nushell/nushell/pull/9378), and [Pin `reedline` to 0.20.0 release](https://github.com/nushell/nushell/pull/9370)
- jt [removed arm v7, which also is broken](https://github.com/nushell/nushell/pull/9376), and [remove more of the risc release](https://github.com/nushell/nushell/pull/9375), and [bump to 0.81](https://github.com/nushell/nushell/pull/9374)
- nibon7 [fixed typos](https://github.com/nushell/nushell/pull/9372)
- WindSoilder [added `http options` command](https://github.com/nushell/nushell/pull/9365)
- dependabot[bot] created [Bump criterion from 0.4.0 to 0.5.1](https://github.com/nushell/nushell/pull/9361), and [Bump serial_test from 1.0.0 to 2.0.0](https://github.com/nushell/nushell/pull/9358)
- gdhuper [added a check for empty params for `url join`](https://github.com/nushell/nushell/pull/9356)
- kubouch [fixed config creation during printing](https://github.com/nushell/nushell/pull/9353)
- skelly37 created [Logger constants refactored, `format` argument added, better formatting of failed (non) equality assertions](https://github.com/nushell/nushell/pull/9315)

## Extension

- gaetschwartz created [Use unique labels for `durationLogWrapper`](https://github.com/nushell/vscode-nushell-lang/pull/133)

## Documentation

- hustcer created [Refresh command docs for Nu v0.81.0](https://github.com/nushell/nushell.github.io/pull/944)
- Omochice created [Fix missing `|`](https://github.com/nushell/nushell.github.io/pull/942)
- dependabot[bot] created [Bump vite from 4.0.4 to 4.0.5](https://github.com/nushell/nushell.github.io/pull/940)
- amtoine created [Release notes for `0.81`](https://github.com/nushell/nushell.github.io/pull/916)

## Nu_Scripts

- fj0r created [parse name of positional args in `parse cmd`](https://github.com/nushell/nu_scripts/pull/527), and [kubernetes: fix `-n` in completion context](https://github.com/nushell/nu_scripts/pull/523), and [more precise parsing of cmd through the information in `nu.scope.comm…](https://github.com/nushell/nu_scripts/pull/522)
- amtoine created [add a "command not found" hook](https://github.com/nushell/nu_scripts/pull/526), and [REFACTOR: rewrite the release note scripts](https://github.com/nushell/nu_scripts/pull/525), and [fix the `std log` import in `make_release/create-website-release-note-pr`](https://github.com/nushell/nu_scripts/pull/524)

## reedline

- fdncred created [update .typos.toml for bui](https://github.com/nushell/reedline/pull/593)
- WindSoilder created [add a new disable_bracketed_paste method](https://github.com/nushell/reedline/pull/592)
- sholderbach created [Revert removal of patch versions](https://github.com/nushell/reedline/pull/590), and [Bump to `0.20.0` for release](https://github.com/nushell/reedline/pull/581)
