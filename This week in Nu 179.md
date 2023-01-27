# This week in Nushell #179


## Nushell


- rgwood [removed 🆖 comments](https://github.com/nushell/nushell/pull/7877), and [Clean up `cd.rs`](https://github.com/nushell/nushell/pull/7876), and [Fix the build after #7204](https://github.com/nushell/nushell/pull/7857)
- jntrnr [added 'enumerate' command for enumeration](https://github.com/nushell/nushell/pull/7871)
- Hofer-Julian [extracted `gather_commandline_args`](https://github.com/nushell/nushell/pull/7868), and [Reduce again the number of match calls](https://github.com/nushell/nushell/pull/7815)
- fdncred created [with the release of rust 1.67, let's bump to 1.66.1](https://github.com/nushell/nushell/pull/7866), and [add decimal to SyntaxShape](https://github.com/nushell/nushell/pull/7852), and [add some startup performance metrics](https://github.com/nushell/nushell/pull/7851), and [print nushell startup time](https://github.com/nushell/nushell/pull/7831)
- zhiburt created [nu-commands/table (`table -e`) Recognize limited space better](https://github.com/nushell/nushell/pull/7861)
- SUPERCILEX [fixed `do` swallowing all output when ignoring errors](https://github.com/nushell/nushell/pull/7859), and [Fix pipeline stall in `do` during capture and remove excessive redirections](https://github.com/nushell/nushell/pull/7204)
- WindSoilder [improved doc about flatten](https://github.com/nushell/nushell/pull/7856), and [Fix multi-line redirection inside a block](https://github.com/nushell/nushell/pull/7808)
- NotLebedev created [To csv fix](https://github.com/nushell/nushell/pull/7850)
- dependabot[bot] [bumped actions-rust-lang/setup-rust-toolchain from 1.3.4 to 1.3.5](https://github.com/nushell/nushell/pull/7840), and [Bump sysinfo from 0.26.4 to 0.27.7](https://github.com/nushell/nushell/pull/7839), and [Bump miette from 5.3.0 to 5.5.0](https://github.com/nushell/nushell/pull/7838), and [Bump shadow-rs from 0.16.3 to 0.20.0](https://github.com/nushell/nushell/pull/7837), and [Bump rayon from 1.5.3 to 1.6.1](https://github.com/nushell/nushell/pull/7836), and [Bump scraper from 0.13.0 to 0.14.0](https://github.com/nushell/nushell/pull/7835), and [Bump regex from 1.6.0 to 1.7.1](https://github.com/nushell/nushell/pull/7833)
- kubouch [fixed command name lookup for known externals](https://github.com/nushell/nushell/pull/7830), and [Allow main command to define top-level module command](https://github.com/nushell/nushell/pull/7764)
- michel-slm created [[nu-test-support] Gate system locale tests](https://github.com/nushell/nushell/pull/7824)
- VincenzoCarlino created [Feat/7725 url join](https://github.com/nushell/nushell/pull/7823)
- zoechi [fixed typos](https://github.com/nushell/nushell/pull/7811)
- merelymyself [converted SyntaxShape::Table into the corresponding Type](https://github.com/nushell/nushell/pull/7781)
- webbedspace created [`benchmark` now pipes input into the closure](https://github.com/nushell/nushell/pull/7776)
- Kangaxx-0 created [Incorrect parsing of unbalanced braces based on issue 6914](https://github.com/nushell/nushell/pull/7621)

## Extension


- Hofer-Julian created [Add another directory where nu might be installed](https://github.com/nushell/vscode-nushell-lang/pull/75)
- fdncred created [get ready for new 1.0 release](https://github.com/nushell/vscode-nushell-lang/pull/74)
- glcraft created [New syntax highlight](https://github.com/nushell/vscode-nushell-lang/pull/73)

## Documentation


- max-nextcloud created [Update rust version requirement in installation](https://github.com/nushell/nushell.github.io/pull/752)
- WindSoilder created [update doc about stdout and stderr](https://github.com/nushell/nushell.github.io/pull/751)

## Wasm


## Nu_Scripts


- fdncred created [small tweaks to get panache working again](https://github.com/nushell/nu_scripts/pull/365), and [fix oh-my.nu script after `do` changes in nushell](https://github.com/nushell/nu_scripts/pull/364)
- Hofer-Julian created [Fix scoop completions](https://github.com/nushell/nu_scripts/pull/363), and [git-completions: Stop checking `--force-with-lease`](https://github.com/nushell/nu_scripts/pull/362), and [conda: Check if environment exists before activating](https://github.com/nushell/nu_scripts/pull/361), and [Explain how to create an alias for conda activate without a prompt](https://github.com/nushell/nu_scripts/pull/360)
- schrieveslaach created [Fix git checkout/switch completions](https://github.com/nushell/nu_scripts/pull/359), and [Improve git checkout/switch completions](https://github.com/nushell/nu_scripts/pull/358)
- 1Kinoti created [add todo script](https://github.com/nushell/nu_scripts/pull/357)

## RFCs


## reedline


- dgkf created [Allow configuration of multiline prompt color](https://github.com/nushell/reedline/pull/531)
