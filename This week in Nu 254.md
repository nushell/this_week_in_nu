# This Week in Nushell #254

## Nushell

- ysthakur [fixed the variable completion sort order](https://github.com/nushell/nushell/pull/13306) and [forced completers to sort in fetch()](https://github.com/nushell/nushell/pull/13242)
- devyn [preserved attributes on external ByteStreams](https://github.com/nushell/nushell/pull/13305)
- lavafroth [fixed exotic types to return float on division and self on modulo](https://github.com/nushell/nushell/pull/13301) and [replaced `unfold` with `from_fn` for the generate command](https://github.com/nushell/nushell/pull/13299)
- fdncred [changed duration mod duration to duration instead of float](https://github.com/nushell/nushell/pull/13300), [created a better error message when saving fails](https://github.com/nushell/nushell/pull/13290), and [updated uutils crate versions](https://github.com/nushell/nushell/pull/13285)
- cablehead [removed the deprecated `register` command](https://github.com/nushell/nushell/pull/13297)
- WindSoilder [ensured errors in examples don't show results](https://github.com/nushell/nushell/pull/13296)
- rgwood [limited drilling down inside `explore`](https://github.com/nushell/nushell/pull/13293)
- kubouch [made Span ID Refactor (Step 2): Make Call SpanId-friendly](https://github.com/nushell/nushell/pull/13268) and then [reverted that change while we fix up some bugs](https://github.com/nushell/nushell/pull/13292) 
- hqsz [supported default offset with the dateformat option](https://github.com/nushell/nushell/pull/13289)
- ayax79 [checked if the cache is empty before enabling GC and added more logging](https://github.com/nushell/nushell/pull/13286), [added the ability to set content-type metadata with `metadata set`](https://github.com/nushell/nushell/pull/13284), and [allowed using pipeline data for HTTP post|put|patch|delete commands](https://github.com/nushell/nushell/pull/13254)
- IanManske [fixed clippy lint](https://github.com/nushell/nushell/pull/13277)
- alex-tdrn [skipped decoration lines for `detect columns --guess`](https://github.com/nushell/nushell/pull/13274)
- NotTheDr01ds [removed the deprecated `--numbered` flag from `for`](https://github.com/nushell/nushell/pull/13239)

## Documentation

- cablehead [removed the deprecated register command](https://github.com/nushell/nushell.github.io/pull/1467)
- monadix [corrected a minor spelling mistake](https://github.com/nushell/nushell.github.io/pull/1466)
- opeik [fixed a broken `$env.PATH` example](https://github.com/nushell/nushell.github.io/pull/1464)
- f3wenbo [fixed the case-sensitive option for `str contains`](https://github.com/nushell/nushell.github.io/pull/1463)

## Nu_Scripts

- amtoine [added a "nuenv" hook](https://github.com/nushell/nu_scripts/pull/889) and [introduced "toolkit" and "startup times" hooks](https://github.com/nushell/nu_scripts/pull/888)
- 1adept [updated `just-completion` from "export def" to "export extern"](https://github.com/nushell/nu_scripts/pull/860)

## Reedline

- adamschmalhofer [added a vi visual mode](https://github.com/nushell/reedline/pull/800)
- ysthakur [made menus process events before updating working details](https://github.com/nushell/reedline/pull/799)
- YizhePKU [added PWD to the `Reedline` state](https://github.com/nushell/reedline/pull/796)
- Jiogo18 [fixed column menu alignments with special characters using width()](https://github.com/nushell/reedline/pull/794)
