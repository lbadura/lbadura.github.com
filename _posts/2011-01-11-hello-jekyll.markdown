---
layout: post
title: Hello Jekyll
---

I've been planning to checkout [Jekyll](http://jekyllrb.com/) for a long time now. I was looking for a
simple solution to maintain my blog and [Jekyll](http://jekyllrb.com/) definitely the way to go.

# What is Jekyll

[Jekyll](http://jekyllrb.com/) is a blog-aware static page generator written in
Ruby. It takes a directory with template files, your posts written in your favourite markup
flavor and generates static HTML files ready to be deployed on your web server. 

# Advantages

* _Simple installation_ - just ``gem install jekyll``
* _Save your server/vps resources_. You don't need a DB instance, or a resource
  consuming stack of dynamic language interpreters. If you're hosting your site
  on a cheap VPS you'll be thrilled.
* You can _deploy your blog on any web server_ able to serve HTML files or even [GitHub](http://www.github.com)
* Simple _backup_ - just save a single directory somewhare safe and you're good to go
* You can write your posts in your _favourite text editor_ (vim !) with your favourite markup: [Markdown](http://en.wikipedia.org/wiki/Markdown), [Textile](http://en.wikipedia.org/wiki/Textile_(markup_language\)), [Liquid](http://www.liquidmarkup.org/).
* You can use your favourite version control system as the backend. [GitHub](http://www.github.com) has a build in support for [Jekyll](http://jekyllrb.com/) since [GitHub](http://www.github.com) Pages are built with it)

# Disadvantages

* _No dynamic fireworks_. Since [Jekyll](http://jekyllrb.com/) generates static pages you can't take
  advantage of all the flexibility a dynamic language can give you. On the
  bright side, you can use JavaScript to add some life to your site.
* _No built in comments_. Well it kind of steps on the _'no dynamic fireworks'_ point, but the lack of comments is the first thing you'll notice. Unfortunately there is a good number of nice services like [Disqus](http://www.disqus.com) which will enable you have comments on your [Jekyll](http://jekyllrb.com/) generated site in no time.

# Workflow

Working with [Jekyll](http://jekyllrb.com/) is very easy. All you have to do is to define basic
templates for your site (a default, and a separate one for pages with posts).
Write some posts and / or import the ones from your previous setup. Run [Jekyll](http://jekyllrb.com/)
to generate your files. Upload and you're all set. It gets even better if you
want to use your [GitHub](http://www.github.com) account.

You can create a repository _<your_github_login>.github.com_ commit your [Jekyll](http://jekyllrb.com/)
directory, and [GitHub](http://www.github.com) will build your site for you and host it under the above
URI. You can also host your site under your own domain name there. Pretty
sweet.

# Summary

Overall I'm very happy with the switch. It feels so much more natural to write
posts on my local machine and then simply committing them to my [GitHub](http://www.github.com) repository. It's also nice that I can use my VPS resources on other things than
to host my own instance on WordPress.
