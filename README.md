# ParallelOperation

Parallel operation by using Tmux

## Installation

On Mac, you can install scripts by [Homebrew](https://github.com/mxcl/homebrew):

    $ brew install rcmdnk/rcmdnkpac/po

If you have [brew-file](https://github.com/rcmdnk/homebrew-file), add following lines to Brewfile:

    tap 'rcmdnk/rcmdnkpac'
    brew 'po'

then, do:

    $ brew file install

Or if you write like:

    tapall 'rcmdnk/rcmdnkpac'

and do `brew file install`, you will have all useful scripts in
[rcmdnkpac](https://github.com/rcmdnk/homebrew-rcmdnkpac).

You can also use an install script on the web like:

    $ curl -fsSL https://raw.github.com/rcmdnk/ParallelOperation/install/install.sh| sh

This will install scripts to `/usr/bin`
and you may be asked root password.

If you want to install other directory, do like:

    $ curl -fsSL https://raw.github.com/rcmdnk/ParallelOperation/install/install.sh|  prefix=~/usr/local/ sh

Or, simply download scripts (`bin/po`) and set where you like.

## Usage


## Thanks

This script was inspired by following blog post:

> [tmuxで複数サーバの同時オペレーション – NaviPlus Engineers' Blog](https://tech.naviplus.co.jp/2014/01/09/tmux%E3%81%A7%E8%A4%87%E6%95%B0%E3%82%B5%E3%83%BC%E3%83%90%E3%81%AE%E5%90%8C%E6%99%82%E3%82%AA%E3%83%9A%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3/)
