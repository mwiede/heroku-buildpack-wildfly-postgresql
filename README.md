# heroku-buildpack-wildfly-postgresql

This is a [Heroku Buildpack](https://devcenter.heroku.com/articles/buildpacks) for adding postgresql Driver to [Wildfly AS](http://wildfly.org) as a module.

## Usage

1. Add a WildFly buildpack, then add this buildpack:

```console
$ heroku buildpacks:clear
$ heroku buildpacks:add heroku/java
$ heroku buildpacks:add https://github.com/mwiede/heroku-buildpack-wildfly
$ heroku buildpacks:add https://github.com/mwiede/heroku-buildpack-wildfly-postgresql
```

2. Then deploy your Maven project
