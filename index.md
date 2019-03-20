---
layout: page
title: Header H1
---

A [link](https://getbootstrap.com/) start up project for [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

* list item
* list item
* list item
* list item

## Header h2

### Header h3
Enter text here.

### Header h3

Here we have two possibilities:

* **You want a user or organization website**

  In this case your website's URL will be `http://<your username>.github.io` where `<your username>` is your Github user name.

  Go in the `Settings` page of your repository and rename it to `<your username>.github.io`.

* **You want a project website**

  In this case your website's URL will be `http://<your username>.github.io/<whatever you want>` where `<whatever you want>` can be any valid name for a Github repository.

  Go in the `Settings` page of your repository and rename it to `<whatever you want>`.

### Activate Github Pages on your repository

Go in the `Settings` page of your repository, in the `Github Pages`, under the `Source` parameter, choose `master branch` then `Save`.

### That's it

Your Github Pages website with customizable Bootstrap 4 is now up and running, you can access it using the URL displayed by Github in the `Github Pages` settings.

## Customization Guide

### Modify the configuration

You should at least edit the `_config.yml` file to edit your website's metadata, like the title, description and repository URL.


### Modify the content

You probably don't want the present guide to be the front page of your website, so you should edit the `index.md` file. You probably also want to edit or delete the `CONTRIBUTING.md`, `README.md` and `LICENSE.md` files.

Aside from that you can of course create new pages and posts like with any Jekyll website by refering to the [Jekyll documentation](https://jekyllrb.com/).

### Run Jekyll on your computer to speed up testing

Editing your website's content or theme directly on Github is completely possible but, due to the time Github Pages takes to update your website, it will probably be much more effective to work using a local Jekyll installation.

To do so:

* Install the [requirements for Jekyll](https://jekyllrb.com/docs/installation/).
* Type `bundle install` at the root of your project to install the necessary Ruby dependencies.
* Type `bundle exec jekyll serve` to launch the test Jekyll web server that will re-compile your work if you edit it.
* You can then open `http://localhost:4000` in your web browser to see your work-in-progress website.

Please note that, to ensure maximum compatibility with Github Pages, the `Gemfile` of this project references the `github-pages` gem, not Jekyll directly. This implies some differences in behavior compared to the official documentation of Jekyll.


## Other projects

[Easy Markdown to Github Pages](https://nicolas-van.github.io/easy-markdown-to-github-pages/) which documents how to publish Markown files to Github Pages in the fastest way.
