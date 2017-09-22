## Multilingual E-commerce Jekyll template

![snipcart-static-site-ecommerce-jekyll](https://snipcartweb-10f3.kxcdn.com/media/all/9570/snipcart-static-site-ecommerce-jekyll.png)

> Read full tutorial [here](https://snipcart.com/blog/cms-jekyll-cloud-cannon-multilingual)

> See live demo [here](https://snipcart.github.io/demo-cloudcannon/)

***

E-commerce template for Jekyll. Browse through a [live demo](https://turquoise-rook.cloudvent.net).

This template is based on [Fur](https://github.com/CloudCannon/fur-jekyll-template) by [CloudCannon](http://cloudcannon.com/) and we added multilingual features and customizable categories.

You can learn more about building stuff on CloudCannon at [CloudCannon Academy](https://learn.cloudcannon.com/).

## Features

* Edit your content in multiple language
* List product by categories
* Take payment online using SnipCart
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Google Analytics

## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics, Google Maps API key and [SnipCart key](https://snipcart.com/) to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

This demo was built with [Jekyll](http://jekyllrb.com/) version 3.5.2, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Fur is already optimised for adding, updating and removing products and editing the navigation and footer in CloudCannon.

### Posts

* Add, update or remove a post in the *Posts* collection.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Navigation

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.

## License

The code and templates are MIT licensed.

The icons are from [The Noun Project](https://thenounproject.com/).
