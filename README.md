bawi.org
========

Setting up development environment on Mac
-----------------------------------------

1. https://toolbelt.heroku.com/
2. https://rvm.io/
3. http://postgresapp.com/

```
$ rvm install 1.9.3 --default
$ gem install pg -- --with-pg-config=/Applications/Postgres.app/Contents/MacOS/bin/pg_config
$ git clone git@github.com:bawi/bawi.org.git
$ cd bawi.org
$ bundle
```
