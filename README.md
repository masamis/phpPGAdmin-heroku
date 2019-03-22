# phpPGAdmin-heroku

## Overview & Deescription

This is update for deploy phpPGAdmin to Heroku. The updates points are bellow:

- modify to store database connection information from ConfigVar(/conf/config.inc.php) <br /><br />
PG_HOST = host name (like foofoo.compute-1.amazonaws.com) <br />
PG_DEFAULTDB = database name <br /><br />
you can find the infomration on https://data.heroku.com/ settings -> Database Credentials
