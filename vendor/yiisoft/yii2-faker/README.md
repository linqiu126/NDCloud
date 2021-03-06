Faker Extension for Yii 2
=========================

This extension provides a [`Faker`](https://github.com/fzaninotto/Faker) fixture command for the [Yii framework 2.0](http://www.yiiframework.com).

For license information check the [LICENSE](LICENSE.md)-file.

[![Latest Stable Version](https://poser.pugx.org/yiisoft/yii2-faker/v/stable.png)](https://packagist.org/packages/yiisoft/yii2-faker)
[![Total Downloads](https://poser.pugx.org/yiisoft/yii2-faker/downloads.png)](https://packagist.org/packages/yiisoft/yii2-faker)
[![Build Status](https://travis-ci.org/yiisoft/yii2-faker.svg?branch=master)](https://travis-ci.org/yiisoft/yii2-faker)


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist yiisoft/yii2-faker
```

or add

```json
"yiisoft/yii2-faker": "~2.0.0"
```

to the require section of your composer.json.


Usage
-----

To use this extension,  simply add the following code in your application configuration (console.php):

```php
'controllerMap' => [
    'fixture' => [
        'class' => 'yii\faker\FixtureController',
    ],
],
```
