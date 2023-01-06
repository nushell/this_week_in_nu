# This week in Nushell #176


## Nushell

- webbedspace made [Primitives now use color closures when printed on the command line](https://github.com/nushell/nushell/pull/7650), and [Make `get` hole errors and cell path hole errors identical (improvement on #7002)](https://github.com/nushell/nushell/pull/7647), and [`def`: make various punctuation misuses into errors](https://github.com/nushell/nushell/pull/7624)
- merelymyself created [a new `start` command to open anything and everything](https://github.com/nushell/nushell/pull/7580)
- MehulG created [a url-encoding command](https://github.com/nushell/nushell/pull/7664)
- rgwood added [benchmarks for evaluating default env+config](https://github.com/nushell/nushell/pull/7688), and [Add Criterion benchmarks for parser](https://github.com/nushell/nushell/pull/7686), and [Upgrade all remaining crates to Rust 2021](https://github.com/nushell/nushell/pull/7681), and [Reorder flags in `nu --help`](https://github.com/nushell/nushell/pull/7672), and [Clarify `url` base command](https://github.com/nushell/nushell/pull/7670), and [Delete unused files](https://github.com/nushell/nushell/pull/7668), and [Tweak new input type error message](https://github.com/nushell/nushell/pull/7646), and [Make stream info visible to users in `describe`](https://github.com/nushell/nushell/pull/7589)
- kubouch [removed environment variable hiding from `hide`](https://github.com/nushell/nushell/pull/7687)
- Mehrbod2002 fixed [Continue and Break on Try/Catch ](https://github.com/nushell/nushell/pull/7683), and [Recursion def](https://github.com/nushell/nushell/pull/7657)
- hikilaka implemented [Make `user` parameter optional in `fetch`](https://github.com/nushell/nushell/pull/7680)
- sholderbach  [cleaned up the `where` implementation](https://github.com/nushell/nushell/pull/7679), and [Try to use the latest tagged virtualenv](https://github.com/nushell/nushell/pull/7638), and [Remove `math eval` command](https://github.com/nushell/nushell/pull/7284)
- fdncred [fixed register-plugins script](https://github.com/nushell/nushell/pull/7677)
- xxnuo [fixed build-all-windows.cmd](https://github.com/nushell/nushell/pull/7674)
- aniou [extended config support from F1-F12 to F1-F20, #7666](https://github.com/nushell/nushell/pull/7669)
- WindSoilder made type checking stricter for [last, skip, drop, take until, take while, skip until, skip while, where, reverse, shuffle, append, prepend and sort-by](https://github.com/nushell/nushell/pull/7623)
- TornaxO7 [added a link to list of nu-plugins](https://github.com/nushell/nushell/pull/7649)
- Decodetalkers [fixed a ci problem](https://github.com/nushell/nushell/pull/7643), and [fix: empty cell in select](https://github.com/nushell/nushell/pull/7639), and [return Error if get meet nothing and without "i"](https://github.com/nushell/nushell/pull/7002)
- Yethal [simplified register-plugins.nu](https://github.com/nushell/nushell/pull/7636)
- Kangaxx-0 created [early return for parsing closure and block with interchanged shape](https://github.com/nushell/nushell/pull/7618)
- NotLebedev [fixed `save` error handling](https://github.com/nushell/nushell/pull/7608)
- raccmonteiro [optimized `uniq` and `uniq-by`](https://github.com/nushell/nushell/pull/7534)

## Documentation

- sholderbach [fixed #705: sidebar links German](https://github.com/nushell/nushell.github.io/pull/731)
- WindSoilder [rename from blog text to changeLog](https://github.com/nushell/nushell.github.io/pull/732)
- hustcer [fixed i18n.nu script and update i18n-meta conf](https://github.com/nushell/nushell.github.io/pull/729)
- webbedspace [documented breaking changes](https://github.com/nushell/nushell.github.io/pull/727), and [Fixed various issues in make_docs.nu](https://github.com/nushell/nushell.github.io/pull/652)
- TornaxO7 [updated plugins.md](https://github.com/nushell/nushell.github.io/pull/724), and [Update custom_completions.md](https://github.com/nushell/nushell.github.io/pull/723), and [Update aliases.md](https://github.com/nushell/nushell.github.io/pull/722), and [Fix syntax error fdor menu](https://github.com/nushell/nushell.github.io/pull/720)
- kubouch [fixed wrong PATH append example](https://github.com/nushell/nushell.github.io/pull/721)

## Nu_Scripts

- kubouch [fixed broken conda prompt](https://github.com/nushell/nu_scripts/pull/338)
