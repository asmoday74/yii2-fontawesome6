Yii2 Font Awesome 6
===================
Font Font Awesome 6 for Yii2

Installation
------------

The preferred way to install this extension is through [composer](https://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist asmoday74/yii2-fontawesome6 "*"
```

or add

```
"asmoday74/yii2-fontawesome6": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php

...

use asmoday74\fontawesome6\FontAwesomeAsset;

...

<?= FontAwesomeAsset::register($this); ?>