# Heroku Buildpack: MongoDB database-tools

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run mongo commands (http://www.mongodb.org/). <br/>
It installs MongoDB database-tools (like mongodump and mongoimport) for Linux environment (stack: heroku-20)

## Usage

Example usage:

    $ heroku create myapp --buildpack http://github.com/siesgstarena/heroku-buildpack-mongo.git
    $ git push heroku master

or:
$ heroku buildpacks:add http://github.com/siesgstarena/heroku-buildpack-mongo.git
