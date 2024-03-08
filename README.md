# Heroku buildpack: MongoDB

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run mongo commands (http://www.mongodb.org/).

It installs MongoDB 7.0 for Ubuntu 20.04 from [https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu2004-7.0.0.tgz](https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu2004-7.0.0.tgz) 

Usage
-----

Example usage:

    $ heroku create myapp --buildpack http://github.com/Lendix/heroku-buildpack-mongo.git
    $ git push heroku master
    
or:

    $ heroku buildpacks:add http://github.com/Lendix/heroku-buildpack-mongo.git
