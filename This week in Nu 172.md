# This week in Nushell #172


## Nushell

- webbedspace [reduced LOC by replacing several instances of `Value::Int {}`, `Value::Float{}`, `Value::Bool {}`, and `Value::String {}` with `Value::int()`, `Value::float()`, `Value::boolean()` and `Value::string()`](https://github.com/nushell/nushell/pull/7412), and [Allow `$env` and mutable records to be mutated by `=` (closes #7110)](https://github.com/nushell/nushell/pull/7318)
- merelymyself [ensured that errore in `else` are forwarded appropriately](https://github.com/nushell/nushell/pull/7411), and [fix external completions; add a caret when there is overlap](https://github.com/nushell/nushell/pull/7405), and [Add quotes to hash file autocomplete](https://github.com/nushell/nushell/pull/7398), and [Make `seq` return a `ListStream` where possible](https://github.com/nushell/nushell/pull/7367)
- sholderbach [added arbitrary base `math log`](https://github.com/nushell/nushell/pull/7409), and [Add `math tau`](https://github.com/nushell/nushell/pull/7408), and [Fix `math e` usage text](https://github.com/nushell/nushell/pull/7406)
- kubouch [fixed tab not working in vi editor mode](https://github.com/nushell/nushell/pull/7396)
- jntrnr [removed and/or from 'help operators'](https://github.com/nushell/nushell/pull/7388), and [Fix input redirect for externals](https://github.com/nushell/nushell/pull/7387), and [Add OneOf shape to fix `else`](https://github.com/nushell/nushell/pull/7385), and [Improve empty pipelines](https://github.com/nushell/nushell/pull/7383), and [Better errors when bash-like operators are used](https://github.com/nushell/nushell/pull/7241)
- rgwood [removed use of deprecated `actions-rs/cargo` GH action](https://github.com/nushell/nushell/pull/7375), and [Fix `watch` for block+closure split](https://github.com/nushell/nushell/pull/7374), and [Pin CI jobs to Ubuntu 20.04](https://github.com/nushell/nushell/pull/7359), and [Make SQLite queries cancellable](https://github.com/nushell/nushell/pull/7351), and [Improve error message for illegal filenames on Windows](https://github.com/nushell/nushell/pull/7348), and [Overhaul `schema` command, remove database name](https://github.com/nushell/nushell/pull/7344)
- WindSoilder [fixed semicolon doesn't work for some commands](https://github.com/nushell/nushell/pull/7373), and [fix `split list` when separater is the first element of list](https://github.com/nushell/nushell/pull/7355)
- stormasm [removed redundant code mentioning ToCsv](https://github.com/nushell/nushell/pull/7370)
- fdncred [bumped to dev build v0.72.2](https://github.com/nushell/nushell/pull/7360), and [add input_output_types() to `ansi gradient`](https://github.com/nushell/nushell/pull/7357), and [add background colors to the ansi command](https://github.com/nushell/nushell/pull/7312)
- raccmonteiro added a [`++=` appendAssign operator (#7346)](https://github.com/nushell/nushell/pull/7354)
- nibon7 fixed [kill: don't show signal example on windows](https://github.com/nushell/nushell/pull/7353)
- JohnJohnstone [fixed menus in default config](https://github.com/nushell/nushell/pull/7352)
- Kangaxx-0 [fixed `upsert` index of zero](https://github.com/nushell/nushell/pull/7350), and [Add comments for nu syntax shape](https://github.com/nushell/nushell/pull/7349)
- zhiburt [fixed an issue with showing the wrong row index](https://github.com/nushell/nushell/pull/7343)
- dbuch landed [Protocol: debug_assert!() Span to reflect a valid slice](https://github.com/nushell/nushell/pull/6806)


## Documentation

- rgwood [removed old features from install instructions](https://github.com/nushell/nushell.github.io/pull/693)

## Nu_Scripts


- jntrnr [switched to 'and' and 'or'](https://github.com/nushell/nu_scripts/pull/322)
- ehdevries [replaced deprecated operators in panache-git](https://github.com/nushell/nu_scripts/pull/321)
