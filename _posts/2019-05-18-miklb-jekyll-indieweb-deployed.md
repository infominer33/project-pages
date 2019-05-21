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

[**UPDATE**] I'm testing a different theme, since that one doesn't really work and I can always switch later, since I don't think I really need this [project-pages](https://github.com/projectpages/project-pages/) theme personally, but I'm pretty sure I know someone who does.