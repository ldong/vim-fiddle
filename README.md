# README

This is a fork of [Vim-fiddle](https://github.com/mharju/vim-fiddle)

To use, just clone this repository and type::

`./fiddle.sh`

The script creates a new fiddling directory, starts up MVIM and the WSGI-server with Bottle Framework.

Use ``<Leader>r`` to compile and open the file in browser or refresh it. 

Set ``g:fiddle_browser`` to the default browser you are having or leave it as is to use Google Chrome.

Check out ``fiddle.sh`` for configuration options such as VIM executable name and the directory where to put the fiddles
in. **Note:** if you use Rooter or a plugin that changes the current working directory, this script might not work.

## Screenshot

image:: http://play.taiste.fi/stuf/vim-fiddle.png

## Requirements

* Python
* [SASS](http://sass-lang.com/)

JS Libraies: 

1. jquery 1.11

2. Underscore 1.8.3

# License
MIT
