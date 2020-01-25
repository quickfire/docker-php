# This is forked

This was forked from [docker-php/docker-php](https://github.com/docker-php/docker-php) for use within quickfire.

Composer commands won't yet work as this isn't yet published on packagist.

Docker PHP
==========

**Docker PHP** (for lack of a better name) is a [Docker](http://docker.com/) client written in PHP.
This library aim to reach 100% API support of the Docker Engine.

The test suite currently passes against Docker Remote API v1.25 to v1.36.

Installation
------------

The recommended way to install Docker PHP is of course to use [Composer](http://getcomposer.org/):

```bash
composer require quickfire/docker-php
```

Docker API Version
------------------

By default it will use the last version of docker api available, if you want to fix a version (like 1.25) you can add this 
requirement to composer:

```bash
composer require "quickfire/docker-php-api:4.1.25.*"
```

Usage
-----

See [the documentation](http://docker-php.readthedocs.org/en/latest/) for now. New docs coming soon(tm)

Unit Tests
----------

Setup the test suite using [Composer](http://getcomposer.org/) if not already done:

```
$ composer install --dev
```

Run it using [PHPUnit](http://phpunit.de/):

```
$ composer test
```

Contributing
------------

Currently not accepting new pull requests.

Credits
-------

Forked from [docker-php/docker-php](https://github.com/docker-php/docker-php) by quickfire.

This README was originally heavily inspired by [willdurand/Negotiation](https://github.com/willdurand/Negotiation) by @willdurand. This guy is pretty awesome.

License
-------

The MIT License (MIT). Please see [License File](LICENSE) for more information.
