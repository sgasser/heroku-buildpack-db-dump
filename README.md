Heroku buildpack: MySQL + MongoDB
========================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for heroku apps, that require msyql and mongodb binaries on the dynos itself. The buildpack is supposed to be a supplement to the existing buildpacks available.

Usage
-----

Example usage:

    $ heroku buildpacks:add https://github.com/sgasser/heroku-buildpack-mysql-mongodb

    $ git push heroku master
