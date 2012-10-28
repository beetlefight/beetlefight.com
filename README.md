Installation
============
Overview: Install ruby, rvm, create a gemset, install gems, start up.

    rvm use 1.9.2
    rvm gemset create beetlefight.com
    rvm gemset use beetlefight.com
    gem install bundler
    bundle

Running
=======

    ruby website.rb
    
    # or install "shotgun" by removing commented out entry in Gemfile
    bundle
    shotgun
  