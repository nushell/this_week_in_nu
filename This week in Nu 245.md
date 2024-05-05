# This week in Nushell #245


## Nushell

- sholderbach [updated `interprocess` to 2.0.1](https://github.com/nushell/nushell/pull/12769), [specified the required minimum `chrono` version](https://github.com/nushell/nushell/pull/12766), [pinned `base64` to the fixed patch version](https://github.com/nushell/nushell/pull/12762), [updated PLATFORM_SUPPORT regarding feature flags](https://github.com/nushell/nushell/pull/12741), [avoided taking unnecessary ownership of intermediates](https://github.com/nushell/nushell/pull/12740), [fixed `clippy::wrong_self_convention` in polars plugin](https://github.com/nushell/nushell/pull/12737), [fixed new clippy lints](https://github.com/nushell/nushell/pull/12736), [eliminated dead code in `nu-explore`](https://github.com/nushell/nushell/pull/12735), and [updated the bundled readme in release archives](https://github.com/nushell/nushell/pull/12688).
- YizhePKU [fixed PWD not pointing to root paths](https://github.com/nushell/nushell/pull/12761), [changed environment variables to be case-preserving](https://github.com/nushell/nushell/pull/12701), [made path expansion no longer remove trailing slashes](https://github.com/nushell/nushell/pull/12662), and [migrated to a new PWD API](https://github.com/nushell/nushell/pull/12603).
- devyn [fixed trailing slash in PWD set by `cd`](https://github.com/nushell/nushell/pull/12760), [upgraded to interprocess 2.0.0](https://github.com/nushell/nushell/pull/12729), [flushed on every plugin `Data` message](https://github.com/nushell/nushell/pull/12728), [added `toolkit release-pkg windows` for Windows release pkg builds](https://github.com/nushell/nushell/pull/12727), [fixed Windows Terminal profile installation](https://github.com/nushell/nushell/pull/12714), [bumped version to `0.93.1`](https://github.com/nushell/nushell/pull/12710), [bumped version to `0.93.0`](https://github.com/nushell/nushell/pull/12709), [bumped `reedline` to `0.32.0`](https://github.com/nushell/nushell/pull/12708), [fixed missing local socket feature](https://github.com/nushell/nushell/pull/12698), and [made `bytes build` accept integer values as individual bytes](https://github.com/nushell/nushell/pull/12685).
- ExaltedBagel [enabled columns with spaces for into_sqlite by adding quotes to column names](https://github.com/nushell/nushell/pull/12759).
- IanManske [bumped `base64` to 0.22.1](https://github.com/nushell/nushell/pull/12757), [refactored flattening to reduce intermediate allocations](https://github.com/nushell/nushell/pull/12756), [fixed a typo](https://github.com/nushell/nushell/pull/12752), [removed some macros](https://github.com/nushell/nushell/pull/12742), [added `fs` feature to `nix` dependency](https://github.com/nushell/nushell/pull/12702), [removed lazy records](https://github.com/nushell/nushell/pull/12682), and provided a [`ListStream` touchup](https://github.com/nushell/nushell/pull/12524).
- szepeviktor [minimized future false positive typos](https://github.com/nushell/nushell/pull/12751).
- rgwood [made some changes to `explore`: adopted `anyhow`, supported `CustomValue`, removed help system](https://github.com/nushell/nushell/pull/12692).
- hustcer [upgraded Nu to v0.93.0 for nightly and release workflow](https://github.com/nushell/nushell/pull/12721).
- fdncred [changed wix install method from perMachine to perUser](https://github.com/nushell/nushell/pull/12720), [fixed a rust-analyzer warning](https://github.com/nushell/nushell/pull/12694), [restored `query web --as-table` to working order](https://github.com/nushell/nushell/pull/12693), and [overhauled shell_integration to enable individual control over ansi escape sequences](https://github.com/nushell/nushell/pull/12629), and [added raw-string literal support](https://github.com/nushell/nushell/pull/9956).
- maxim-uvarov [added more tests to the `polars` plugin](https://github.com/nushell/nushell/pull/12719).
- amtoine [added support for cell-paths to NUON](https://github.com/nushell/nushell/pull/12718) and [improved NUON documentation](https://github.com/nushell/nushell/pull/12717).
- FilipAndersson245 [initiated Tango migration](https://github.com/nushell/nushell/pull/12469).
- lavafroth [fixed a bug to prevent relative directory traversal from crashing](https://github.com/nushell/nushell/pull/12438).
- merelymyself [prevented `each` from swallowing errors when `eval_block` returns a `ListStream`](https://github.com/nushell/nushell/pull/12412).
- rtpg [reported errors that occur on file operations in ls](https://github.com/nushell/nushell/pull/12033).

## Documentation

- woosaaahh [corrected a wrong result in an example from 'lang-guide'](https://github.com/nushell/nushell.github.io/pull/1390).
- hustcer [fixed make_docs.nu for Nu v0.93.0](https://github.com/nushell/nushell.github.io/pull/1389), [upgraded lefthook, shiki, and vuepress plugins](https://github.com/nushell/nushell.github.io/pull/1383), and [refreshed command docs for Nu v0.93](https://github.com/nushell/nushell.github.io/pull/1379).
- UmeSiyah [fixed username in sys_get_nested_example.sh](https://github.com/nushell/nushell.github.io/pull/1386).
- devyn [warned about Windows Installer on the 0.93.0 release notes](https://github.com/nushell/nushell.github.io/pull/1384), [fixed a broken link to plugin protocol reference](https://github.com/nushell/nushell.github.io/pull/1381), [clarified that `plugin use` is not needed in the config file](https://github.com/nushell/nushell.github.io/pull/1380), [provided release notes for 0.93.0](https://github.com/nushell/nushell.github.io/pull/1368), and [documented the plugin management overhaul - new commands and new file format](https://github.com/nushell/nushell.github.io/pull/1367), along with documentation for other features.
- mandarvaze [corrected a minor typo in background_task.md](https://github.com/nushell/nushell.github.io/pull/1382).
- fdncred [wrote the 30k star blog post](https://github.com/nushell/nushell.github.io/pull/1377).
- YizhePKU [explained that $env is case-insensitive](https://github.com/nushell/nushell.github.io/pull/1376).
- IanManske [nearly finished 0.93.0 release notes](https://github.com/nushell/nushell.github.io/pull/1375) and [edited `0.93.0` release notes](https://github.com/nushell/nushell.github.io/pull/1373).
- ayax79 [provided release notes for Polars plugin and dataframes deprecation](https://github.com/nushell/nushell.github.io/pull/1374).
- tesujimath [added a reference to Nu Plugin Tracer in the Nushell Book](https://github.com/nushell/nushell.github.io/pull/1372).

## Nu_Scripts

- IanManske [updated the release script](https://github.com/nushell/nu_scripts/pull/828).
- dam4rus [removed deprecated --redirect-stdout in git branch cleanup](https://github.com/nushell/nu_scripts/pull/827).
- rayanamal [updated the README.md for background tasks](https://github.com/nushell/nu_scripts/pull/826).
- kubouch [fixed the link for creating release note PR](https://github.com/nushell/nu_scripts/pull/728).

## reedline

- devyn [bumped version for `0.32.0` release](https://github.com/nushell/reedline/pull/785).
