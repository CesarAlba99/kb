---
author: omaralba
title: Bundler
date: 25-05-2025
tags: [ruby]
---

# Bundler

Bundler is a tracker of dependencys, provides a consist environment for Ruby
projects by tracking and installing the exact gems and versions that are needed.

For example, if we have a project called TODO, then we should use Bundler to
configure all the versions that we are going to use, we don't have to worry
about the versions, Bundler will install the versions used in that specific
project. Thats why we should use bundler since the beggining of our project. 

See: <https://bundler.io/guides/getting_started.html#getting-started>

## Bundler in my projects

To use bundler in a project we have to have installed Bundler, then located in
the root of the project we create a new file called Gemfile, inside of it we
have to add the source of the gems, usually is <https://rubygems.org>, but it
can be different if necessary, we can add the versions needed for our project 
or simply specify the name of the gem.

Then we have to use bundle install, and bundler will get the necessary gems,
automatically bundler will create a Gemfile.lock file.

## Add a new gem

We can add only the gem in the gemfile like gem 'rspec', but also we can do it
from the terminal using bundle add gemName, and this will add it in the Gemfile,
to actually get the gem we have to run bundle install. 

See: <https://bundler.io/guides/gemfile.html>

