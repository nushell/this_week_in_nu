# This week in Nushell #153


## Nushell


- hustcer [bumped to 0.66.3 dev version](https://github.com/nushell/nushell/pull/6183), and [fix typo of `port` command](https://github.com/nushell/nushell/pull/6120) 
- nibon7 [fixed touch panics when using invalid timestamp](https://github.com/nushell/nushell/pull/6181), and [Prevent mv panic again](https://github.com/nushell/nushell/pull/6171), and [Prevent mv panic](https://github.com/nushell/nushell/pull/6158), and [Fix ls panics when a file or directory not exists](https://github.com/nushell/nushell/pull/6148), and [Make path::canonicalize::canonicalize_dot test case more reliable](https://github.com/nushell/nushell/pull/6141), and [Make login.nu work when using nu as a login shell ](https://github.com/nushell/nushell/pull/6134), and [Use local time for logger](https://github.com/nushell/nushell/pull/6132), and [Fix print_table_or_error when `table` is overridden](https://github.com/nushell/nushell/pull/6130), and [Fix PipelineData::print when `table` is overridden](https://github.com/nushell/nushell/pull/6129), and [Simplify print_table_or_error](https://github.com/nushell/nushell/pull/6122), and [Simplify eval_block](https://github.com/nushell/nushell/pull/6121), and [Simplify PipelineData::print](https://github.com/nushell/nushell/pull/6119), and [Don't panic if nu failed to create config files ](https://github.com/nushell/nushell/pull/6104) 
- WindSoilder [made default env works better with bash style PATH](https://github.com/nushell/nushell/pull/6176), and [try make port test more reliable](https://github.com/nushell/nushell/pull/6117) 
- jt [moved `ls` back to last-known-good state](https://github.com/nushell/nushell/pull/6175), and [Revert cp and mv back to last-known-good state](https://github.com/nushell/nushell/pull/6169), and [bump to 0.66.2 dev version](https://github.com/nushell/nushell/pull/6157), and [fix var names coming from long/short flags](https://github.com/nushell/nushell/pull/6142), and [bump to 0.66.1 dev version](https://github.com/nushell/nushell/pull/6140), and [fix 0.66 nu-command crate](https://github.com/nushell/nushell/pull/6138), and [bump to 0.66](https://github.com/nushell/nushell/pull/6137), and [move to latest stable reedline](https://github.com/nushell/nushell/pull/6136), and [require variable names to follow additional restrictions](https://github.com/nushell/nushell/pull/6125), and [Revert "`extern` command should be treated as external"](https://github.com/nushell/nushell/pull/6116), and [exit with non-zero exit code when script ends with non-zero exit](https://github.com/nushell/nushell/pull/6115) 
- kubouch [quickly patched wrong 'export' command name](https://github.com/nushell/nushell/pull/6168), and [Allow modules to `use` other modules](https://github.com/nushell/nushell/pull/6162), and [Use relative paths as file-relative when parsing a file](https://github.com/nushell/nushell/pull/6150), and [Use official virtualenv repo for the CI tests](https://github.com/nushell/nushell/pull/6127) 
- fdncred [add a new welcome banner to nushell](https://github.com/nushell/nushell/pull/6163), and [move application reset mode ansi sequence after cmdline execute](https://github.com/nushell/nushell/pull/6153), and [winget wants this to match](https://github.com/nushell/nushell/pull/6152), and [clean up some comments](https://github.com/nushell/nushell/pull/6147), and [update some dependencies](https://github.com/nushell/nushell/pull/6131), and [expand durations to include month, year, decade](https://github.com/nushell/nushell/pull/6123), and [move the shell integration title setting to the right place](https://github.com/nushell/nushell/pull/6112) 
- elferherrera [maintained quotes for arguments](https://github.com/nushell/nushell/pull/6161), and [plugin show signature](https://github.com/nushell/nushell/pull/6126) 
- merelymyself [allowed view-source to view aliases](https://github.com/nushell/nushell/pull/6135), and [remove misleading example from `source`](https://github.com/nushell/nushell/pull/6118), and [throw error if any? or all? expression invokes invalid command](https://github.com/nushell/nushell/pull/6110) 
- PlasmaIntec [allowed cp multiple files at once](https://github.com/nushell/nushell/pull/6114), and [Allow multiple patterns in ls command](https://github.com/nushell/nushell/pull/6098) 
- Mathspy [added CustomValue support to plugins](https://github.com/nushell/nushell/pull/6070) 

## Documentation

- hustcer created [Refresh commands for v0.66](https://github.com/nushell/nushell.github.io/pull/544), and [Translate hooks.md to Chinese](https://github.com/nushell/nushell.github.io/pull/541) 
- jt created [add the 0.66 release blog](https://github.com/nushell/nushell.github.io/pull/543) 
- kubouch created [Add overviews of chapters; Move Introduction to top level](https://github.com/nushell/nushell.github.io/pull/542) 

## Nu_Scripts

- fdncred created [winget: switch kebab case parameters to snake case](https://github.com/nushell/nu_scripts/pull/269) 
- skelly37 created [Unspanned error](https://github.com/nushell/nu_scripts/pull/267) 
- kubouch created [Update conda to 0.67 variable naming convention](https://github.com/nushell/nu_scripts/pull/266) 

## reedline

- jt created [bump to 0.9](https://github.com/nushell/reedline/pull/454) 
- fdncred created [update some deps](https://github.com/nushell/reedline/pull/453) 
- sholderbach created [Update crossterm to 0.24](https://github.com/nushell/reedline/pull/447) 

## Nana

- rgwood created [Implement copy card button](https://github.com/nushell/nana/pull/61) 
