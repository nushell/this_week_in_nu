# This week in Nushell #212


## Nushell

- amtoine [fixed the pretty printing of failing tests in std](https://github.com/nushell/nushell/pull/10373), and [added a `std repeat` command to replace `"foo" * 3`](https://github.com/nushell/nushell/pull/10339), and [added a case-insensitive example to `where`](https://github.com/nushell/nushell/pull/10299), and [allowed `into duration` to take an integer amount of ns](https://github.com/nushell/nushell/pull/10286)
- zhiburt made several fixes to table rendering: [1](https://github.com/nushell/nushell/pull/10367), [2](https://github.com/nushell/nushell/pull/10357), [3](https://github.com/nushell/nushell/pull/10351)
- jntrnr [fixed 'let' to properly redirect](https://github.com/nushell/nushell/pull/10360), and [changed `echo` to print when not redirected](https://github.com/nushell/nushell/pull/10338), and [removed profiling from nushell's hot loop](https://github.com/nushell/nushell/pull/10325)
- GomesGoncalo [made a fix to allow json requests of value type list](https://github.com/nushell/nushell/pull/10356)
- fdncred [added a helper switch to move cursor to end of buffer](https://github.com/nushell/nushell/pull/10354), and [added a few more columns to linux `ps -l` output](https://github.com/nushell/nushell/pull/10344), and [silenced some ucp warnings](https://github.com/nushell/nushell/pull/10294), and [allowed update to use metadata](https://github.com/nushell/nushell/pull/10264)
- sholderbach [optimized the use of range in `std repeat`](https://github.com/nushell/nushell/pull/10353), and [updated internal use of `decimal` to `float`](https://github.com/nushell/nushell/pull/10333), and [made a change to use slices directly instead of `&Vec`](https://github.com/nushell/nushell/pull/10328), and [deref `&String` arguments to `&str` where appropriate](https://github.com/nushell/nushell/pull/10321), and [renamed `random decimal` to `random float`](https://github.com/nushell/nushell/pull/10320), and [inverted `&Option`s to `Option<&T>`](https://github.com/nushell/nushell/pull/10315), and [bumped `calamine`](https://github.com/nushell/nushell/pull/10314), and [updated `crates-ci/typos` and fixed new typos](https://github.com/nushell/nushell/pull/10313), and [removed python-like string multiplication](https://github.com/nushell/nushell/pull/10293), and [removed pythonic `int * list` behavior](https://github.com/nushell/nushell/pull/10292), and [renamed `into decimal` to `into float`](https://github.com/nushell/nushell/pull/9979)
- Tiggax [removed `select` error if same row/column is provided](https://github.com/nushell/nushell/pull/10350), and [updated `reject` to be able to recive arg list](https://github.com/nushell/nushell/pull/10216), and [updated `reject` to support multiple row args](https://github.com/nushell/nushell/pull/10163)
- WindSoilder [updated `ps` to add `cwd` column on linux and macos](https://github.com/nushell/nushell/pull/10347)
- hustcer [updated Nu to v0.84 for release and nightly-build](https://github.com/nushell/nushell/pull/10334), and [upgraded softprops/action-gh-release to v0.1.15 for release and nightly build workflow](https://github.com/nushell/nushell/pull/10331)
- kubouch [allowed parse-time evaluation of `if`](https://github.com/nushell/nushell/pull/10326), and [removed leftover const eval file](https://github.com/nushell/nushell/pull/10324)
- dmatos2012 [fixed variables not allowed in ucp](https://github.com/nushell/nushell/pull/10304)
- geniusisme [made a change to provide env to commands and try to start provided path](https://github.com/nushell/nushell/pull/10302)
- dzorya [added a comment that perl is required for feature static-link-openssl…](https://github.com/nushell/nushell/pull/10291)
- nibon7 [made cursor_shape optional](https://github.com/nushell/nushell/pull/10289)
- alsuren [signposted 'input list --types [key]' from 'keybindings list'](https://github.com/nushell/nushell/pull/10287)
- utouto97 [added 'from ndjson' into standard library](https://github.com/nushell/nushell/pull/10283)
- IanManske [fixed `rm` on macOS](https://github.com/nushell/nushell/pull/10282)
- nanoqsh [made a change to keep order for `par-each`](https://github.com/nushell/nushell/pull/10249)
- J-Kappes [fixed input --until-bytes: now stops at any of given bytes](https://github.com/nushell/nushell/pull/10235)

## Documentation

- edhowland created [Changed Python plugin example to be more portable](https://github.com/nushell/nushell.github.io/pull/1060)
- Gryff created [Change direnv example to upload $env.PATH as a list](https://github.com/nushell/nushell.github.io/pull/1058)
- dnsem created [Support for standard input in script with shebang](https://github.com/nushell/nushell.github.io/pull/1057)
- petrisch created [DE translation for custom_completions.md](https://github.com/nushell/nushell.github.io/pull/1056), and [Typos in custom_completions](https://github.com/nushell/nushell.github.io/pull/1052)
- mb21 created [Cookbook setup: fix command to append to PATH](https://github.com/nushell/nushell.github.io/pull/1055)
- connorjs created [Update variables_and_subexpressions.md - remove obsolete section](https://github.com/nushell/nushell.github.io/pull/1054), and [Update working_with_lists.md - format date](https://github.com/nushell/nushell.github.io/pull/1053)
- JoaquinTrinanes created [Fix external completers typo](https://github.com/nushell/nushell.github.io/pull/1051)
- hustcer created [Update min required node version and some node modules](https://github.com/nushell/nushell.github.io/pull/1050)

## Nu_Scripts

- WindSoilder created [Improve background job.nu](https://github.com/nushell/nu_scripts/pull/607), and [use closure instead of block](https://github.com/nushell/nu_scripts/pull/602)
- brunerm99 created [Change nu_conda list to output active status of environment as well (#604)](https://github.com/nushell/nu_scripts/pull/605)
- Zinvoke created [FEATURE: add `catppuccin-mocha` theme](https://github.com/nushell/nu_scripts/pull/601)
- amtoine created [add a `typeof` command](https://github.com/nushell/nu_scripts/pull/597), and [add `$.type` to `package.nuon`](https://github.com/nushell/nu_scripts/pull/582)
- icp1994 created [feat(hook): add `rusty-paths.nu`](https://github.com/nushell/nu_scripts/pull/596)

## reedline

- sholderbach created [Remove old `actions-rs/cargo`](https://github.com/nushell/reedline/pull/637), and [Add a configuration to codecov.io](https://github.com/nushell/reedline/pull/636), and [Setup coverage with codecov.io](https://github.com/nushell/reedline/pull/635)
- Hofer-Julian created [Minor improvements](https://github.com/nushell/reedline/pull/633)
- ysthakur created [Let prompts choose to repaint on enter](https://github.com/nushell/reedline/pull/627)
