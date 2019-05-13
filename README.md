Heroku buildpack: Logstash
==================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [Logstash](https://www.elastic.co/products/logstash).

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack http://github.com/evosystem-jp/heroku-buildpack-logstash

# or if your app is already created:
$ heroku buildpacks:add http://github.com/evosystem-jp/heroku-buildpack-logstash

$ git push heroku master
```