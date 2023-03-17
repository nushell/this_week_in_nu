# This week in Nushell #186


## Nushell


- jt [added rest and glob support to 'open'](https://github.com/nushell/nushell/pull/8506), and [bump to 0.77.2](https://github.com/nushell/nushell/pull/8496), and [parser: Add cell path literal syntax](https://github.com/nushell/nushell/pull/8493), and [parser: Fix panic that happens when you type a single `{`](https://github.com/nushell/nushell/pull/8492), and [Fix CI tests that landed after no-implicit-echo](https://github.com/nushell/nushell/pull/8491), and [Fix parse of def with paren params](https://github.com/nushell/nushell/pull/8490), and [Escape will now escape paths with '=' in them](https://github.com/nushell/nushell/pull/8485), and [Start grouping parsing of values better](https://github.com/nushell/nushell/pull/8470), and [Fix warnings and old names](https://github.com/nushell/nushell/pull/8457)
- amtoine created [standard library: fix the tests for the new closure parsing of `0.77.2`](https://github.com/nushell/nushell/pull/8504), and [REFACTOR: put all the standard library in `std.nu`](https://github.com/nushell/nushell/pull/8489), and [DOC: make the README of the standard library clearer](https://github.com/nushell/nushell/pull/8465)
- dandavison created [Short redirection syntax](https://github.com/nushell/nushell/pull/8503), and [SQL-style join command for Nushell tables](https://github.com/nushell/nushell/pull/8424)
- fdncred [reverted "Allow NU_LIBS_DIR and friends to be const"](https://github.com/nushell/nushell/pull/8501), and [enable error reporting from enable_vt_processing](https://github.com/nushell/nushell/pull/8373)
- NotLebedev [reverted "Hide 7925"](https://github.com/nushell/nushell/pull/8500), and [Disable pipeline echo](https://github.com/nushell/nushell/pull/8292)
- rgwood [added `-i` flag back to `get` and `select`](https://github.com/nushell/nushell/pull/8488), and [Fix ls behaviour when directory is empty](https://github.com/nushell/nushell/pull/8439), and [Optional members in cell paths: Attempt 2](https://github.com/nushell/nushell/pull/8379)
- bgeron created [Exit successfully from `nu --help` for compatibility with halp](https://github.com/nushell/nushell/pull/8478)
- hustcer [fixed docs building error caused by missing end tag](https://github.com/nushell/nushell/pull/8477)
- WindSoilder [reverted "Throw out error if external command in subexpression is failed to run (#8204)"](https://github.com/nushell/nushell/pull/8475), and [make better usage of error value in `catch` block](https://github.com/nushell/nushell/pull/8460), and [Restrict closure expression to be something like `{|| ...}`](https://github.com/nushell/nushell/pull/8290), and [make `else if` generate helpful error when condition have an issue](https://github.com/nushell/nushell/pull/8274)
- lucperkins [added char --list example to char command docs](https://github.com/nushell/nushell/pull/8474)
- presidento [made assert eq, assert ne consistent with ==, != operators](https://github.com/nushell/nushell/pull/8473), and [stdlib: add test discovery, extract test files](https://github.com/nushell/nushell/pull/8443), and [std.nu: Rewrite assert method](https://github.com/nushell/nushell/pull/8405)
- Hofer-Julian created [Fix xml docs](https://github.com/nushell/nushell/pull/8462)
- nicokosi created [docs: Use capital letters for CSV and JSON acronyms](https://github.com/nushell/nushell/pull/8459), and [docs: Add missing space in Filesystem/start's usage](https://github.com/nushell/nushell/pull/8458)
- sholderbach [bumped to `0.77.1` development version](https://github.com/nushell/nushell/pull/8453), and [Pin to `reedline` 0.17](https://github.com/nushell/nushell/pull/8441), and [Pin to `nu-ansi-term` 0.47](https://github.com/nushell/nushell/pull/8440), and [Remove unused `nu-json` from `nu-protocol`](https://github.com/nushell/nushell/pull/8417), and [Bump version to `0.77.0`](https://github.com/nushell/nushell/pull/8410), and [Box `ShellError` in `Value::Error`](https://github.com/nushell/nushell/pull/8375)
- tcoratger [modified reject algorithm for identical elements](https://github.com/nushell/nushell/pull/8446)
- BlacAmDK [fixed SQLite table creation sql](https://github.com/nushell/nushell/pull/8430)
- dependabot[bot] [bumped sqlparser from 0.30.0 to 0.32.0](https://github.com/nushell/nushell/pull/8428), and [Bump open from 3.4.0 to 4.0.0](https://github.com/nushell/nushell/pull/8427), and [Bump mockito from 0.32.5 to 1.0.0](https://github.com/nushell/nushell/pull/8426), and [Bump lru from 0.9.0 to 0.10.0](https://github.com/nushell/nushell/pull/8425), and [Bump nix from 0.25.0 to 0.26.2](https://github.com/nushell/nushell/pull/8129)
- klementievdmitry [Added `help externs` command](https://github.com/nushell/nushell/pull/8403)
- mdeville created [Additional flags for commands `from csv` and `from tsv`](https://github.com/nushell/nushell/pull/8398)
- kubouch [disabled alias recursion](https://github.com/nushell/nushell/pull/8397), and [Add proptest regression](https://github.com/nushell/nushell/pull/8396)
- initinll created [Added fix for bug #8278 to read tag values from YAML files](https://github.com/nushell/nushell/pull/8354)
- StevenDoesStuffs created [Allow NU_LIBS_DIR and friends to be const](https://github.com/nushell/nushell/pull/8310)
- stevenxxiu created [fix: fix `commandline` when called with no arguments](https://github.com/nushell/nushell/pull/8207)

## Extension

- fdncred created [next release won't be a preview](https://github.com/nushell/vscode-nushell-lang/pull/85), and [update language, version, changelog](https://github.com/nushell/vscode-nushell-lang/pull/84)

## Documentation

- hustcer created [Update plugin docs for v0.77](https://github.com/nushell/nushell.github.io/pull/831)
- Hofer-Julian created [Update command docs to 0.77](https://github.com/nushell/nushell.github.io/pull/828)
- kubouch created [Finish release notes](https://github.com/nushell/nushell.github.io/pull/825), and [Add alias note](https://github.com/nushell/nushell.github.io/pull/824)
- NotLebedev created [Add description for #8205 and #8014](https://github.com/nushell/nushell.github.io/pull/821)
- martinetd created [Fix show_banner config item](https://github.com/nushell/nushell.github.io/pull/820)
- rgwood created [Newbie-friendly command reference header](https://github.com/nushell/nushell.github.io/pull/818), and [Release notes for `0.77`](https://github.com/nushell/nushell.github.io/pull/800)
- bergus created [Dashes instead of underscores in command comparisons](https://github.com/nushell/nushell.github.io/pull/816)

## Nu_Scripts

- fdncred created [updated some scripts to support the latest changes in 0.77.1](https://github.com/nushell/nu_scripts/pull/416), and [Revert "conda activate base if env_name not given"](https://github.com/nushell/nu_scripts/pull/408)
- fj0r created [upgrade to nu 0.77](https://github.com/nushell/nu_scripts/pull/413)
- kubouch created [Fix since last release script](https://github.com/nushell/nu_scripts/pull/412)
- sholderbach created [Add `nu-cmd-lang` to `nu_release.nu`](https://github.com/nushell/nu_scripts/pull/411)
- siph created [Replace deprecated `str collect` command](https://github.com/nushell/nu_scripts/pull/410)
- Tiggax created [Updated conda script to default to base if no arg given](https://github.com/nushell/nu_scripts/pull/409)
- Kissaki created [Fix docs typo in job.nu](https://github.com/nushell/nu_scripts/pull/405)
- sgasse created [custom-completions: git: Add `git rebase`](https://github.com/nushell/nu_scripts/pull/404)


## reedline


- jaudiger created [Set MSRV to 1.62.1](https://github.com/nushell/reedline/pull/554)
- ClementNerma created [Make `Event` public to allow implements custom `EditMode`](https://github.com/nushell/reedline/pull/552)
- sholderbach created [Apply clippy lints](https://github.com/nushell/reedline/pull/551), and [Bump version for `0.17.0` release](https://github.com/nushell/reedline/pull/550), and [Update `nu-ansi-term` to 0.47.0](https://github.com/nushell/reedline/pull/549)
- micron-mushroom created [fix: singlebyte char assumption in `parse_selection_char`](https://github.com/nushell/reedline/pull/548)

## Nana
