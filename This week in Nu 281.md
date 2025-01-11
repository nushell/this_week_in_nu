# This week in Nushell #281

## Nushell

- blindFS [fixed PWD env_var for LSP](https://github.com/nushell/nushell/pull/14805), [added inlay hints of variable types and command params for LSP](https://github.com/nushell/nushell/pull/14802), [fixed unknown span for special variables `$in/$it`](https://github.com/nushell/nushell/pull/14789), [added document_symbols and workspace_symbols for LSP](https://github.com/nushell/nushell/pull/14770), and [implemented use of lsp-textdocument to handle utf16 position for LSP](https://github.com/nushell/nushell/pull/14742)
- cptpiepmatz [made `table` only check for `use_ansi_coloring` config value](https://github.com/nushell/nushell/pull/14798), [added `"whereis"` and `"get-command"` to `which` search terms](https://github.com/nushell/nushell/pull/14797), and [handled permission denied error at `nu_engine::glob_from`](https://github.com/nushell/nushell/pull/14679)
- fdncred [upgraded to Rust version 1.82](https://github.com/nushell/nushell/pull/14795), [fixed `stor reset` when there are foreign keys](https://github.com/nushell/nushell/pull/14772), and [improved closure serialization](https://github.com/nushell/nushell/pull/14698)
- 132ikl [removed file accidentally re-introduced by merge](https://github.com/nushell/nushell/pull/14785), [fixed extra newline on empty lists when $env.config.table.show_empty is set](https://github.com/nushell/nushell/pull/14766), [added newline to empty list output](https://github.com/nushell/nushell/pull/14758), [changed `PipelineData::into_value` to use internal `Value`'s span before passed in span](https://github.com/nushell/nushell/pull/14757), [fixed config reset to use scaffold config files](https://github.com/nushell/nushell/pull/14756), [prevented ndots expansion if prefixed with `./`](https://github.com/nushell/nushell/pull/14755), [added doccomments to `find` functions in EngineState and StateWorkingSet](https://github.com/nushell/nushell/pull/14750), [added flag to `debug profile` to output duration field as Value::Duration](https://github.com/nushell/nushell/pull/14749), and [added run-time type checking for command pipeline input](https://github.com/nushell/nushell/pull/14741)
- sholderbach [updated typos workflow to `1.29.4`](https://github.com/nushell/nushell/pull/14782)
- Bahex [enabled conditional `source` and `use` patterns by allowing `null` as a no-op module](https://github.com/nushell/nushell/pull/14773), [made small, backwards compatible enhancements to std](https://github.com/nushell/nushell/pull/14763), and [fixed nuon conversions of range values](https://github.com/nushell/nushell/pull/14687)
- NotTheDr01ds [converted Path to `list` in main and preserved case](https://github.com/nushell/nushell/pull/14764), and [removed deprecated commands](https://github.com/nushell/nushell/pull/14726)
- hustcer [prevented release workflow from triggering on nightly tags](https://github.com/nushell/nushell/pull/14803)
- dead10ck [expanded custom values on table display](https://github.com/nushell/nushell/pull/14760)
- userwiths [fixed root directory traversal issue](https://github.com/nushell/nushell/pull/14747)
- ysthakur [made custom completions inherit case_sensitive option from $env.config](https://github.com/nushell/nushell/pull/14738)
- WindSoilder [prevented auto cd from canonicalizing symbolic path](https://github.com/nushell/nushell/pull/14708)
- Chen1Plus [fixed wrong error message of `save` command on Windows](https://github.com/nushell/nushell/pull/14699)
- ChetanXpro [fixed handling of zero-size cursor in binary viewer for explore command](https://github.com/nushell/nushell/pull/14592)

## Documentation

- sholderbach [fixed `usage` to `description` in plugin documentation](https://github.com/nushell/nushell.github.io/pull/1743)
- emad-elsaid [corrected docs for emacsclient](https://github.com/nushell/nushell.github.io/pull/1742)
- NotTheDr01ds [removed deprecated/removed split-by command from Map table](https://github.com/nushell/nushell.github.io/pull/1741), and [removed "Edit this page" and contributors list from Command docs](https://github.com/nushell/nushell.github.io/pull/1729)
- jesper-olsen [updated using_modules.md](https://github.com/nushell/nushell.github.io/pull/1739), and [updated scripts.md](https://github.com/nushell/nushell.github.io/pull/1738)
- lodagro [fixed example typo in thinking_in_nu.md](https://github.com/nushell/nushell.github.io/pull/1736)
- maxim-uvarov [fixed typo in configuration.md `($nu.data-dir)/vendor/autoloads`](https://github.com/nushell/nushell.github.io/pull/1735)

## Nu_Scripts

- 132ikl [fixed `path with-parent` example output](https://github.com/nushell/nu_scripts/pull/1013), and [renamed path replace-extension to path with-extension, added with-stem and with-parent](https://github.com/nushell/nu_scripts/pull/1011)
- ehdevries [excluded prompt indicator in panache-git so users can choose their own](https://github.com/nushell/nu_scripts/pull/1012)
- Bahex [added `clip copy` and `clip paste`](https://github.com/nushell/nu_scripts/pull/1009)

