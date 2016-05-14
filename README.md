# <img src="https://github.com/chrisdone/intero/raw/master/images/intero.svg" height=25> intero [![Build Status](https://travis-ci.org/chrisdone/intero.png)](https://travis-ci.org/chrisdone/intero)

Complete interactive development program for Haskell

## Features

It's basically GHCi plus extra features. Those are:

* [Find uses of an identifier in a module.](https://github.com/chrisdone/intero/blob/master/src/test/Main.hs#L118)
* [Find definition of an identifier in a module.](https://github.com/chrisdone/intero/blob/master/src/test/Main.hs#L143)
* [Show the type of an expression or identifier](https://github.com/chrisdone/intero/blob/master/src/test/Main.hs#L82).
* [List all types of all expressions of all modules loaded.](https://github.com/chrisdone/intero/blob/master/src/test/Main.hs#L98)

Probably more to come.

## Requirements

The following dependencies are necessary:

* The `tinfo` and `ncurses` library.

  * Ubuntu and Debian users can install it using the following command:

          $ apt-get install libtinfo-dev
          $ apt-get install libncurses5-dev

## Installing

Standard:

    $ stack build intero

From source:

    $ git clone https://github.com/chrisdone/intero.git
    $ cd intero
    $ stack build intero

## Supported GHC versions

Intero been built and tested on the following GHC versions:

* GHC 7.8.4
* GHC 7.10.2
* GHC 7.10.3
