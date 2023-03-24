# This week in Nushell #187


## Nushell

- jntrnr [added pattern matching](https://github.com/nushell/nushell/pull/8590), created [Fix closures that use matches. Move 'collect' to core.](https://github.com/nushell/nushell/pull/8596), and [Make timeit work with command calls](https://github.com/nushell/nushell/pull/8594), and [Move timeit to use blocks. Make match vars immutable](https://github.com/nushell/nushell/pull/8592), and [Switch let/let-env family to init with math expressions](https://github.com/nushell/nushell/pull/8545), and [Fix command missing hook default config](https://github.com/nushell/nushell/pull/8540)
- amtoine fixed [FIX: do not allow *start > end* in `error make` spans](https://github.com/nushell/nushell/pull/8570), and [FIX: expand all the `base_path`s in `std::test_dirs`](https://github.com/nushell/nushell/pull/8552), and [standard library: fix the readme](https://github.com/nushell/nushell/pull/8526), and [FEATURE: write better errors for `error make` and complete the doc](https://github.com/nushell/nushell/pull/8511), and [standard library: use the standard assert and fix test output](https://github.com/nushell/nushell/pull/8509), and [FEATURE: add a pretty output to `toolkit check pr`](https://github.com/nushell/nushell/pull/8416), and [FEATURE: add `--raw`. `--tabs` and `--indent` to `to nuon` as in `to json`](https://github.com/nushell/nushell/pull/8366)
- StevenDoesStuffs [fixed mode tests which use sh to not run on windows](https://github.com/nushell/nushell/pull/8601)
- fdncred [allowed startup-time to be captured when starting nushell with `nu -c`](https://github.com/nushell/nushell/pull/8599), and [tweak logging format](https://github.com/nushell/nushell/pull/8588), and [Clarify how `register` works](https://github.com/nushell/nushell/pull/8583), and [use reedline main branch](https://github.com/nushell/nushell/pull/8580), and [fixes the ability to have multiple modifiers on keybindings](https://github.com/nushell/nushell/pull/8579), and [make std.nu tests work on mac](https://github.com/nushell/nushell/pull/8576)
- rgwood added [a better error message for `mv` when file not found](https://github.com/nushell/nushell/pull/8586), and [Cell paths: make optional path members short-circuit](https://github.com/nushell/nushell/pull/8554)
- 1Kinoti [unified the `run` functions of `all` and `any`](https://github.com/nushell/nushell/pull/8578), and [fix: `bytes length` example description typo](https://github.com/nushell/nushell/pull/8550), and [allow lists to have type annotations](https://github.com/nushell/nushell/pull/8529)
- Sygmei [added multiple options to http commands](https://github.com/nushell/nushell/pull/8571), and [fix: fixed typo and improved Value TypeMismatch exceptions](https://github.com/nushell/nushell/pull/8324)
- jaudiger [removed the once_cell dependency from nu-test-support create.](https://github.com/nushell/nushell/pull/8568)
- WindSoilder created a [better error message if plugin name doesn't starts with `nu_plugin_`](https://github.com/nushell/nushell/pull/8562)
- stevenxxiu fixed [set `repl_buffer_state` to the REPL buffer after the `pre_execut…](https://github.com/nushell/nushell/pull/8560), and [feat: add a `command_not_found` hook](https://github.com/nushell/nushell/pull/8314)
- hyiltiz fixed [the nu build script since for loops are stateful now](https://github.com/nushell/nushell/pull/8559)
- friedow created [from ssv --aligned-columns should separate lines by character index instead of byte index](https://github.com/nushell/nushell/pull/8558)
- kubouch [disabled alias recursion (for real)](https://github.com/nushell/nushell/pull/8557)
- sholderbach [added a `CONTRIBUTING` section on PRs and git](https://github.com/nushell/nushell/pull/8521)
- presidento created [stdlib: Implement common assert commands](https://github.com/nushell/nushell/pull/8515), and [std lib: extend test runner capabilities](https://github.com/nushell/nushell/pull/8499), and [standard library: add log commands](https://github.com/nushell/nushell/pull/8448)
- stormasm [removed unused imports: `Deserialize`, `Serialize` compiler warning for nu-protocol/src/example.rs](https://github.com/nushell/nushell/pull/8514)
- uaeio created [Decode and Encode hex](https://github.com/nushell/nushell/pull/8392)
- alesito85 [fixed ls symlinks](https://github.com/nushell/nushell/pull/8276)

## Extension

- fdncred created [fix `use` when it's used in variable name](https://github.com/nushell/vscode-nushell-lang/pull/86)

## Documentation


- fdncred created [show the list of combined keybinding modifiers](https://github.com/nushell/nushell.github.io/pull/840)
- presidento created [Add chapter about testing in Nushell](https://github.com/nushell/nushell.github.io/pull/839)
- amtoine created [add a note about "value / description" completion](https://github.com/nushell/nushell.github.io/pull/838)
- petrisch created [DE translation for command_signature](https://github.com/nushell/nushell.github.io/pull/837), and [DE translation for overlays](https://github.com/nushell/nushell.github.io/pull/832)
- thomasgoulet created [Add context aware custom completions to the book](https://github.com/nushell/nushell.github.io/pull/836)
- alurm created [Fix typos in book/stdout_stderr_exit_codes.md](https://github.com/nushell/nushell.github.io/pull/835)
- aidalgol created [Add "Coming from Bash" entries for discarding command output](https://github.com/nushell/nushell.github.io/pull/834)

## Nu_Scripts


- fj0r created [dp for `docker ps` support docker and podman](https://github.com/nushell/nu_scripts/pull/421)
- davidlattimore created [git-completions: Add completions for more subcommands](https://github.com/nushell/nu_scripts/pull/420)
- Hofer-Julian created [Add CODEOWNERS file](https://github.com/nushell/nu_scripts/pull/419), and [conda: Disable prompt via env var instead of flag](https://github.com/nushell/nu_scripts/pull/417)
- amtoine created [FIX: define a `main` function to `use` the themes modules](https://github.com/nushell/nu_scripts/pull/402)
- sholderbach created [Fix `since_last_release.nu` script](https://github.com/nushell/nu_scripts/pull/385)

## reedline


- fdncred created [show the ability to have multiple modifiers](https://github.com/nushell/reedline/pull/559)
- Hofer-Julian created [Check typos in CI](https://github.com/nushell/reedline/pull/557)
- jaudiger created [Add const to some new functions.](https://github.com/nushell/reedline/pull/555)
- ryanwhitehouse created [Allow multi byte characters as the marker without panicking](https://github.com/nushell/reedline/pull/553)
