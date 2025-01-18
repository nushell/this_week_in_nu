# This week in Nushell #282

## Nushell

- blindFS [added cancellable heavy requests for LSP](https://github.com/nushell/nushell/pull/14851), [implemented workspace-wide operations for LSP](https://github.com/nushell/nushell/pull/14837), [fixed goto definition on variables in match guard](https://github.com/nushell/nushell/pull/14818), [adjusted span of $it/$in to the first character of its scope](https://github.com/nushell/nushell/pull/14817), and [added inlay hints of types in assignments for LSP](https://github.com/nushell/nushell/pull/14809)
- WindSoilder [fixed issue with variable names ending in duration suffix on the right side of a range](https://github.com/nushell/nushell/pull/14848), and [added a new `help pipe-and-redirect` command](https://github.com/nushell/nushell/pull/14821)
- Bahex [fixed error propagation in export-env](https://github.com/nushell/nushell/pull/14847), [added new operators 'has' and 'not-has'](https://github.com/nushell/nushell/pull/14841), and [added pipeline input support to `generate`](https://github.com/nushell/nushell/pull/14804)
- ysthakur [replaced skim with nucleo for faster completions](https://github.com/nushell/nushell/pull/14846)
- Tyarel8 [made 'into datetime' a noop when input is already a datetime](https://github.com/nushell/nushell/pull/14845)
- hustcer [updated Nu to 0.101.0 for workflow and pinned ubuntu-latest to 22.04 for riscv64gc build](https://github.com/nushell/nushell/pull/14835)
- ChrisDenton [used non-canonicalized paths in shell integrations](https://github.com/nushell/nushell/pull/14832)
- fdncred [replaced icons in grid with devicons + color](https://github.com/nushell/nushell/pull/14827), and [finished removing terminal_size dependency](https://github.com/nushell/nushell/pull/14819)
- sholderbach [renamed/deprecated 'range' to 'slice'](https://github.com/nushell/nushell/pull/14825)
- 132ikl [removed required positional arguments from 'run-external' and 'exec'](https://github.com/nushell/nushell/pull/14765)

## Documentation

- kai687 [showed link for save command](https://github.com/nushell/nushell.github.io/pull/1750)
- schlich [updated hooks.md](https://github.com/nushell/nushell.github.io/pull/1749)
- WindSoilder [added pipeline examples](https://github.com/nushell/nushell.github.io/pull/1748)
- NotTheDr01ds [added package dependencies for Nix on macOS](https://github.com/nushell/nushell.github.io/pull/1746)
- AdrienLemaire [added command_not_found hook for nixos](https://github.com/nushell/nushell.github.io/pull/1745)

## Nu_Scripts

- melMass [updated imgcat and added support for kitty](https://github.com/nushell/nu_scripts/pull/1017)
- LoicRiegel [removed duplicate in git-completions.nu](https://github.com/nushell/nu_scripts/pull/1016)
- sholderbach [updated release excerpt script](https://github.com/nushell/nu_scripts/pull/1015), and [renamed 'range' to 'slice'](https://github.com/nushell/nu_scripts/pull/1014)

## reedline

- sholderbach [fixed new clippy lint from 1.84.0](https://github.com/nushell/reedline/pull/872)

