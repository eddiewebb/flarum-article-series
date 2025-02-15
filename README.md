# Blog Article Series

![License](https://img.shields.io/badge/license-MIT-blue.svg) [![Latest Stable Version](https://img.shields.io/packagist/v/askvortsov/flarum-article-series.svg)](https://packagist.org/packages/askvortsov/flarum-article-series) [![Total Downloads](https://img.shields.io/packagist/dt/askvortsov/flarum-article-series.svg)](https://packagist.org/packages/askvortsov/flarum-article-series)

A [Flarum](http://flarum.org) extension. Article Series support for Flarum Blog

This allows you to create article series by labelling discussions with certain secondary tags.

![](https://i.imgur.com/uJ74H6g.jpg)

Live site: [ceramichacker.com](https://ceramichacker.com)

### Usage

1. Install and enable the extension
2. Go to a tag that you'd like to be an article series on the tags settings page, and select the "Is Article Series" checkbox in the tag settings modal
   1. Usually, secondary tags should be used for article series
3. For every discussion that's part of the article series, open the discussion controls dropdown, select which article series it's a part of, and select an order index. Articles will be sorted from lowest to highest order.
4. Go to the article in the flarum-blog view, and you should see an article series navigation on the right

### Installation

Install with composer:

```sh
composer require askvortsov/flarum-article-series:"*"
```

### Updating

```sh
composer update askvortsov/flarum-article-series:"*"
php flarum migrate
php flarum cache:clear
```

### Links

- [Packagist](https://packagist.org/packages/askvortsov/flarum-article-series)
- [GitHub](https://github.com/askvortsov/flarum-article-series)
- [Discuss](https://discuss.flarum.org/d/PUT_DISCUSS_SLUG_HERE)
