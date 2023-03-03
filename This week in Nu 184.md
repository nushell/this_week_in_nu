# This week in Nushell #184


## Nushell


- jaudiger created [Shadow rs dep](https://github.com/nushell/nushell/pull/8298), and [Uniformize usage() and extra_usage() message ending for commands helper.](https://github.com/nushell/nushell/pull/8268), and [Add unit tests for HTTP commands.](https://github.com/nushell/nushell/pull/8267), and [Fix insecure + max-time arguments for HTTP commands.](https://github.com/nushell/nushell/pull/8266)
- 1Kinoti [fixed `NotAConstant` error help message](https://github.com/nushell/nushell/pull/8293), and [fix: allow subtraction of durations from dates](https://github.com/nushell/nushell/pull/8247)
- rgwood [used `for` instead of `each` in register-plugins.nu](https://github.com/nushell/nushell/pull/8284), and [Fix CPU frequency in `sys` output](https://github.com/nushell/nushell/pull/8275), and [Switch http to https in banner](https://github.com/nushell/nushell/pull/8272), and [Simplify `str trim` command](https://github.com/nushell/nushell/pull/8205)
- stormasm [removed left over build.rs from nu-command](https://github.com/nushell/nushell/pull/8280), and [clean up nu-cmd-lang Cargo.toml](https://github.com/nushell/nushell/pull/8252), and [cratification: Example support](https://github.com/nushell/nushell/pull/8231)
- sholderbach [fixed codecov badge](https://github.com/nushell/nushell/pull/8279), and [Pull bleeding edge virtualenv tests again](https://github.com/nushell/nushell/pull/8262), and [Document and critically review `ShellError` variants - Ep. 1](https://github.com/nushell/nushell/pull/8229)
- Vctr-w created [Type mismatch span fix #7288](https://github.com/nushell/nushell/pull/8271)
- ryand67 created [math floor and ceil round to int rather than float #8258](https://github.com/nushell/nushell/pull/8269)
- amtoine created [REFACTOR: move the standard library to a less-confusing place](https://github.com/nushell/nushell/pull/8265), and [REFACTOR: format some example commands](https://github.com/nushell/nushell/pull/8223), and [FEATURE: print example command results in the `help`](https://github.com/nushell/nushell/pull/8189), and [FEATURE: add the first draft of the standard library](https://github.com/nushell/nushell/pull/8150)
- alesito85 [fixed insecure and timeout flags](https://github.com/nushell/nushell/pull/8255)
- baehyunsol [removed unnecessary rows in `into datetime --list`](https://github.com/nushell/nushell/pull/8243)
- dependabot[bot] [bumped actions/checkout from 2 to 3](https://github.com/nushell/nushell/pull/8240), and [Bump actions-rust-lang/setup-rust-toolchain from 1.4.2 to 1.4.3](https://github.com/nushell/nushell/pull/8239), and [Bump sysinfo from 0.27.7 to 0.28.0](https://github.com/nushell/nushell/pull/8237), and [Bump bytesize from 1.1.0 to 1.2.0](https://github.com/nushell/nushell/pull/8236), and [Bump csv from 1.1.6 to 1.2.0](https://github.com/nushell/nushell/pull/8235), and [Bump procfs from 0.14.1 to 0.15.1](https://github.com/nushell/nushell/pull/8233)
- merelymyself [added case insensitive switch to starts-with and ends-with](https://github.com/nushell/nushell/pull/8221), and [allow for arguments in EDITOR and VISUAL env vars](https://github.com/nushell/nushell/pull/8105)
- Xoffio created [Ctrl+c interruption - `cp` command](https://github.com/nushell/nushell/pull/8219)
- gustavopmaia [added Remove welcome message tutorial](https://github.com/nushell/nushell/pull/8217)
- WindSoilder created [Throw out error if external command in subexpression is failed to run](https://github.com/nushell/nushell/pull/8204)
- Dorumin created [special-case ExternalStream in bytes starts-with](https://github.com/nushell/nushell/pull/8203), and [Make the default prompt play nice with basic fonts](https://github.com/nushell/nushell/pull/8080)
- dmatos2012 created [Error out when Select gets same row](https://github.com/nushell/nushell/pull/8200)
- jt created [Remove the 'env' command, as we have the variable](https://github.com/nushell/nushell/pull/8185)
- kubouch created [Re-implement aliases](https://github.com/nushell/nushell/pull/8123)

## Extension


- adhadse created [modified extension.ts to include standard dir for binary files on linux](https://github.com/nushell/vscode-nushell-lang/pull/82)

## Documentation


- amtoine created [FIX: remove mentions to old and deprecated `&&` and `||` logic operators](https://github.com/nushell/nushell.github.io/pull/802)
- debemdeboas created [Rename $env.PATH to $env.Path to reflect actual shell behavior](https://github.com/nushell/nushell.github.io/pull/801)
- gustavopmaia created [feat: Remove welcome message](https://github.com/nushell/nushell.github.io/pull/799)

## Wasm


## Nu_Scripts


- fdncred created [update scripts that use benchmark to timeit command](https://github.com/nushell/nu_scripts/pull/397), and [update str lpad str rpad to fill](https://github.com/nushell/nu_scripts/pull/396)
- WindSoilder created [fix conda script](https://github.com/nushell/nu_scripts/pull/395)
- washanhanzi created [FIX `kubernetes.nu` since str lpad and str rpad are deprecated in 0.76](https://github.com/nushell/nu_scripts/pull/394)
- Yethal created [Add parsers for cpuinfo and dmidecode](https://github.com/nushell/nu_scripts/pull/393)

## RFCs


## reedline


- merelymyself created [allow reedline ctrl+o to take editor arguments](https://github.com/nushell/reedline/pull/544)

## Nana


