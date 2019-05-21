---
layout: post
title: "Webmentions - Look Ma, No Hands!"
description: "A try at Using Webmentions."
date: "2019-05-19"
tags: indieweb github-pages resources github jekyll static-sites
subtitle: "A first attempt at using webmentions."
permalink: webmentions/
category: indieweb
---

Welcome!

The short version of how I got here:

Create a (free) GitHub personal access token:

![](https://imgur.com/IuHdqcCl.png)

It needs the `repo` scope.

![](https://imgur.com/b4G9F1rl.png)

Once I got my access token, I forked:

* [bmann/webpage-webmentions](https://github.com/bmann/webpage-webmentions) - Turnkey to heroku rendition of [voxpelli/webpage-webmentions](https://github.com/voxpelli/webpage-webmentions) (also Free)

![](https://imgur.com/5Tze7dC.png)

Click Deploy to heroku:

it's pretty straightforward... just make sure to format the address like so:

* [infomicro.herokuapp.com/](https://infomicro.herokuapp.com/)

Also free, and if you don't feel like doing this part, the first 10 people who try to can sign up through my endpoint at above address.

## Now What?

well, I followed a few other steps besides this:

```

	<link href="https://micro.blog/infominer" rel="me" />
    <link rel="token_endpoint" href="https://tokens.indieauth.com/token">
	<link rel="authorization_endpoint" href="https://indieauth.com/auth">
	<link rel="micropub" href="https://infomicro.herokuapp.com/api/webmention" />
	<link href="https://instagram.com/infominer33" rel="me">
	<link href="https://infominer.id" rel="me"/>
	<link rel="webmention" href="https://infomicro.herokuapp.com/api/webmention" />

```

As you can see, I signed up w:

* [micro.blog](https://micro.blog), and am self-hosted, so that's free.
* [indieauth.com](https://indieauth.com) (also free)
* [ownyourgram.com](https://ownyourgram.com/) - Even if you don't plan to use insta, go thru the steps here will help, if you are stuck.

## The Fun Stuff

<script id="webmention-hosted">
(function () {
var sn = document.createElement("script"), s = document.getElementsByTagName("script")[0], url;
url = document.querySelectorAll ? document.querySelectorAll("link[rel~=canonical]") : false;
url = url && url[0] ? url[0].href : false;
sn.type = "text/javascript"; sn.async = true;
sn.src = "//infomicro.herokuapp.com/api/embed?url=" + encodeURIComponent(url || window.location);
s.parentNode.insertBefore(sn, s);
}());
</script>