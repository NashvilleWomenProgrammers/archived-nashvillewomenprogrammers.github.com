# How to update the site for nashvillewomenprogrammers.com

This is a fork of the [Minimal Mistakes Jekyll theme](http://jekyllthemes.org/themes/minimal-mistakes/).

If you're a member of our github organization, you can clone and edit the site on our [github page](https://github.com/nashville-women-programmers/nashville-women-programmers.github.com).  If you aren't a member, you can fork the project from there and then edit it.

1. Run `bundle install` to make sure you have all the necessary dependencies installed.
2. Fork this site from our [github page](https://github.com/nashville-women-programmers/nashville-women-programmers.github.com), then clone your fork of the site.
3. Once you've downloaded the project, swap out the comments on lines 5 and 6 of `_config.yml`.
4. Then, run `jekyll serve --watch` in the project directory.
5. The site will now be visible locally at [localhost:4000](localhost:4000).
6. Make your edits and then commit to github (making sure not to commit your changes to lines 5 and 6 of `config.yml`).
7. Make a pull request on github.com, and we'll integrate your changes.


# Minimal Mistakes Theme

**[Minimal Mistakes](http://mmistakes.github.io/minimal-mistakes)** is a two column responsive Jekyll theme perfect for powering your GitHub hosted blog.

## Minimal Mistakes is all about:

* Responsive templates. Looking good on mobile, tablet, and desktop.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 8+ and all modern browsers. 
* Minimal embellishments. Content first; other widget nonsense never.
* Large feature images for posts and pages.
* Simple and clear permalink structure.
* [Custom 404 page](http://mmistakes.github.io/minimal-mistakes/404.html) to get you started.
* Stylesheets for Pygments and Coderay [syntax highlighting](http://mmistakes.github.io/minimal-mistakes/articles/code-highlighting-post/) to make your code examples look snazzy.

![screenshot of Minimal Mistakes theme](http://mmistakes.github.io/minimal-mistakes/images/mm-theme-post-600.jpg)

General notes and suggestions for customizing Minimal Mistakes.

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com) if you haven't already.
2. Fork the [Minimal Mistakes repo](http://github.com/mmistakes/minimal-mistakes/)
3. Clone the repo you just forked to your computer.
4. Edit `_config.yml` to personalize your site.
5. Check out the sample posts in `_posts` to see examples for pulling in large feature images, tags, and other YAML data.
6. Read the documentation below for further customization pointers and documentation.

[Demo the Theme](http://mmistakes.github.io/minimal-mistakes)

**Pro-tip:** Delete the `gh-pages` branch after cloning and start fresh by branching off `master`. There is a bunch of garbage in `gh-pages` used for the theme's demo site that I'm guessing you don't want on your site.

---

## Setup for an Existing Jekyll site

1. Clone the following folders: `_includes`, `_layouts`, `assets`, and `images`.
2. Clone the following files and personalize content as need: `about.md`, `articles.html`, `index.md`, `feed.xml`, `sitemap.xml`
3. Set the following variables in your `config.yml` file:

``` yaml
title:            Site Title
description:      Describe your website here.
disqus_shortname: shortname
url:              http://your-website.com

# Owner/author information
owner:
  name:           Your Name
  avatar:         avatar.jpg
  bio:            "Your bio goes here. It shouldn't be super long but a good two sentences or two should suffice."
  email:          you@email.com
  # Social networking links used in footer. Update and remove as you like.
  twitter:        
  facebook:       
  github:         
  stackexchange:  
  linkedin:       
  instagram:      
  flickr:         
  tumblr:         
  # For Google Authorship https://plus.google.com/authorship
  google_plus:    

# Analytics and webmaster tools stuff goes here
google_analytics:   
google_verify:      
# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:         

# Links to include in top navigation
# For external links add external: true
links:
  - title: Theme Setup
    url: /theme-setup
  - title: External Link
    url: http://mademistakes.com
    external: true

# http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
timezone:    America/New_York
future:      true
pygments:    true
markdown:    kramdown

```

---

## Questions?

Having a problem getting something to work or want to know why I setup something in a certain way? Ping me on Twitter [@mmistakes](http://twitter.com/mmistakes) or [file a GitHub Issue](https://github.com/mmistakes/minima-mistakes/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the [GNU General Public License](http://mmistakes.github.io/minimal-mistakes/LICENSE) version 2 or later. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer. 
