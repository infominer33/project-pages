---
layout: post
title:  "Jekyll Indieweb Deployed!"
date:   "2019-05-19"
categories: 
  - jekyll 
  - indieweb
  - update
og_image: https://infominer.id/indieweb/indieweb-willow-brugh.jpg
---

Welcome to an instance of [@miklb](https://github.com/miklb)'s [jekyll-indieweb](https://github.com/miklb/jekyll-indieweb).

To get to this point, I forked the repo, changed over to the `gh-pages` branch and ran `bundle update`, `bundle install`, and `bundle exec jekyll serve`.

Locally, it built beautifully without changing anything, but I got a warning to change the config file's reference of gems to plugins.

Once I pushed the updated `Gemfile.lock` and the references to gems in the config file, it WORKS!!!! :D

From there, I followed instructions from [@miklb](https://github.com/miklb)'s [jekyll-indieweb](https://github.com/miklb/jekyll-indieweb)'s post:

> The built in support is for Voxpelli's [webmention end point](https://webmention.herokuapp.com).

I registered there, and put `webmentions: yes` in [_config.yml](/_config.yml)

I will offer you a word of caution, this project in its current state is finnicky, and I find that [@miklb](https://twitter.com/miklb) is releasing a new version soon.

[![](https://imgur.com/LrC8gO8.png)](https://github.com/miklb/jekyll-indieweb/pull/25#issuecomment-494123723)

Once I got it running (this time) I am building every change locally to make sure it's deploying, since even change of parenthesis in config.yml can break it.

For the most part I'm just going to use this as a base for my IndieWeb Research, while I wait for Jekyll Indieweb v2.