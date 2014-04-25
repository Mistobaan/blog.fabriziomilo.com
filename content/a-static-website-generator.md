Title: Features of a Static Web Generator
date: 2014-4-30 10:20
tags: web, general
category: Web
slug: first-contact
author: Fabrizio Milo
summary: Brief description of what this is all about

# Static Web Site Generators

I finally decide to just do it and start typing down all my 
awesome ideas.
My main blocker so far to not publish a blog was that, I 
did not have a good experience with online blogging services.
My personal requirements were:

* Be able to write simple text code 
* Be able to auto-generate all the rest

Shopping Around the web I ended up on these [list of active github projects](http://staticsitegenerators.net)

I have been a long term lover of Python, but my favorite language right now
is [Golang](http://golang.org)

I contributed a few patched to the [hugo project](http://github.com/spf13/hugo)

But I needed something with more features and I ended up using [Pelican](http://getpelican.com)

### Other features That I would like to have in a static web site generator

1. Powerful Templates
1. Add Social buttons just by proving the links
1. Spell Check
1. Auto Compilation on Edit
1. Link Checking
1. Readability Statistics (Like what [Marked](http://markedapp.com/) does)
1. Some more AI word selection / optimization
1. I would like to be able to know if a link supports affiliate marketing
1. Mailing List (through something like mail chip)
1. Disqus Integration
1. Analytics Integrations (Google Analytics)
1. Bit.ly, link generator to tracking the source
1. Post to multiple websites (hackernews, reddit, facebook, twitter, ...)
1. Be able to upload to S3 or other services (pelican does this nicely)
1. Be able to import from another blog engine 

A pattern that I see coming up from this features sets is the need of a
plugin system. What I would like is to be able to configure a set of plugins
and then the system will download the appropriate packages.

    :::
    plugins {
        github.com/Mistobaan/awebsome-s3 
        github.com/Mistobaan/awebsome-bitly
    }

    awesome-bitly {
        # plugin sample configuration
    }


I will keep updating this post with more Features as they come to my mind

What features are the ones that you most love of your own website generator ?

