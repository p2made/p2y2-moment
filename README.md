P2Y2 Timezones v0.1.0
==============

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

P2Y2 Timezones gives you the option of loading assets from the official CDNs. Just put this into `common/config/params.php`...

```
	'p2made' => [
		'useStatic' => true, // false or not set to use published assets
	],
```

When things are set up to your liking, register the `P2CoreLoaderAsset` with...

```
```

...&  you get
* `yii\web\YiiAsset`, followed by
* `Jquery` (as `p2m\assets\JqueryAsset`),
* `Jui` (as `p2m\assets\JuiAsset`),
* `Bootstrap` (as `p2m\assets\BootstrapAsset`), &
* `Font Awesome` (as `p2m\assets\FontAwesomeAsset`)

nicely loaded in one line.


---
[![Dependency Status](https://www.versioneye.com/user/projects/56de5856df573d00352c66c0/badge.svg?style=flat)](https://www.versioneye.com/user/projects/56de5856df573d00352c66c0)
