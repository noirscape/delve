# delve - A simple terminal gopher client

This is a port of the delve gopher client to the Nintendo Switch. Requires Homebrew to run.

Has slight differences with the original delve, which are described below.

## Compiling

Make sure you have devKitPro installed, then run Make.

## License

GPLv3.

## Differences with the original delve

* Pager works as follows: 
  * Press the down key to show the next piece of information.
  * Press `-` to enter a command at any point.
* No support for command histories (incompatible with swkbd)
* Default config file is loaded from `/switch/delve/delve.conf`.
