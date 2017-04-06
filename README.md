P2Y2 Moment Timezone v1.0.0
====================

moment.js & moment-timezone.js as Yii2 assets

Installation
------------

The preferred way to install P2Y2 Timezones is through [composer](http://getcomposer.org/download/).
Depending on your composer installation, run *one* of the following commands:

```
	composer require p2made/yii2-p2y2-timezones "^0.0"
```

or

```
	php composer.phar require p2made/yii2-p2y2-timezones "^0.0"
```

Alternatively add:

```
	"p2made/yii2-p2y2-timezones": "^0.0"
```

to the requires section of your `composer.json` file & P2Y2 Timezones will be installed next time you run `composer update`.

And then...
-----------

Register either of the assets with...

```
	p2m\assets\MomentAsset::register($this);
	p2m\assets\MomentTimezoneAsset::register($this);
```

Declare them as dependancies with...

```
	p2m\assets\MomentAsset::register($this);
	p2m\assets\MomentTimezoneAsset::register($this);
```

