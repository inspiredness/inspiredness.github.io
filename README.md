Inspiredness.io Project
=========================

This is a jekyll project for:
* [https://inspiredness.io/](https://inspiredness.io/)

**This website is built with Jekyll**. It uses a fork of a template called [Tale](https://github.com/chesterhow/tale) which was **customized** for the purpose of this project. It is fully compatible with Github pages, where it is actually hosted. 

![inspiredness_screenshot](https://user-images.githubusercontent.com/1360604/76074925-65762580-5f9c-11ea-9a93-ef4f840ebfdb.png)

## What is Jekyll?

No more databases, comment moderation, or pesky updates to install-just your content. **Markdown, Liquid, HTML & CSS go in**. Static sites come out ready for deployment. Permalinks, categories, pages, posts, and custom layouts are all first-class citizens here.

**GitHub Pages are powered by Jekyll,** so you can easily deploy your site using GitHub for free-custom domain name and all.
**Jekyll is a simple, blog-aware, static site generator.**

You create your content as text files (Markdown), and organize them into folders. Then, you build the shell of your site using Liquid-enhanced HTML templates. **Jekyll automatically stitches the content and templates together, generating a website made entirely of static assets, suitable for uploading to any server.**

Jekyll happens to be the engine behind GitHub Pages, so you can host your project’s Jekyll page/blog/website on GitHub’s servers for free.


## Quick Start Guide

**If you already have a full Ruby development environment** (go to the Bundler section on this page for more information) with all headers and RubyGems installed (see Jekyll’s requirements), you can create a new Jekyll site by doing the following:

```ruby
# Install Jekyll and Bundler gems through RubyGems
gem install jekyll bundler

# Create a new Jekyll site at ./myblog
jekyll new myblog

# Change into your new directory
cd myblog

# Build the site on the preview server
bundle exec jekyll serve

# Now browse to http://localhost:4000
```

## About Bundler

`gem install bundler` installs the bundler gem through RubyGems. You only need to install it once - not every time you create a new Jekyll project. Here are some additional details:
{: .text-justify}

`bundler` is a gem that manages other Ruby gems. It makes sure your gems and gem versions are compatible, and that you have all necessary dependencies each gem requires.
{: .text-justify}

The `Gemfile` and `Gemfile.lock` files inform `Bundler` about the gem requirements in your site. If your site doesn’t have these Gemfiles, you can omit `bundle exec` and just `run jekyll serve`.
{: .text-justify}

When you run `bundle exec jekyll serve`, `Bundler` uses the gems and versions as specified in `Gemfile.lock` to ensure your Jekyll site builds with no compatibility or dependency conflicts.
{: .text-justify}

For more information about how to use `Bundler` in your Jekyll project, this tutorial should provide answers to the most common questions and explain how to get up and running quickly.
{: .text-justify}


## Using this template

Download or Fork it: [https://github.com/inspiredness/inspiredness.github.io](https://github.com/inspiredness/inspiredness.github.io). 
- In your local project, open <code>_config.yml</code>. If your site is in root, for <code>baseurl</code>, make sure this is set to <code>baseurl: ""</code>. Also, change your Google Analytics code and disqus username.
- Edit the menu and footer copyrights in <code>default.html</code>
- Start by adding your .md files in <code>_posts</code>. 
- YAML front matter
    - exclude featured post from "All stories" loop to avoid duplicated posts - <code>hidden:true</code>
    - post image - <code>image: assets/images/mypic.jpg</code>
    - page comments - <code>comments:true</code>
    - meta description (optional) - <code>description: "this is my meta description"</code>
    
YAML Post Example:
<pre>
---
layout: post
title:  "Your Post title"
description: "this is my meta description"
author: Fernando Cejas
comments: true
---
</pre>

## Features
- Easy installation
- Compatible with GitHub Pages
- Responsive design (looks just as good on mobile)
- Syntax highlighting, with the help of Pygments
- Markdown and HTML text formatting
- Pagination of posts
- [Disqus comments (can be enabled if needed)](#enabling-comments)

### Enabling Comments
Comments are disabled by default. To enable them, look for the following line in `_config.yml` and change `jekyll-tale` to your site's Disqus id.

```yml
disqus: jekyll-tale
```

Next, add `comments: true` to the YAML front matter of the posts which you would like to enable comments for.


## Contribute

Feel free to contribute either by requesting features or collaborating with new articles. 
- [Clone the repo](https://github.com/inspiredness/inspiredness.github.io).
- Create a branch off of master and give it a meaningful name (e.g. my-new-post or my-new-feature).
- Open a pull request on GitHub and describe the feature, fix or post.


## Useful links

* [Inspiredness.io BLOG HELP](https://inspiredness.io/help/)
* [Jekyll: Quick-start guide](https://jekyllrb.com/docs/quickstart/)
* [Jekyll: Documentation](https://jekyllrb.com/docs/home/)
* [Github: Jekyll dependency versions](https://pages.github.com/versions/)
* [Github: Jekyll supported themes](https://pages.github.com/themes/)


Useful commands for building this site
-----------------

 * `bundle install`: Install all the dependencies.
 * `bundle update`: Updates all dependencies.
 * `jekyll clean`: Clean up the project.
 * `jekyll build`: Build and generate all the static files for the website. 
 * `bundle exec jekyll serve`: Starts a local server to test the website. 


License
--------
     
    MIT License

    Copyright (c) 2020 Fernando Cejas

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

![http://www.fernandocejas.com](https://github.com/android10/Sample-Data/blob/master/android10/android10_logo_big.png)

<a href="https://www.buymeacoffee.com/android10" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Invite Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
