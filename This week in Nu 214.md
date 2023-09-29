# This week in Nushell #214

## Nushell

- sholderbach [renamed `SyntaxShape::Custom` to `CompleterWrapper`](https://github.com/nushell/nushell/pull/10548), and [Docstring some intricacies around `SyntaxShape`](https://github.com/nushell/nushell/pull/10544), and [Fix editor config for reedline and `config nu/env`](https://github.com/nushell/nushell/pull/10535), and [Rename `random integer` to `random int`](https://github.com/nushell/nushell/pull/10520), and [Remove parsing literals of unrepresentable `SyntaxShape`s](https://github.com/nushell/nushell/pull/10512), and [Remove unused `SyntaxShape::Variable`](https://github.com/nushell/nushell/pull/10511), and [Bump `dialoguer` to `0.11.0`](https://github.com/nushell/nushell/pull/10510)
- Abdillah [added kitty protocol config to nushell](https://github.com/nushell/nushell/pull/10540)
- fennewald [fixed Default Prompt Tilde Insertion Logic](https://github.com/nushell/nushell/pull/10539)
- amtoine created [break the definition of LS_COLORS onto multiple lines](https://github.com/nushell/nushell/pull/10538), and [remove the `$nothing` variable](https://github.com/nushell/nushell/pull/10478), and [show the full directory / file path in "directory not found" error](https://github.com/nushell/nushell/pull/10430)
- rgwood created [`explore`: highlight selected cell using background colour instead of cursor](https://github.com/nushell/nushell/pull/10533)
- 1256-bits [changed LS_COLORS to highlight .fb2 files as text documents](https://github.com/nushell/nushell/pull/10532)
- bobhy created [ `toolkit check pr` does same clippy checks as  github CI](https://github.com/nushell/nushell/pull/10528), and [glob with ../ prefix now works;](https://github.com/nushell/nushell/pull/10504), and [std dt datetime-diff: fix uninitialized field ref when borrowing](https://github.com/nushell/nushell/pull/10466)
- WindSoilder [allowed early return outside of main](https://github.com/nushell/nushell/pull/10514), and [make better error message for `not` operator](https://github.com/nushell/nushell/pull/10507)
- hustcer [improved release script for github release workflow](https://github.com/nushell/nushell/pull/10502), and [Update winget submission workflow include only default msi files](https://github.com/nushell/nushell/pull/10487), and [feat: Update nightly build workflow add full release support](https://github.com/nushell/nushell/pull/10485)
- dependabot[bot] created [Bump rayon from 1.7.0 to 1.8.0](https://github.com/nushell/nushell/pull/10497), and [Bump crate-ci/typos from 1.16.11 to 1.16.13](https://github.com/nushell/nushell/pull/10493)
- zhiburt created [nu-table: Fix failing test (relied on termwidth assumptions)](https://github.com/nushell/nushell/pull/10492)
- fdncred created [fix magenta_reverse and friends](https://github.com/nushell/nushell/pull/10491)
- poliorcetics created [Command: Add `config env/nu --default` to print defaults](https://github.com/nushell/nushell/pull/10480)
- NotLebedev [fixed default argument value type checking](https://github.com/nushell/nushell/pull/10460), and [Allow complex types in input/output and let](https://github.com/nushell/nushell/pull/10405)
- poketch [made `open` case-insensitive to file extensions](https://github.com/nushell/nushell/pull/10451)
- fnuttens [added support for HTTP proxy in network commands](https://github.com/nushell/nushell/pull/10401)
- ZerdoX-x created [Completions: add support for doas as for sudo](https://github.com/nushell/nushell/pull/10256)

## Documentation

- sholderbach created [Fix typo](https://github.com/nushell/nushell.github.io/pull/1080)
- hustcer created [Fix code formatting hooks](https://github.com/nushell/nushell.github.io/pull/1079)
- ShalokShalom created [correct typo](https://github.com/nushell/nushell.github.io/pull/1077)
- marcelarie created [Update external_completers.md](https://github.com/nushell/nushell.github.io/pull/1076)
- petrisch created [Align the DE/book structure to the EN original](https://github.com/nushell/nushell.github.io/pull/1075)

## Nu_Scripts

- sholderbach created [Replace use of `$nothing` with `null`](https://github.com/nushell/nu_scripts/pull/621)
- schrieveslaach created [Fix git-completions.nu](https://github.com/nushell/nu_scripts/pull/620)
- 1adept created [Fix: Completions Broken '-s' flag in man-completions](https://github.com/nushell/nu_scripts/pull/619)

## reedline

- sholderbach created [Update motto title](https://github.com/nushell/reedline/pull/640)
- horasal created [Accept `Command` with args for `BufferEditor`](https://github.com/nushell/reedline/pull/630)

- sholderbach created [Update motto title](https://github.com/nushell/reedline/pull/640)
- horasal created [Accept `Command` with args for `BufferEditor`](https://github.com/nushell/reedline/pull/630)
