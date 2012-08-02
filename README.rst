Buildpack-Fiesta
================

**Deprecated for ddollar/anvil**

A quick and dirty buildpack testing.

Written in bash, just because.


Usage
-----

Deploy a public app with a public buildpack::

    $ fiesta git@github.com:kennethreitz/httpbin.git git@github.com:heroku/heroku-buildpack-python.git

Deploy a local app with a public buildpack::

    $ fiesta ./httpbin git@github.com:heroku/heroku-buildpack-python.git

Deploy a local app with a local buildpack::

    $ fiesta ./httpbin ./python-buildpack

How?
----

It uploads your stuff to private gists.

Depends on:

- git
- curl
