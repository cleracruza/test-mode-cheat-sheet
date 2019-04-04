# test-mode-cheat-sheet

Cheat sheet for the test-mode mode of TipToi pens.

* [Motivation](#motivation)
* [Installation](#installation)
* [Questions/Support](#questionssupport)

[![Build Status](https://travis-ci.org/cleracruza/test-mode-cheat-sheet.svg?branch=master)](https://travis-ci.org/cleracruza/test-mode-cheat-sheet)

## Motivation

When trying to debug your projects, it is often helpful to see which
OID the pen scans. TipToi pens come with a test mode that does just
that by reading out the scanned OIDs (although in Chinese). While
documentation of that mode [is available](https://github.com/entropia/tip-toi-reveng/wiki/Firmware#test-mode),
having to look for it again and again along with translation of
Chinese digits is cumbersome. So we collect all the needed information
in a single cheat sheet.

## Installation

* Install [`tttool`](https://github.com/entropia/tip-toi-reveng)
* Install the requirements for [`ttbox`](https://github.com/cleracruza/ttbox)
* Clone this repository and make sure to init the submodules:
```
git clone --recursive https://github.com/cleracruza/test-mode-cheat-sheet.git
```
* Switch to the cloned directory `cd test-mode-cheat-sheet`
* Run `make` to build the SVGs with OIDs.
* Print the SVGs with OIDs on a 1200dpi printer (`test-mode-cheat-sheet-de-with-oids.svg` is the German variant, `test-mode-cheat-sheet-en-with-oids.svg` is the English variant)
* Follow the printed cheat sheet to put your pen into test mode.
* Tip on OIDs (from books or your own projects) to hear the OID read out. The pronounciation printed on the cheat sheet will help you to understand the numbers. When in doubt, tip on the numbers on the cheat sheet to compare the read-outs.

## Questions/Support

If you run into issues or have questions, please file a ticket at [GitHub's issue tracker](https://github.com/cleracruza/test-mode-cheat-sheet/issues/new)
