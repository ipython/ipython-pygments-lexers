A [Pygments](https://pygments.org/) plugin for IPython code & console sessions

[IPython](https://ipython.org/) is an interactive Python shell. Among other features,
it adds some special convenience syntax, including `%magics`, `!shell commands`
and `help?`. This package contains lexers for these, to use with the Pygments syntax
highlighting package.

- The `ipython` lexer should be used where only input code is highlighted
- The `ipythonconsole` lexer works for an IPython session, including code,
  prompts, output and tracebacks.

These lexers were previously part of IPython itself (in `IPython.lib.lexers`),
but have now been moved to a separate package.