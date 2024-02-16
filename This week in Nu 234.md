# This week in Nushell #234

## Nushell

- IanManske [simplified input types for `select` and `reject`](https://github.com/nushell/nushell/pull/11859), [removed the required positional arg for some file system commands](https://github.com/nushell/nushell/pull/11858), [fixed an error message for `headers`](https://github.com/nushell/nushell/pull/11809), [prevented duplicate keys for `lazy make`](https://github.com/nushell/nushell/pull/11808), and [prevented duplicate record keys when decoding from nuon](https://github.com/nushell/nushell/pull/11807)
- ayax79  [added the ability to cast a dataframe's column to a different datatype](https://github.com/nushell/nushell/pull/11803)
- kit494way [fixed `commandline --cursor` to return an int](https://github.com/nushell/nushell/pull/11864)
- hustcer [fixed an issue building for riscv64](https://github.com/nushell/nushell/pull/11861)
- ysthakur [disallowed spreading lists automatically when calling externals](https://github.com/nushell/nushell/pull/11857)
- fdncred [updated default_config with new defaults](https://github.com/nushell/nushell/pull/11856), and bumped the reedline version ([1](https://github.com/nushell/nushell/pull/11844), [2](https://github.com/nushell/nushell/pull/11840))
- sholderbach [fixed `workspace.members` for dependabot](https://github.com/nushell/nushell/pull/11855)
- WindSoilder [moved `du` from platform to filesystem](https://github.com/nushell/nushell/pull/11852)
- nibon7 [bumped polars from 0.36 to 0.37](https://github.com/nushell/nushell/pull/11848)
- dannou812 [fixed date formatting in `to/from toml`](https://github.com/nushell/nushell/pull/11846)
- 0323pin [fixed a build failure on NetBSD](https://github.com/nushell/nushell/pull/11823)
- CAD97 [simplified prompt tilde substitution](https://github.com/nushell/nushell/pull/11822)

## Documentation

- nett00n created [Update coming_from_bash.md](https://github.com/nushell/nushell.github.io/pull/1255)
- WindSoilder created [fill contents to handling stderr](https://github.com/nushell/nushell.github.io/pull/1240)

## Nu_Scripts

- jolheiser created [fix: update deprecated spread operator in just](https://github.com/nushell/nu_scripts/pull/758)

## reedline

- Tastaturtaste created [Fix logic error in style_range leading to overflow on subtraction](https://github.com/nushell/reedline/pull/751)
