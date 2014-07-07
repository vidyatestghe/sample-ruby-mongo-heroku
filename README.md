Ruby+MongoDB Heroku sample
==========================

This sample demonstrates how to setup continuous integration and deployment for a Sinatra+MongoDB project deployed on Heroku.

For sake of simplicity, this example does not use full-blown migration system (e.g. from ActiveRecord), but rather adds a
simple `db:migrate` Rake task to illustrate how it can be called from Shippable build script.

For more detailed documentation, please see Shippable's continuous deployment section: http://docs.shippable.com/en/latest/config.html#continuous-deployment