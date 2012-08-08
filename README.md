# GHC plugin for loop unrolling

This plugin gives an example of defining a compiler plugin for GHC.
You mark functions with annotations which the compiler the unrolls or
peels to some threshold.

[travis-ci.org](http://travis-ci.org) results: [![Build Status](https://secure.travis-ci.org/thoughtpolice/unroll-ghc-plugin.png?branch=master)](http://travis-ci.org/thoughtpolice/unroll-ghc-plugin)

[Homepage][main page].

# Installation

Install the latest version of the plugin from Hackage (requires GHC 7.4.1):

    $ cabal install unroll-ghc-plugin

# Join in

File bugs in the GitHub [issue tracker][].

Master [git repository][gh]:

* `git clone https://github.com/thoughtpolice/unroll-ghc-plugin.git`

There's also a [BitBucket mirror][bb]:

* `git clone https://bitbucket.org/thoughtpolice/unroll-ghc-plugin.git`

# Authors

See [AUTHORS.txt](https://raw.github.com/thoughtpolice/unroll-ghc-plugin/master/AUTHORS.txt).

# License

BSD3. See `LICENSE.txt` for terms of copyright and redistribution.

[main page]: http://thoughtpolice.github.com/unroll-ghc-plugin
[issue tracker]: http://github.com/thoughtpolice/unroll-ghc-plugin/issues
[gh]: http://github.com/thoughtpolice/unroll-ghc-plugin
[bb]: http://bitbucket.org/thoughtpolice/unroll-ghc-plugin
