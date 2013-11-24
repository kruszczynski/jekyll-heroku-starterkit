jekyll-heroku-starterkit
========================

Jekyll on Heroku build with sprockets like assets pipeline and coffescript and sass compilation.

Running
-------

Here's a clean jekyll-heroku-starterkit on heroku [http://jekyll-starterkit.herokuapp.com/](http://jekyll-starterkit.herokuapp.com/).

Heroku
------

jekyll-heroku-starterkit is configured and bundled to work with Heroku without additional configuration, just create an application and push.

Assets
------

jekyll-heroku-starterkit uses jekyll-assets plugin. It's sprockets assets pipeline known from rails configured for Jekyll. For usage visit [https://github.com/ixti/jekyll-assets/8](https://github.com/ixti/jekyll-assets/8).

Dynopoker
---------

Heroku free dyno goes to sleep. [Dynopoker gem](https://github.com/kubenstein/dynopoker) runs a process that pings itself. All you need to do is change address in _plugins/dynopoke_config.rb.

Jekyll
------

As far as Jekyll is concerned - it's business as usual, for more info visit [Jekyll website](http://jekyllrb.com/).
