# This week in Nushell #147

## Nushell


- rgwood created [Fix parser panic](https://github.com/nushell/nushell/pull/5820)
- merelymyself created [Fixes `to nuon` for `inf`, `-inf`, and `NaN`](https://github.com/nushell/nushell/pull/5818), and [Attempts to fix file completions for `open`, `rm` and `ls` (and other filesystem commands)](https://github.com/nushell/nushell/pull/5805), and [shows location of sqlite3 history file](https://github.com/nushell/nushell/pull/5784), and [Add option to sort-by naturally](https://github.com/nushell/nushell/pull/5774), and [Attempts to add `//` math operator](https://github.com/nushell/nushell/pull/5759)
- fdncred created [add more columns to the history command when using sqlite history](https://github.com/nushell/nushell/pull/5817), and [more verbose error handling](https://github.com/nushell/nushell/pull/5765)
- Kangaxx-0 created [Fix alias completion crash](https://github.com/nushell/nushell/pull/5814), and [Add NU config to allow user be able to turn off external completion](https://github.com/nushell/nushell/pull/5773)
- stormasm created [Move the history and tutor commands out of core_commands](https://github.com/nushell/nushell/pull/5813), and [default_context.rs: move Du to platform instead of core](https://github.com/nushell/nushell/pull/5795)
- wolimst created [Add Windows Terminal profile and icon in Windows control panel](https://github.com/nushell/nushell/pull/5812)
- kubouch created [Add test requirements to PR template](https://github.com/nushell/nushell/pull/5809)
- nibon7 created [Fix drop nth with open end range on 32-bit platforms](https://github.com/nushell/nushell/pull/5808)
- WindSoilder created [add notes for def_env](https://github.com/nushell/nushell/pull/5807), and [add light theme to default_config](https://github.com/nushell/nushell/pull/5804), and [add --values flag to sort record by values, by default, sort record by keys](https://github.com/nushell/nushell/pull/5782), and [sort not change shape](https://github.com/nushell/nushell/pull/5778), and [path join support multi path](https://github.com/nushell/nushell/pull/5775), and [fix arg parse](https://github.com/nushell/nushell/pull/5754)
- elferherrera created [Standardise to commands](https://github.com/nushell/nushell/pull/5800), and [Update polars 0.22.8](https://github.com/nushell/nushell/pull/5791), and [bool type for binary operations](https://github.com/nushell/nushell/pull/5779), and [each while command](https://github.com/nushell/nushell/pull/5771), and [filesize conversion](https://github.com/nushell/nushell/pull/5770), and [expression to literal](https://github.com/nushell/nushell/pull/5769), and [Remove dfr from dataframe commands](https://github.com/nushell/nushell/pull/5760)
- hustcer created [Try to fix winget package submit](https://github.com/nushell/nushell/pull/5790), and [Add setup-nu link in README.md](https://github.com/nushell/nushell/pull/5763)
- sholderbach created [Pin reedline v0.7.0 for the nushell v0.64.0 release](https://github.com/nushell/nushell/pull/5781)
- jntrnr created [bump to 0.64](https://github.com/nushell/nushell/pull/5777), and [Force floats to output a decimal in nuon](https://github.com/nushell/nushell/pull/5768)
- Mathspy created [Should we keep old semantics of `uniq` command?](https://github.com/nushell/nushell/pull/5761)
- phiresky created [SQLite History MVP with timestamp, duration, working directory, exit status metadata](https://github.com/nushell/nushell/pull/5721)
- onthebridgetonowhere created [Fix drop nth bug](https://github.com/nushell/nushell/pull/5312)

## Documentation


- elferherrera created [Standard command name](https://github.com/nushell/nushell.github.io/pull/511), and [remove dfr from dataframe chapter](https://github.com/nushell/nushell.github.io/pull/493)
- hustcer created [Remove old_book related stuffs](https://github.com/nushell/nushell.github.io/pull/508), and [Fix command overlapping for `make_docs.nu` and Refresh commands for v0.64](https://github.com/nushell/nushell.github.io/pull/505), and [fix blog layout and font color of article title for dark mode](https://github.com/nushell/nushell.github.io/pull/504), and [Fix some broken links for de](https://github.com/nushell/nushell.github.io/pull/502), and [Add nav links for some new de docs, and do dome doc formatting](https://github.com/nushell/nushell.github.io/pull/495)
- rgwood created [Remove MS CRT info now that we're statically linking it](https://github.com/nushell/nushell.github.io/pull/506)
- jntrnr created [Add the 0.64 release blog](https://github.com/nushell/nushell.github.io/pull/503)
- Kangaxx-0 created [Add configuration command](https://github.com/nushell/nushell.github.io/pull/501)
- aslilac created [docs(book): Update the "Coming from Bash" page](https://github.com/nushell/nushell.github.io/pull/499)
- jcjolley created [Show how to cast between number types](https://github.com/nushell/nushell.github.io/pull/498)
- f2hafner created [Fixed example causing type_mismatch in working_with_lists.md](https://github.com/nushell/nushell.github.io/pull/497)
- petrisch created [Some new German translation with new snippet links](https://github.com/nushell/nushell.github.io/pull/494)

## Nu_Scripts


- skelly37 created [maths refactor](https://github.com/nushell/nu_scripts/pull/254), and [up.nu fixed](https://github.com/nushell/nu_scripts/pull/252)
- Yethal created [Update branch-protections.nu](https://github.com/nushell/nu_scripts/pull/251), and [Add branch protections](https://github.com/nushell/nu_scripts/pull/250)


## reedline


- WindSoilder created [fix double bang](https://github.com/nushell/reedline/pull/444)
- fdncred created [add impl Display to HistoryItemId and HistorySessionId](https://github.com/nushell/reedline/pull/443)
- drbrain created [Add vi WORD motions B, E, W](https://github.com/nushell/reedline/pull/441)
- sholderbach created [Prepare 0.7.0 release](https://github.com/nushell/reedline/pull/440), and [Expose the `History` query functionality](https://github.com/nushell/reedline/pull/439)
