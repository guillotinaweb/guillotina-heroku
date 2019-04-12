# Guillotina-heroku

Guillotina is the only full-featured Python AsyncIO REST Resource Application Server designed for high-performance, horizontally scaling solutions

Read more at [Guillotina](https://guillotina.readthedocs.io/en/latest/) 

Deploy Guillotina on Heroku with Postgres in one clicks

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/guillotinaweb/guillotina-heroku)


## Overridding configuration

You can add configuration variables, see https://guillotina.readthedocs.io/en/latest/developer/commands.html#overridding-configuration

Env variables you should customize for every deployment:

- G_root_user__password
- G_jwt__secret