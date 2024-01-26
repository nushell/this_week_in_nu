# This week in Nushell #231


## Nushell

- maxomatic458 [added an IDE-style completion menu](https://github.com/nushell/nushell/pull/11593), and [updated reedline](https://github.com/nushell/nushell/pull/11589)
- amtoine [fixed spreading of arguments to externals in toolkit](https://github.com/nushell/nushell/pull/11640), and [hid `std testing`](https://github.com/nushell/nushell/pull/11331)
- Hofer-Julian [updated tests to account for internationalization](https://github.com/nushell/nushell/pull/11628)
- nibon7 made dependency version improvements ([1](https://github.com/nushell/nushell/pull/11624), [2](https://github.com/nushell/nushell/pull/11613))
- WindSoilder [unified glob behavior on `open`, `rm`, `cp-old`, `mv`, `umv`, `cp` and `du` commands](https://github.com/nushell/nushell/pull/11621), [made sure that an empty list matches list<int> types](https://github.com/nushell/nushell/pull/11596), [fixed glob expansion if the file path is wrapped in quotes](https://github.com/nushell/nushell/pull/11569), and [removed `--flag: bool` support](https://github.com/nushell/nushell/pull/11541)
- fdncred [made the `input_output_types` of `each` and `par-each` consistent](https://github.com/nushell/nushell/pull/11645), and [cleanup hide testing PR](https://github.com/nushell/nushell/pull/11638), [removed cp-old](https://github.com/nushell/nushell/pull/11622), and [allowed math avg to work with durations](https://github.com/nushell/nushell/pull/11598)
- ysthakur [fixed a help menu regression](https://github.com/nushell/nushell/pull/11608), [made it so we evaluate string interpolation at parse time](https://github.com/nushell/nushell/pull/11562), [upgraded the byte-unit dependency](https://github.com/nushell/nushell/pull/11584)
- Tastaturtaste [improved navigation functionality through reedline](https://github.com/nushell/nushell/pull/11535)
- yukitomoda [implemented `<` and `>` operators for strings](https://github.com/nushell/nushell/pull/11590)
- NotLebedev [fixed explicit flags for plugins](https://github.com/nushell/nushell/pull/11581)
- andrei-27 [added a new `--index` flag to `input list`](https://github.com/nushell/nushell/pull/11580)
- rsteube [added style support to the external completer](https://github.com/nushell/nushell/pull/11442)
- drbrain [added `into cell-path` for dynamic cell-path creation](https://github.com/nushell/nushell/pull/11322)
- stormasm updated versions ([1](https://github.com/nushell/nushell/pull/11635), [2](https://github.com/nushell/nushell/pull/11594))
- davehorner [fixed a panic caused by `ls \\.\pipe`](https://github.com/nushell/nushell/pull/10558)
- crides [fixed env conversion for buffer editor](https://github.com/nushell/nushell/pull/11636), and [made it so that resolving external highlight takes the current PATH into account](https://github.com/nushell/nushell/pull/11618)

## Documentation

- crasite created [Add a section describing how to change table outputs](https://github.com/nushell/nushell.github.io/pull/1224)
- TWSiO created [Adding a page on control flow (and small misspelling)](https://github.com/nushell/nushell.github.io/pull/1222)
- SLASHLogin created [Update `scope`'s syntax in external_completers.md](https://github.com/nushell/nushell.github.io/pull/1220)
- samoylovfp created [Remove outdated commands from explore.md](https://github.com/nushell/nushell.github.io/pull/1219)
- Tirka created [Fix deprecation in external_completers.md (one more)](https://github.com/nushell/nushell.github.io/pull/1218)
- dependabot[bot] created [Bump vite from 5.0.10 to 5.0.12](https://github.com/nushell/nushell.github.io/pull/1217)
- Roshanjossey created [docs: translate metadata page to German](https://github.com/nushell/nushell.github.io/pull/1187)

## Nu_Scripts

- fj0r created [image-push supports renaming via -t](https://github.com/nushell/nu_scripts/pull/750), and [krd for kubectl redistribution deployment](https://github.com/nushell/nu_scripts/pull/745), and [git-v2: fix ga](https://github.com/nushell/nu_scripts/pull/744), and [docker.nu : fix container-log and container-attach, add registry](https://github.com/nushell/nu_scripts/pull/742)
- AucaCoyan created [:bug: fix `winget-completions`](https://github.com/nushell/nu_scripts/pull/749)
- fdncred created [update jalon-git.nu to latest nushell syntax](https://github.com/nushell/nu_scripts/pull/748), and [remove comma.nu from repo](https://github.com/nushell/nu_scripts/pull/747)

## reedline

- maxomatic458 created [Fix style in ide menu](https://github.com/nushell/reedline/pull/725), and [add style from #691 to ide menu](https://github.com/nushell/reedline/pull/722), and [get back the ranges of the strings from the completer used for generating completions](https://github.com/nushell/reedline/pull/713), and [respect windows newline in update_values](https://github.com/nushell/reedline/pull/709), and [get correct cursor pos when menu indicator contains newline](https://github.com/nushell/reedline/pull/708)
- stormasm created [update history error message](https://github.com/nushell/reedline/pull/721), and [update the ide_completions example with more cases to explore](https://github.com/nushell/reedline/pull/718), and [modify ci.yml to see if it will turn off code coverage in the reedline repo](https://github.com/nushell/reedline/pull/710)
- rsteube created [columnar_menu: fix explicit highlighting color](https://github.com/nushell/reedline/pull/720), and [suggestion: added style](https://github.com/nushell/reedline/pull/691)
- kubouch created [Update dependencies](https://github.com/nushell/reedline/pull/717), and [Update nu-ansi-term to 0.50.0](https://github.com/nushell/reedline/pull/716)
- Tastaturtaste created [Remove conflicting keybindings added with selection feature](https://github.com/nushell/reedline/pull/715)
- abusch created [Clipboard graceful handling](https://github.com/nushell/reedline/pull/712)
- nibon7 created [ Don't panic when creating `FileBackedHistory` with `usize::MAX` capacity ](https://github.com/nushell/reedline/pull/701)
- andreistan26 created [Fix panic when history size set to 0](https://github.com/nushell/reedline/pull/653)
