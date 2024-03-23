# The last 2 weeks in Nushell #239

(we were busy and missed last week's update, sorry)

## Nushell

- devyn made a LOT of improvements, mostly around plugins:
    - [introduced better generic errors for plugins (and perhaps scripts)](https://github.com/nushell/nushell/pull/12236)
    - [allowed plugins to set environment variables in their caller's scope](https://github.com/nushell/nushell/pull/12204)
    - [refactored `PluginCustomValue::render_to_base_value_in`](https://github.com/nushell/nushell/pull/12244)
    - [merged stream_example into the example plugin and cleaned up names](https://github.com/nushell/nushell/pull/12234)
    - [added `Value::recurse_mut()` to save duplicated code in `PluginCustomValue`](https://github.com/nushell/nushell/pull/12218)
    - [supported custom values in plugin examples](https://github.com/nushell/nushell/pull/12213)
    - [made more robustness improvements to plugin persistence tests](https://github.com/nushell/nushell/pull/12185)
    - [disabled plugin GC tests on macOS](https://github.com/nushell/nushell/pull/12177)
    - [reorganized plugin API around commands](https://github.com/nushell/nushell/pull/12170)
    - [added environment engine calls for plugins](https://github.com/nushell/nushell/pull/12166)
    - [made the plugin persistence GC delay test more reliable](https://github.com/nushell/nushell/pull/12153)
    - [synced with the plugin garbage collector when setting config](https://github.com/nushell/nushell/pull/12152)
    - [fixed an unused IntoSpanned warning in nu_parser::parse_keywords when 'plugin' feature not enabled](https://github.com/nushell/nushell/pull/12144)
    - [fixed locking soundness in PersistentPlugin](https://github.com/nushell/nushell/pull/12182)
    - [improved the error message for a plugin version mismatch](https://github.com/nushell/nushell/pull/12122)
    - [supported all custom value operations on plugin custom values](https://github.com/nushell/nushell/pull/12088)
    - [kept plugins persistently running in the background](https://github.com/nushell/nushell/pull/12064)
    - [added support for engine calls from plugins](https://github.com/nushell/nushell/pull/12029).
    - [improved handling of EOF in MsgPack deserializer](https://github.com/nushell/nushell/pull/12183)
    - [miscellaneous documentation fixes](https://github.com/nushell/nushell/pull/12266)
    - [refactored PipelineDataHeader ⇄ PipelineData](https://github.com/nushell/nushell/pull/12248)
    - [fixed a broken build by replacing value_string() straggler](https://github.com/nushell/nushell/pull/12237)
    - [added support for `into string for custom values`](https://github.com/nushell/nushell/pull/12231)
    - [made custom value type handling more consistent](https://github.com/nushell/nushell/pull/12230)
    - made EngineState clone cheaper with Arc on all heavy objects ([1](https://github.com/nushell/nushell/pull/12229), [2](https://github.com/nushell/nushell/pull/12242))
    - [fixed zip signature to mention closure input type](https://github.com/nushell/nushell/pull/12216)
    - [changed the ignore command to use drain() instead of collecting a value](https://github.com/nushell/nushell/pull/12120)

- fdncred [bumped the rust-toolchain to 1.75.0](https://github.com/nushell/nushell/pull/12258), and [removed stdlib logging environment variables](https://github.com/nushell/nushell/pull/12196).
- JoaoFidalgo1403 [fixed usage of the --tabs flag while converting to json](https://github.com/nushell/nushell/pull/12251).
- WindSoilder [removed the str escape-glob command](https://github.com/nushell/nushell/pull/12241), [cleaned cp tests](https://github.com/nushell/nushell/pull/12202), [removed test warnings](https://github.com/nushell/nushell/pull/12201), [fixed ls with an empty string](https://github.com/nushell/nushell/pull/12086), and [made closure in `do` command support default parameters and type checking](https://github.com/nushell/nushell/pull/12056).
- sholderbach [refactored source cache into the `CachedFile` struct](https://github.com/nushell/nushell/pull/12240), [updated contributor image generation with new upper bound](https://github.com/nushell/nushell/pull/12198), [bumped `arboard` from `3.3.0` to `3.3.2`](https://github.com/nushell/nushell/pull/12178), [responded to nightly clippy](https://github.com/nushell/nushell/pull/12174), [removed the rarely used std-lib issue template](https://github.com/nushell/nushell/pull/12173), [minor refactored in `to html`](https://github.com/nushell/nushell/pull/12172), [refactored benches for more command benchmarks](https://github.com/nushell/nushell/pull/12171), [included benchmarks in the CI clippy run](https://github.com/nushell/nushell/pull/12165), [bumped `iana-time-zone` due to yanked locked version](https://github.com/nushell/nushell/pull/12162), [removed outdated doccomment on `EngineState`](https://github.com/nushell/nushell/pull/12158), [disabled `fmt` feature of `polars(-core)`](https://github.com/nushell/nushell/pull/12151), [bumped `reedline` to dev (and `strum`)](https://github.com/nushell/nushell/pull/12150), [removed feat `extra`
and included it in default](https://github.com/nushell/nushell/pull/12140), and [restructured `nu-protocol` into more meaningful units](https://github.com/nushell/nushell/pull/11917).
- YizhePKU [fixed a missing parse error when extra tokens were given to let bindings](https://github.com/nushell/nushell/pull/12238), and [fixed
inaccurate sleep duration](https://github.com/nushell/nushell/pull/12235).
- IanManske [used the rest argument in `export use` to match `use`](https://github.com/nushell/nushell/pull/12228), [fixed wrong stdout with `e>|`](https://github.com/nushell/nushell/pull/12227), [fixed `$in` value for `insert` closure](https://github.com/nushell/nushell/pull/12209), [fixed ignored clippy lints](https://github.com/nushell/nushell/pull/12160), [fixed clippy lints](https://github.com/nushell/nushell/pull/12139), and
[overhauled IO and redirection](https://github.com/nushell/nushell/pull/11934).
- sarubo [adjusted permissions using `umask` in `mkdir`](https://github.com/nushell/nushell/pull/12207).
- thomassimmer [fixed a histogram error message](https://github.com/nushell/nushell/pull/12197).
- zhiburt [used hex-dump for binary data in nu-explore](https://github.com/nushell/nushell/pull/12184).
- Tastaturtaste [used the system clipboard only for explicit copy/paste operations, addressing issue 11907](https://github.com/nushell/nushell/pull/12179).
- ysthakur [canonicalized each component of config files](https://github.com/nushell/nushell/pull/12167), [canonicalized the config dir](https://github.com/nushell/nushell/pull/12136), [updated tests Playground](https://github.com/nushell/nushell/pull/12134), and [used XDG_CONFIG_HOME before the default config directory](https://github.com/nushell/nushell/pull/12118).
- nils-degroot [improved the error message for `into sqlite` with empty records](https://github.com/nushell/nushell/pull/12149).
- kubouch [refactored nu-check](https://github.com/nushell/nushell/pull/12137), and [continued to experiment with the debugger](https://github.com/nushell/nushell/pull/11441).
- hustcer [upgraded actions/checkout and softprops/action-gh-release](https://github.com/nushell/nushell/pull/12135), [fixed Nu release packages
after upgrading to Nu v0.91](https://github.com/nushell/nushell/pull/12119), and [upgraded Nu to v0.91 for release and nightly workflow](https://github.com/nushell/nushell/pull/12114).
- rgwood [fixed up ctrl+C handling in `into_sqlite`](https://github.com/nushell/nushell/pull/12130).
- NowackiPatryk [fixed unexpected sqlite insert behavior (attempt 2)](https://github.com/nushell/nushell/pull/12128).
- wellweek [removed a repetitive word](https://github.com/nushell/nushell/pull/12117).
- FilipAndersson245 [dived into extra benchmarks](https://github.com/nushell/nushell/pull/12025).
- dannou812 [fixed `to json -r` not removing whitespaces](https://github.com/nushell/nushell/pull/11948).
- rtpg [allowed for stacks to have parents](https://github.com/nushell/nushell/pull/11654).
- lavafroth [used environment variables to prevent the command_not_found from recursing](https://github.com/nushell/nushell/pull/11090).

## Documentation

- IanManske created [Edit release notes](https://github.com/nushell/nushell.github.io/pull/1308)
- qdm12 created [fix(files.md): override Cargo.toml in example](https://github.com/nushell/nushell.github.io/pull/1307)
- devyn created [Release notes for 0.92.0 for @devyn so far](https://github.com/nushell/nushell.github.io/pull/1306), and [Plugin command api doc updates](https://github.com/nushell/nushell.github.io/pull/1305), and [Env var plugin engine calls docs](https://github.com/nushell/nushell.github.io/pull/1302), and [Custom value ops documentation](https://github.com/nushell/nushell.github.io/pull/1300), and [Add "Contrib" link to the navbar](https://github.com/nushell/nushell.github.io/pull/1295), and [Documentation for plugin persistence](https://github.com/nushell/nushell.github.io/pull/1291), and [Documentation for engine calls](https://github.com/nushell/nushell.github.io/pull/1290)
- fdncred created [a few more tweaks](https://github.com/nushell/nushell.github.io/pull/1304), and [some formatting tweaks to the language guide](https://github.com/nushell/nushell.github.io/pull/1303)
- gdennie created [ensure showing of back ticks in <code />  block example](https://github.com/nushell/nushell.github.io/pull/1299)
- zerfix created [Document dynamic command arguments](https://github.com/nushell/nushell.github.io/pull/1298)
- jweckman created [Update plugins.md (#12146)](https://github.com/nushell/nushell.github.io/pull/1297)
- ysthakur created [Add info on XDG_CONFIG_HOME](https://github.com/nushell/nushell.github.io/pull/1296)
- sholderbach created [Remove feature `extra` detection from make_docs.nu](https://github.com/nushell/nushell.github.io/pull/1294), and [Fix release note toc](https://github.com/nushell/nushell.github.io/pull/1293)
- remmycat created [Add cookbook chapter on how to read env vars from foreign shell scripts](https://github.com/nushell/nushell.github.io/pull/1292)
- Gremious created [Clarify pipeline arguments/output in book](https://github.com/nushell/nushell.github.io/pull/1287)
- edhowland created [Added missing types in Basic Types section.](https://github.com/nushell/nushell.github.io/pull/1285)

## Nu_Scripts

- texastoland created [[stdlib-candidate] Clean up `str append`/`prepend` a little](https://github.com/nushell/nu_scripts/pull/797), and [Refactor toolkit.nu](https://github.com/nushell/nu_scripts/pull/791), and [Refactor stdlib-candidate for nupm](https://github.com/nushell/nu_scripts/pull/790), and [[stdlib-candidate] `set-env`](https://github.com/nushell/nu_scripts/pull/787)
- AucaCoyan created [:sparkles: add `gh gist` and gh repo `list` and `view`](https://github.com/nushell/nu_scripts/pull/794), and [:sparkles: add `flutter` completions](https://github.com/nushell/nu_scripts/pull/792), and [:bug: fix more parser errors](https://github.com/nushell/nu_scripts/pull/783), and [:bug: fix a couple of parser errors](https://github.com/nushell/nu_scripts/pull/782), and [:sparkles: `clone all` script](https://github.com/nushell/nu_scripts/pull/781), and [:bug: fix `scoop` completinos (an extra `)`](https://github.com/nushell/nu_scripts/pull/780), and [✨ add a `nu-check` verification CI](https://github.com/nushell/nu_scripts/pull/771)
- fnuttens created [Add chezmoi aliases](https://github.com/nushell/nu_scripts/pull/788)
- fj0r created [standardized parameter naming for `--help` and fix regex capture](https://github.com/nushell/nu_scripts/pull/786), and [nu-complete docker containers: show all containers](https://github.com/nushell/nu_scripts/pull/778)
- neur1n created [fix: update modules/virtual_environments/nu_msvs to work with nushell 0.91.0](https://github.com/nushell/nu_scripts/pull/784)

## reedline

- fdncred created [Revert "Move left when exiting insert mode"](https://github.com/nushell/reedline/pull/773)
- sholderbach created [Bump version of `strum`/`strum_macros`](https://github.com/nushell/reedline/pull/768)
- Tastaturtaste created [Use the OS clipboard only for explicit cut/copy/paste operations](https://github.com/nushell/reedline/pull/761)

## Nana

- cablehead created [fix: collect LazyRecords before attempting to serialize them](https://github.com/nushell/nana/pull/80)
