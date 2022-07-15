# This week in Nushell #151


## Nushell


- merelymyself [added `wc` search term for `size` and `length`](https://github.com/nushell/nushell/pull/6056), and [allow for easy reset of config files with a single command](https://github.com/nushell/nushell/pull/6041), and [make auto-cd change `$env.OLDPWD`](https://github.com/nushell/nushell/pull/6019), and [add `unspanned` flag to error make, add tests](https://github.com/nushell/nushell/pull/6017), and [throw parser error when multiple short flags are defined without whitespace](https://github.com/nushell/nushell/pull/6000)
- fdncred [ensured users colors are maintained when highlighting find matches](https://github.com/nushell/nushell/pull/6054), and [allow `into int` to convert octal numbers and 0 padded strings](https://github.com/nushell/nushell/pull/6053), and [add ability to do into int on floats using a radix](https://github.com/nushell/nushell/pull/6033), and [fix small bug converting string to int](https://github.com/nushell/nushell/pull/6031), and [fixes ansi escape leakage from ill-behaved externals, again!](https://github.com/nushell/nushell/pull/6012), and [update some dependencies](https://github.com/nushell/nushell/pull/6009)
- Benjamin-L [fixed documentation of plugin encodings](https://github.com/nushell/nushell/pull/6052)
- stormasm created [Cargo.lock was not checked in on typetag revert](https://github.com/nushell/nushell/pull/6050)
- zhiburt [refactored nu_table](https://github.com/nushell/nushell/pull/6049), and [nu-table: Bump tabled to master](https://github.com/nushell/nushell/pull/6038), and [nu-table: Use all available termwidth](https://github.com/nushell/nushell/pull/6037), and [nu-table: Restore atty check](https://github.com/nushell/nushell/pull/6036), and [nu-table: Don't show empty header](https://github.com/nushell/nushell/pull/6035), and [nu_table: Fix truncating logic](https://github.com/nushell/nushell/pull/6028), and [nu_table: Fix style of tables with no header](https://github.com/nushell/nushell/pull/6025), and [Move wrap responsibility on tabled](https://github.com/nushell/nushell/pull/5999)
- nibon7 [fixed ps command on linux](https://github.com/nushell/nushell/pull/6047), and [Fix panic when opening symlink which points to an inaccessible directory](https://github.com/nushell/nushell/pull/6034)
- Kangaxx-0 [downgraded typetag to 0.1.8](https://github.com/nushell/nushell/pull/6044)
- WindSoilder created [load default env when user don't specified env path](https://github.com/nushell/nushell/pull/6040), and [Add bytes collect, bytes remove, bytes build cmd](https://github.com/nushell/nushell/pull/6008)
- jt [used simpler reedline](https://github.com/nushell/nushell/pull/6016)
- kubouch [allowed keeping selected environment variables from removed overlay](https://github.com/nushell/nushell/pull/6007), and [Fix load order of config files](https://github.com/nushell/nushell/pull/6006), and [Split merging of parser delta and stack environment](https://github.com/nushell/nushell/pull/6005), and [Revert "make module imports in scripts used for relative path."](https://github.com/nushell/nushell/pull/6002), and [Expand Hooks Functionality](https://github.com/nushell/nushell/pull/5982)

## Documentation

- merelymyself created [Remove entry for `count`](https://github.com/nushell/nushell.github.io/pull/533)
- WindSoilder created [add light theme relative doc](https://github.com/nushell/nushell.github.io/pull/532)


## Nu_Scripts

- WindSoilder created [fix env.PATH after conda activate](https://github.com/nushell/nu_scripts/pull/264)

## reedline

- drbrain created [Support swtiching the case of a char with ~ in vi](https://github.com/nushell/reedline/pull/452), and [Support vi mode ; and , motions](https://github.com/nushell/reedline/pull/450)
- jt [removed animations and resize repaint](https://github.com/nushell/reedline/pull/451)
