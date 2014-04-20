# Heroku Buildpack: Ø

This repo is forked from the origin at https://github.com/ryandotsmith/null-buildpack.

Use it if you need Heroku to execute a binary AND take the java.runtime.version in System.properties into account.

## Usage

$ heroku config:add BUILDPACK_URL=https://github.com/gregross/jdk-only-buildpack.git
