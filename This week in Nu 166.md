# This week in Nushell #166

## Nushell

- sholderbach [updated the `nix` crate to `0.25` and removed unused features](https://github.com/nushell/nushell/pull/6924),  [fixed `each while` behavior when printing and maybe in other situations by fusing the iterator](https://github.com/nushell/nushell/pull/6897), [wrapped `open` parse errors from `from` commands](https://github.com/nushell/nushell/pull/6877), [removed unnecessary `#[allow(...)]` annotations](https://github.com/nushell/nushell/pull/6870), and [reduced required dependencies for diagnostics](https://github.com/nushell/nushell/pull/6648)
- paper-lark [highlighted matching brackets / parentheses](https://github.com/nushell/nushell/pull/6655)
- rgwood [updated the PR template to mention user-facing changes](https://github.com/nushell/nushell/pull/6923), and [improved the error message for `get 0` on non-collection types](https://github.com/nushell/nushell/pull/6892), added [support ranges in `str substring`](https://github.com/nushell/nushell/pull/6867), and [fixed `ps` on Linux](https://github.com/nushell/nushell/pull/6858)
- webbedspace [updated merge to also take single records (closes #5281)](https://github.com/nushell/nushell/pull/6919), made [further edits to help messages](https://github.com/nushell/nushell/pull/6913), and [edited a small handful of help messages](https://github.com/nushell/nushell/pull/6868)
- kambala-decapitator [fixed the description of build-string's second example](https://github.com/nushell/nushell/pull/6912)
- ChrisDenton [fixed UNC shares](https://github.com/nushell/nushell/pull/6824)
- melMass created [docs: 📝 add "map" to each's search terms](https://github.com/nushell/nushell/pull/6903)
- zhiburt created [table: Show truncated record differently](https://github.com/nushell/nushell/pull/6884), and [`table -e` Fix stackoverflow (cause endless empty list)](https://github.com/nushell/nushell/pull/6847)
- FilipAndersson245 [bumped Windows dependencies](https://github.com/nushell/nushell/pull/6865)
- dandavison [exposed reedline EditCommand::Complete command](https://github.com/nushell/nushell/pull/6863)
- nibon7 created [path: fix error message](https://github.com/nushell/nushell/pull/6860), and [Add support to render right prompt on last line of the prompt](https://github.com/nushell/nushell/pull/6781), and [Prepend directory to the binary tarball](https://github.com/nushell/nushell/pull/6701)
- Decodetalkers implemented [feat: coredump](https://github.com/nushell/nushell/pull/6791)
- merelymyself [added a more helpful error for calling a decl that exists in a module](https://github.com/nushell/nushell/pull/6752)

## Extension

- nibon7 [added a right prompt guide](https://github.com/nushell/nushell.github.io/pull/651), and [right prompt release notes](https://github.com/nushell/nushell.github.io/pull/650)
- kambala-decapitator [fixed the description of build-string's second example](https://github.com/nushell/nushell.github.io/pull/649)
- webbedspace [added a categories column to command_reference](https://github.com/nushell/nushell.github.io/pull/646)


## Nu_Scripts

- SUPERCILEX [added a prompt with exit code and command duration](https://github.com/nushell/nu_scripts/pull/309)
- fdncred [tweaked the no back progress bar example](https://github.com/nushell/nu_scripts/pull/308)
- WindSoilder [fixed a conda deactivate error when activate with no-prompt](https://github.com/nushell/nu_scripts/pull/307)


## reedline

- nibon7 created [show right prompt on indicator line in last line mode](https://github.com/nushell/reedline/pull/501)
- dandavison created [Tab inline completion](https://github.com/nushell/reedline/pull/498)