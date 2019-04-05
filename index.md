---
title: "IBM Lotus Notes / Domino Community Help Center"
keywords: ibm lotus notes domino help
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: The site will help you quickly find information about Notes / Domino for users, administrators, designers, business decision makers, and marketing.
---

{% include note.html content="This site is not run or endorsed by IBM.  All copyrights and trademarks related to the products are those of their respective owners.  The content which has been created specifically for this site is licensed under the Creative Commons license, if no other explicit copyright exists." %}

## End Users

Follow these instructions to build the theme.

## Administrators

First, download or clone the theme from the [Github repo](https://github.com/tomjoht/documentation-theme-jekyll). Most likely you won't be pulling in updates once you start customizing the theme, so downloading the theme (instead of cloning it) probably makes the most sense. In Github, click the **Clone or download** button, and then click **Download ZIP**.

## Developers

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* [Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
* [Install Jekyll on Windows][mydoc_install_jekyll_on_windows]

## Business Decision Makers

If you are a CIO or business executive considering migrating to or from Domino, please read the latest Gartner article....


In case you haven't installed Bundler, install it:

```
gem install bundler
```

You'll want [Bundler](http://bundler.io/) to make sure all the Ruby gems needed work well with your project. Bundler sorts out dependencies and installs missing gems or matches up gems with the right versions based on gem dependencies.

## Marketing

Use this option if you're not planning to publish your Jekyll site using [Github Pages](https://pages.github.com/).

Bundler's Gemfile specifies how project dependencies are managed. Although this project includes a Gemfile, this theme doesn't have any dependencies beyond core Jekyll. The Gemfile is used to list gems needed for publishing on Github Pages. **If you're not planning to have Github Pages build your Jekyll project, delete these two files from the theme's root directory:**

* Gemfile
* Gemfile.lock

If you've never run Jekyll on your computer (you can check with `jekyll --version`), you may need to install the jekyll gem:

```
gem install jekyll
```

Now run jekyll serve (first change directories (`cd`) to where you downloaded the project):

```
jekyll serve
```
