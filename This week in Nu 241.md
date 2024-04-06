# This week in Nushell #241


## Nushell

- ysthakur [fixed a bug by canonicalizing XDG_CONFIG_HOME before comparing to config_dir()](https://github.com/nushell/nushell/pull/12420)
- devyn [added BufWriter to ChildStdin on the plugin interface](https://github.com/nushell/nushell/pull/12419), [fixed deadlock on PluginCustomValue drop](https://github.com/nushell/nushell/pull/12418), [fixed some of the tests in `tests::shell`](https://github.com/nushell/nushell/pull/12417), [improved handling of custom values in plugin examples](https://github.com/nushell/nushell/pull/12409), [fixed #12391: mkdir uses process startup directory instead of current script directory](https://github.com/nushell/nushell/pull/12394), [fixed testing.nu import of std log](https://github.com/nushell/nushell/pull/12392), and [made drop notification timing for plugin custom values more consistent](https://github.com/nushell/nushell/pull/12341)
- friaes [fixed a bug where encode returns an error with utf-16le and utf-16be encodings](https://github.com/nushell/nushell/pull/12411)
- SylvanBrocard [updated the list of supported formats in the `dfr open` error message](https://github.com/nushell/nushell/pull/12408)
- IanManske [refactored `Range`](https://github.com/nushell/nushell/pull/12405), [fixed hooks on 0.92.0](https://github.com/nushell/nushell/pull/12383), and [fixed `mkdir` umask](https://github.com/nushell/nushell/pull/12354)
- sholderbach [tweaked release workflow after `0.92.1` lessons](https://github.com/nushell/nushell/pull/12401), [made the default config conservative about clipboard](https://github.com/nushell/nushell/pull/12385), [bumped `crate-ci/typos` and fixed typos](https://github.com/nushell/nushell/pull/12381), and [bumped the Nu version for `0.92.0` release](https://github.com/nushell/nushell/pull/12349)
- merelymyself [prevented `select` (negative number) from hanging shell](https://github.com/nushell/nushell/pull/12393), [prevented parser from parsing variables as units](https://github.com/nushell/nushell/pull/12378), [made `view source` more robust](https://github.com/nushell/nushell/pull/12359), and [made auto-cd check for permissions](https://github.com/nushell/nushell/pull/12342)
- deepanchal [fixed a simple typo in commandline_.rs](https://github.com/nushell/nushell/pull/12387)
- kubouch [added missing crate description to nu-plugin-test-support](https://github.com/nushell/nushell/pull/12368) and [bumped reedline to 0.31.0](https://github.com/nushell/nushell/pull/12366)
- fdncred [bumped the Python plugin's nushell version](https://github.com/nushell/nushell/pull/12367)
- eopb [fixed stop suggesting `--trash` when already enabled (issue #12361)](https://github.com/nushell/nushell/pull/12362)
- Jasha10 [fixed dead links in CONTRIBUTING.md](https://github.com/nushell/nushell/pull/12353)

## Documentation

- hustcer [upgraded vuepress and related plugins](https://github.com/nushell/nushell.github.io/pull/1341), and [removed doc for `str escape-glob` command](https://github.com/nushell/nushell.github.io/pull/1331)
- douyacai911 [updated README.md](https://github.com/nushell/nushell.github.io/pull/1339)
- thinkryan [updated plugins.md](https://github.com/nushell/nushell.github.io/pull/1338)
- devyn [created Release notes 0.92.1 + breaking change](https://github.com/nushell/nushell.github.io/pull/1337), [fixed testing example](https://github.com/nushell/nushell.github.io/pull/1335), [created release notes for nushell/nushell#12184 (binary data in explore)](https://github.com/nushell/nushell.github.io/pull/1329), [added/sorted breaking changes, full changelog for 0.92 release notes](https://github.com/nushell/nushell.github.io/pull/1324), and [made more minor changes to the 0.92 release notes](https://github.com/nushell/nushell.github.io/pull/1323)
- IanManske [created Release notes for `0.92.1`](https://github.com/nushell/nushell.github.io/pull/1336), [cleaned up 0.92.0 release notes](https://github.com/nushell/nushell.github.io/pull/1326), [edited release notes for 0.92.0](https://github.com/nushell/nushell.github.io/pull/1322), [updated workflow actions](https://github.com/nushell/nushell.github.io/pull/1320), and [created Release notes for `0.92`](https://github.com/nushell/nushell.github.io/pull/1301)
- tommorris [made a stylistic fix in loading_data.md NUON section](https://github.com/nushell/nushell.github.io/pull/1333)
- b-van-b [updated http.md](https://github.com/nushell/nushell.github.io/pull/1332)
- github-actions[bot] [compressed Images](https://github.com/nushell/nushell.github.io/pull/1330)
- kubouch [fixed minor version 0.92.0](https://github.com/nushell/nushell.github.io/pull/1328), [filled in Hall of Fame; added `debug profile` to new commands](https://github.com/nushell/nushell.github.io/pull/1325), and [added debugger note](https://github.com/nushell/nushell.github.io/pull/1321)
- sholderbach [created stefan release note](https://github.com/nushell/nushell.github.io/pull/1327)
- texastoland [added category backlinks](https://github.com/nushell/nushell.github.io/pull/1312)

## Nu_Scripts

- kubouch [added nu-plugin-test-support to release script](https://github.com/nushell/nu_scripts/pull/810)
- sholderbach [bumped version in the python plugin example as well](https://github.com/nushell/nu_scripts/pull/809)
- cptpiepmatz [added `from env`](https://github.com/nushell/nu_scripts/pull/808)
- csc530 [added op (1password cli) completions](https://github.com/nushell/nu_scripts/pull/807)
- fj0r [created utils of history with sqlite](https://github.com/nushell/nu_scripts/pull/779)

## reedline

- sholderbach [bumped version for `0.31.0` release](https://github.com/nushell/reedline/pull/780)
