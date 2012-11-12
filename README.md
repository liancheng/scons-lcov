SCons tool for `lcov` and `genhtml`
===================================

Run `lcov` and `genhtml` to generate HTML coverage report with [SCons](http://www.scons.org).

## How to use

Clone the repository:

    $ cd /your/local/repo
    $ git clone git://github.com/liancheng/scons-lcov.git

Set up your `site_scons` directory:

    $ mkdir -p ~/.scons/site_scons/site_tools

Set up SCons tools:

    $ cd ~/.scons/site_scons/site_tools
    $ ln -s /your/local/repo/scons-lcov/lcov
    $ ln -s /your/local/repo/scons-lcov/genhtml

Test your setup:

    $ cd /your/local/repo/scons-lcov/sample
    $ scons

If everything's OK, you may see the `html` directory where HTML report pages stay.
