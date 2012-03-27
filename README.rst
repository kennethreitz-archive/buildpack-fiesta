Buildpack-Fiesta
================

A quick and dirty buildpack testing.

Written in bash, just because.


Usage
-----

Deploy a public app with a public buildpack::

    $ fiesta --app  git@github.com:kennethreitz/httpbin.git --buildpack git@github.com:heroku/heroku-buildpack-python.git

Deploy a local app with a public buildpack::

    $ fiesta --app ./httpbin --buildpack git@github.com:heroku/heroku-buildpack-python.git

Deploy a local app with a local buildpack::

    $ fiesta --app ./httpbin --buildpack ./python-buildpack

How?
----

It uploads your stuff to private gists.

Depends on:

- git
- curl
