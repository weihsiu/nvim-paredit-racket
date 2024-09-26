# Racket extension for nvim-paredit

Forked from https://github.com/ekaitz-zarraga/nvim-paredit-scheme

This is a Racket extension for [`nvim-paredit`][paredit].

[paredit]: https://github.com/julienvincent/nvim-paredit

Install it with any plugin manager you like and then:

``` lua
local paredit = require "nvim-paredit"
local racket  = require "nvim-paredit-racket"

racket.setup(paredit)
```
