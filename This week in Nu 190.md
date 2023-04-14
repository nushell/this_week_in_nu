# This week in Nushell #190


## Nushell

- 1Kinoti [used `let-else` syntax where possible](https://github.com/nushell/nushell/pull/8886)
- jt [improved hovers, including for custom commands](https://github.com/nushell/nushell/pull/8881), and [Make -I take in a ;-delimited list](https://github.com/nushell/nushell/pull/8864), and [Adds multi-file support to IDE support](https://github.com/nushell/nushell/pull/8857), and [Relax the closure syntax, highlight differently](https://github.com/nushell/nushell/pull/8846), and [Revert numberlike parsing restriction](https://github.com/nushell/nushell/pull/8845), and [Add option to not load std-lib. Default tests to not use std-lib](https://github.com/nushell/nushell/pull/8833), and [Only add the std lib files once](https://github.com/nushell/nushell/pull/8830)
- presidento created [std: remove logging example](https://github.com/nushell/nushell/pull/8877), and [Move unit test runner to standard library](https://github.com/nushell/nushell/pull/8850), and [stdlib test runner: implement `setup` and `teardown` commands to unit tests](https://github.com/nushell/nushell/pull/8776)
- sholderbach created [Run coverage immediately](https://github.com/nushell/nushell/pull/8876), and [Reenable CI coverage](https://github.com/nushell/nushell/pull/8867), and [Fix span of multibyte short flags](https://github.com/nushell/nushell/pull/8866), and [Move CLI related commands to `nu-cli`](https://github.com/nushell/nushell/pull/8832), and [Follow up #8758 with a style fix](https://github.com/nushell/nushell/pull/8822)
- fdncred [limited the ide-check error amount](https://github.com/nushell/nushell/pull/8875), and [change include dirs separator to colon](https://github.com/nushell/nushell/pull/8873)
- WindSoilder created [`rm`: enable trash flag on android and ios platrofm](https://github.com/nushell/nushell/pull/8871), and [optimize hash md5 for binary input](https://github.com/nushell/nushell/pull/8860), and [Remove autoprinting of `for` loop](https://github.com/nushell/nushell/pull/8843)
- vaishaag [corrected error description for unknown external commands](https://github.com/nushell/nushell/pull/8868)
- pingiun [added $env.CURRENT_FILE variable](https://github.com/nushell/nushell/pull/8861)
- amtoine created [FEATURE: do not use theme-independant colors in the default configs](https://github.com/nushell/nushell/pull/8855), and [stdlib: make helper modules available in std](https://github.com/nushell/nushell/pull/8841), and [stdlib: refactor into a multi-module library](https://github.com/nushell/nushell/pull/8815), and [stdlib: add completion to `help` commands](https://github.com/nushell/nushell/pull/8799), and [DEV: make all "comments" real md comments in the PR template](https://github.com/nushell/nushell/pull/8708)
- federicoviscomi created [Parser panic for signature with multibyte char for short flag #8821](https://github.com/nushell/nushell/pull/8849)
- nibon7 [fixed process_range on 32-bit platforms](https://github.com/nushell/nushell/pull/8842)
- hustcer [upgraded to nu v0.78 for binaries release workflow](https://github.com/nushell/nushell/pull/8840)
- dependabot [bumped sys-locale from 0.2.4 to 0.3.0](https://github.com/nushell/nushell/pull/8838), and [Bump winreg from 0.11.0 to 0.50.0](https://github.com/nushell/nushell/pull/8837), and [Bump rstest from 0.16.0 to 0.17.0](https://github.com/nushell/nushell/pull/8836), and [Bump umask from 2.0.0 to 2.1.0](https://github.com/nushell/nushell/pull/8835)
- MariaSolOs [added git hooks for formatting and running `clippy`](https://github.com/nushell/nushell/pull/8820)
- bobhy [picked up fix in dtparse for nanosec truncation noted at bottom of #8337](https://github.com/nushell/nushell/pull/8805)

## Extension

- fdncred created [update vscode launch json so we can see debug messages from client](https://github.com/nushell/vscode-nushell-lang/pull/103), and [update files to model after jakt](https://github.com/nushell/vscode-nushell-lang/pull/101), and [limit the amount of errors returned by ide-check](https://github.com/nushell/vscode-nushell-lang/pull/98), and [respect the setting to enable or disable hints/inlays](https://github.com/nushell/vscode-nushell-lang/pull/97), and [change include dir separator from semicolon to colon](https://github.com/nushell/vscode-nushell-lang/pull/96), and [revert vscodeignore changes](https://github.com/nushell/vscode-nushell-lang/pull/95), and [add include dirs setting to extension](https://github.com/nushell/vscode-nushell-lang/pull/94), and [utilize nushell IDE features with built-in vscode LSP functionality](https://github.com/nushell/vscode-nushell-lang/pull/89)
- jt created [Have launch build instead of watch](https://github.com/nushell/vscode-nushell-lang/pull/102), and [Delete tmp file on exit](https://github.com/nushell/vscode-nushell-lang/pull/100), and [Limit buffer calculation to buffer size not text size](https://github.com/nushell/vscode-nushell-lang/pull/99), and [Move runCompiler to be in charge of the script include flag](https://github.com/nushell/vscode-nushell-lang/pull/93), and [Add support for -I call to nushell](https://github.com/nushell/vscode-nushell-lang/pull/92)

## Documentation

- hustcer created [Fix i18n script for nu v0.78](https://github.com/nushell/nushell.github.io/pull/867)
- SamirTalwar created [Update the Direnv recipe to use a block, rather than `code:`](https://github.com/nushell/nushell.github.io/pull/852)

## Nu_Scripts

- Hofer-Julian created [conda: Add `||` to closure](https://github.com/nushell/nu_scripts/pull/447), and [Speeding up activating conda environment](https://github.com/nushell/nu_scripts/pull/442)
- fnuttens created [Add --all aliases for exa](https://github.com/nushell/nu_scripts/pull/446)
- fdncred created [move assets so they're more accessible](https://github.com/nushell/nu_scripts/pull/445), and [a little cleanup](https://github.com/nushell/nu_scripts/pull/444)
- Kissaki created [Fix winget-completions.nu for nushell v0.78 closure syntax change](https://github.com/nushell/nu_scripts/pull/443)

## reedline

- WindSoilder created [Update crossterm to version 0.26.1](https://github.com/nushell/reedline/pull/560)
