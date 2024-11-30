# This week in Nushell #275

## Nushell

- ayax79 [upgraded to polars 0.44](https://github.com/nushell/nushell/pull/14478)
- 132ikl [improved try/catch errors](https://github.com/nushell/nushell/pull/14477), and [made length only operate on supported input types](https://github.com/nushell/nushell/pull/14475)
- sholderbach [removed unused `FlatShape`s `And`/`Or`](https://github.com/nushell/nushell/pull/14476)
- fdncred [updated the Rust toolchain to rust 1.81.0](https://github.com/nushell/nushell/pull/14473), and [removed `terminal_size` crate from several places](https://github.com/nushell/nushell/pull/14423)
- cptpiepmatz [started to add WASM support again](https://github.com/nushell/nushell/pull/14418)
- paulie4 [added more `less` key bindings and added `Transition::None` to `explore`](https://github.com/nushell/nushell/pull/14468)
- NotTheDr01ds [allowed inherited environment variables](https://github.com/nushell/nushell/pull/14467), [updated default-files README](https://github.com/nushell/nushell/pull/14461), [bumped reedline to current main](https://github.com/nushell/nushell/pull/14455), [added example for PROMPT_COMMAND_RIGHT](https://github.com/nushell/nushell/pull/14439), [removed long-unused `autoenv` tests](https://github.com/nushell/nushell/pull/14436), [ensured config record is always populated during startup](https://github.com/nushell/nushell/pull/14435), and [deprecated `date to-record` and `date to-table`](https://github.com/nushell/nushell/pull/14319)
- WindSoilder [updated unicode-width to 0.2](https://github.com/nushell/nushell/pull/14456), [updated miette to 7.3](https://github.com/nushell/nushell/pull/14454), [raised a ParseError if assigning to a non-variable or non-mutable-variable](https://github.com/nushell/nushell/pull/14405), [deprecated --ignore-shell-errors and --ignore-program-errors in `do`](https://github.com/nushell/nushell/pull/14385), and [made `std help` more user friendly](https://github.com/nushell/nushell/pull/14347)
- Bahex [propagated existing errors in `insert` and `merge`](https://github.com/nushell/nushell/pull/14453), and [added `term query`, for querying information from terminals](https://github.com/nushell/nushell/pull/14427)
- PegasusPlusUS [fixed an unstable test case](https://github.com/nushell/nushell/pull/14451)
- IanManske [removed the obsolete `ListStream` type](https://github.com/nushell/nushell/pull/14425), [added a `Filesize` type](https://github.com/nushell/nushell/pull/14369), [made `Hooks` fields non-optional to match the new config defaults](https://github.com/nushell/nushell/pull/14345), and [changed append operator to concatenation operator](https://github.com/nushell/nushell/pull/14344)
- ysthakur [fixed: Respect sort in custom completions](https://github.com/nushell/nushell/pull/14424)
- cosineblast [implemented chunk_by operation](https://github.com/nushell/nushell/pull/14410)
- amtoine [added `from ndnuon` and `to ndnuon` to stdlib](https://github.com/nushell/nushell/pull/14334)
- DziubaMaksym [fixed a README link](https://github.com/nushell/nushell/pull/14465)

## Documentation

- NotTheDr01ds [updated/renamed Shells-in-Shells Chapter - 0.100 changes](https://github.com/nushell/nushell.github.io/pull/1653)
- WieeRd [updated the Fish completer to leverage nushell/nushell#14399](https://github.com/nushell/nushell.github.io/pull/1649), and [fixed broken links to the default config files](https://github.com/nushell/nushell.github.io/pull/1648)

## Nu_Scripts

- rikukiix [added Catppuccin Frappe theme](https://github.com/nushell/nu_scripts/pull/984)

