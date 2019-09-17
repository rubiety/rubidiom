Rubidiom, LLC
========

Simple static website for Rubidiom, LLC.

## Deploying

Hosting is handled by dokku as a static site with the [buildpack-nginx](https://github.com/dokku/buildpack-nginx) buildpack (specified in `.env`).

Configuration:

    NGINX_ROOT=build
