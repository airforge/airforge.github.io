---
layout: post
title: "THIS ME FIRST POST WOO"
category: posts
---

So, this is the all-new UP version. It is more based
on my own [blog][my-blog], which is a some kind of
branch of this theme.

The biggest changes here are:

- Assets are now managed by [bower][bower];
- Build are now made by [grunt][grunt];
- `Procfile.dev` to use with foreman to watch
changes everywhere (assets, pages, posts);
- Removed the hardcoded Jekyll from Gemfile and
replaced it with the github pages Gem;
- Bumped all assets versions;
- Some semantics fixed in HTML;

### Usage

To get started, with Ruby, Bundler, Node.js and NPM
previously in your `PATH`, run the init script:

{% highlight bash %}
./script/init.sh
{% endhighlight %}

This will install all needed dependencies and build
the the assets for you (just run `grunt`).

You can also start it up in watch mode with

{% highlight bash %}
foreman start -f Procfile.dev
{% endhighlight %}

### Update

To update, the easiest way is to backup your _posts folder and override
everything else. If you don't want to do that, you will have to hack
around the changes and do it by hand.

If you have any issues or suggestions, ping me at the [up project][up].

[up]: http://github.com/caarlos0/up
[my-blog]: http://carlosbecker.com
[bower]: http://bower.io
[grunt]: http://gruntjs.com/
