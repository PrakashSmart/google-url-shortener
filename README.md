Yii2-Google URL Shortener
=========================
Google URL Shortener at goo.gl is used by Google products to create short URLs that can be easily shared, tweeted, or emailed to friends.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist smartt/yii2-google-url-shortener "*"
```

or add

```
"smartt/yii2-google-url-shortener": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \smartt\googleurlshortener\GoogleURLShortner::widget(); ?>
