![](indieweb-willow-brugh.jpg)
*Source: [Willow Brugh](https://www.flickr.com/photos/willowbl00/13199772894) - [BY-SA](https://creativecommons.org/licenses/by-sa/2.0/)*

# GitHub-Pages IndieWeb Quickstart

I was using [@miklb](https://github.com/miklb)'s [jekyll-indieweb](https://github.com/miklb/jekyll-indieweb), which this repository and the website it supports intend to expand upon. That theme is buggy and a new release is coming soon. You can see that implementation published at [infominer.id/indieweb-old](https://infominer.id/indieweb-old)


[![](https://imgur.com/LrC8gO8.png)](https://github.com/miklb/jekyll-indieweb/pull/25#issuecomment-494123723)


Now that I have a solid theme under me, I can experiment with webmentions and other features of indieweb, here. 

## Project Pages

Project Pages is Jekyll Template specifically geared towards collaborative science. For more information, click [here](https://github.com/projectpages/project-pages/wiki/).

## Nav Bar Jumbles

If you have seemingly random pages popping up on your Nav Bar recently, this is due to the fact that GitHub/Jekyll changed a fundemental rule they used to render pages. 

## CAUSE:
It used to be that if a markdown file didn't have `---` frontmatter at the beginning, it wasn't rendered as a page. This was changed very recently (like in the last 2 days) so that every markdown file anywhere no matter what gets rendered as a page.  

## FIX:

1) Go to:

`project-pages/plugin/projector/` or `yourreponame/plugin/projector/` and delete the `README.md` file. This can be done graphically for the non-Git-savvy by simply going to your:

GitHub account -> Your Profile -> Repositories -> Project-Pages/Your Repo -> Plugin -> projector 

and clicking on the files, then clicking on the "thrash can / delete this file" icon on the top right corner of the file.

2) Go to:

`project-pages/css/theme/` or `yourreponame/css/theme/` and delete the `README.md` file. This can be done graphically for the non-Git-savvy by simply going to your:

GitHub account -> Your Profile -> Repositories -> Project-Pages/Your Repo -> Plugin -> projector 

and clicking on the files, then clicking on the "thrash can / delete this file" icon on the top right corner of the file.
