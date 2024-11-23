# This week in Nushell #274

## Nushell

- NotTheDr01ds [ensured default env/config values are always loaded](https://github.com/nushell/nushell/pull/14249)
- rikukiix [updated SHLVL (only when interactive) on startup](https://github.com/nushell/nushell/pull/14404)
- fdncred [added new --flatten parameter to the ast command](https://github.com/nushell/nushell/pull/14400), [allowed ps1 files to be executed without pwsh/powershell -c file.ps1](https://github.com/nushell/nushell/pull/14379), [updated uutils crates](https://github.com/nushell/nushell/pull/14371), and [fixed a formatting issue with the right prompt](https://github.com/nushell/nushell/pull/14357)
- Bahex [made CSV/TSV parsing more flexible](https://github.com/nushell/nushell/pull/14399), and [fixed name collision prevention in `group-by`](https://github.com/nushell/nushell/pull/14360)
- rfaulhaber [added MAC and IP address entries to `sys net`](https://github.com/nushell/nushell/pull/14389)
- devyn [turned IR compilation errors into fatal errors](https://github.com/nushell/nushell/pull/14388)
- WindSoilder [removed deprecated warnings](https://github.com/nushell/nushell/pull/14386), and [added `--default` flag to input command](https://github.com/nushell/nushell/pull/14374)
- ysthakur [avoided recomputing fuzzy match scores for speed](https://github.com/nushell/nushell/pull/13700), and [added utouch command from uutils/coreutils](https://github.com/nushell/nushell/pull/11817)
- zhiburt [improved table footers](https://github.com/nushell/nushell/pull/14380)
- 132ikl [updated pipeline formatting logic to use the `display_output` hook](https://github.com/nushell/nushell/pull/14361)
- michel-slm [bumped quick-xml to 0.37.0](https://github.com/nushell/nushell/pull/14354)
- sgvictorino [made command signature parsing more strict](https://github.com/nushell/nushell/pull/14309)
- IanManske [deprecated the `split-by` command](https://github.com/nushell/nushell/pull/14019)
- Kissaki [fixed some doc and code comment typos](https://github.com/nushell/nushell/pull/14366)
- schrieveslaach [bumped Calamine dependency](https://github.com/nushell/nushell/pull/14403)

## Documentation

- j1mr10rd4n [fixed typo in python example code in plugins.md](https://github.com/nushell/nushell.github.io/pull/1646)
- Kissaki [dropped experimental label from display_output hook](https://github.com/nushell/nushell.github.io/pull/1644), [used `in` for variable defined condition](https://github.com/nushell/nushell.github.io/pull/1643), [fixed absolute path example item text](https://github.com/nushell/nushell.github.io/pull/1640), [updated and simplified Escaping to the System Windows Note](https://github.com/nushell/nushell.github.io/pull/1639), [fixed and extended CMD.EXE START docs](https://github.com/nushell/nushell.github.io/pull/1638), [added missing cmd to nu command](https://github.com/nushell/nushell.github.io/pull/1637), [improved pipelines input output types documentation](https://github.com/nushell/nushell.github.io/pull/1636), and [added missing cmd to nu command](https://github.com/nushell/nushell.github.io/pull/1634)
- allan2 [added `--locked` flag to Cargo install](https://github.com/nushell/nushell.github.io/pull/1642)

## Nu_Scripts

- IanManske [fixed typos](https://github.com/nushell/nu_scripts/pull/982), and [edited release notes template and edit scripts](https://github.com/nushell/nu_scripts/pull/981)

## reedline

- sholderbach [set `Ctrl-J`/`\n` to `ReedlineCommand::Enter`](https://github.com/nushell/reedline/pull/855)
- NotTheDr01ds [added Newline keybindings](https://github.com/nushell/reedline/pull/854)

