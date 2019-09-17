Rubidiom, LLC
========

Simple static website for Rubidiom, LLC.

## Deploying

Hosting is handled by dokku as a static site with the [buildpack-nginx](https://github.com/dokku/buildpack-nginx) buildpack:

    $ dokku buildpacks:add rubidiom https://github.com/dokku/buildpack-nginx.git

We use [middleman-deploy](https://fullstackstanley.com/read/using-middleman-with-dokku-updated) to push to dokku.
