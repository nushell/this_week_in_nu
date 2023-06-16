# This week in Nushell #199


## Nushell

- dev-cyprium [fixed a panic bug in platform ansi logic (Closes #9448)](https://github.com/nushell/nushell/pull/9458)
- BrianLondon [added plugin api docs](https://github.com/nushell/nushell/pull/9452)
- bgeron [fixed usage for the exit command.](https://github.com/nushell/nushell/pull/9450), and [a bug in std dirs drop; improve documentation](https://github.com/nushell/nushell/pull/9449)
- stormasm created [nu-cmd-lang readme](https://github.com/nushell/nushell/pull/9446), and [add in the nu-cmd-extra tests to the CI](https://github.com/nushell/nushell/pull/9439)
- sholderbach [dropped unused `nu-color-config` in `nu-cmd-lang`](https://github.com/nushell/nushell/pull/9444), and [broke up interdependencies of command crates](https://github.com/nushell/nushell/pull/9429), and [moved `explore` command out of `nu-command` deps](https://github.com/nushell/nushell/pull/9421), and [enabled history entry exclusion with leading space](https://github.com/nushell/nushell/pull/9371)
- hustcer [changed the nightly build schedule make it start by 9:15 BeiJing Time](https://github.com/nushell/nushell/pull/9442), and [fixed cleanup of nightly build workflow](https://github.com/nushell/nushell/pull/9441), and [fixed the cleanup of old nightly releases](https://github.com/nushell/nushell/pull/9433), and [Use Nushell v0.81 for release workflows](https://github.com/nushell/nushell/pull/9432), and [Synchronize code before the nightly build starts](https://github.com/nushell/nushell/pull/9430), and [Fix removal of old nightly releases](https://github.com/nushell/nushell/pull/9423), and [Try to make a nightly release by workflow](https://github.com/nushell/nushell/pull/9422), and [Reset .github/workflows/release-pkg.nu](https://github.com/nushell/nushell/pull/9414)
- alkhatib [fixed clippy errors (Mac)](https://github.com/nushell/nushell/pull/9440), and [http post --content-type should set Content-Type header](https://github.com/nushell/nushell/pull/9431)
- WindSoilder [allowed comments in multiple line pipeline](https://github.com/nushell/nushell/pull/9436), and [disable bracketed paste during evaluation](https://github.com/nushell/nushell/pull/9399), and [`save` command: Don't use BufWriter to write external strem to a file](https://github.com/nushell/nushell/pull/9377), and [don't allow `save` command to save both stdout and stderr to the same file](https://github.com/nushell/nushell/pull/9368)
- hanjunghyuk [removed ZB and ZiB from file size type](https://github.com/nushell/nushell/pull/9427)
- fdncred [updated ini dependency](https://github.com/nushell/nushell/pull/9426), and [updated dfr to polars 0.30.0](https://github.com/nushell/nushell/pull/9424), and [allow empty string arguments](https://github.com/nushell/nushell/pull/9420), and [allow paths to have brackets](https://github.com/nushell/nushell/pull/9416)
- FilipAndersson245 [changed global allocator to mimalloc, improving performance.](https://github.com/nushell/nushell/pull/9415), and [Changes HashMap to use aHash instead, giving a performance boost.](https://github.com/nushell/nushell/pull/9391)
- Mehrbod2002 [renamed uid to user column in ls --long](https://github.com/nushell/nushell/pull/9407)
- ja-cop [added "regex" search term to commands with regex functionality](https://github.com/nushell/nushell/pull/9402)
- amtoine [simplified the declaration of extra commands](https://github.com/nushell/nushell/pull/9398), and [added a comment note to the PR template about linking issues](https://github.com/nushell/nushell/pull/9392)
- AstrickHarren [fixed find puts extra cols into record](https://github.com/nushell/nushell/pull/9397), and [Add `zip-into-record` to std iter](https://github.com/nushell/nushell/pull/9395)
- tarunsamanta2k20 [completed the install command to install plugins #9342](https://github.com/nushell/nushell/pull/9357)
- Yethal [refactored test-runner to no longer require tests to be exported](https://github.com/nushell/nushell/pull/9355)
- zhiburt [bumped tabled to 0.12.1](https://github.com/nushell/nushell/pull/9341)
- stevenxxiu [merged `repl_buffer_state`, `repl_cursor_pos` into one mutex](https://github.com/nushell/nushell/pull/9031)

## Documentation

- hanjunghyuk created [Remove mentioning ZB and ZiB](https://github.com/nushell/nushell.github.io/pull/949)
- BrianLondon created [Modernize and add additional info to plugin tutorial](https://github.com/nushell/nushell.github.io/pull/948)
- Mehrbod2002 created [chore: add detail to breaking changes](https://github.com/nushell/nushell.github.io/pull/947)

## Nu_Scripts

- kachick created [Replace deprecated `hash base64` with `decode`](https://github.com/nushell/nu_scripts/pull/531), and [Replace deprecated `fetch` with `http get`](https://github.com/nushell/nu_scripts/pull/530)
- fdncred created [create readme.md with theme previews](https://github.com/nushell/nu_scripts/pull/519)
