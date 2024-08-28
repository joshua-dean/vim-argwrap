# Vim-Argwrap

The source repo has permanently moved to [git.foosoft.net](https://git.foosoft.net/alex/vim-argwrap).

## Fork Additions
The argwrap logic works for the following braces: `()`, `[]`, `{}`.

It does not work for quotes, and the expansion is not trivial as 
`searchpairpos` requires `start` and `end` to be distinct.

This fork adds support for triple quotes (`"""`),
allowing it to wrap/unwrap python docstrings.