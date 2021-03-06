# [Wip] Laravel artisan scan

[![Latest Version on Packagist](https://img.shields.io/packagist/v/appstract/laravel-artisan-scan.svg?style=flat-square)](https://packagist.org/packages/appstract/laravel-artisan-scan)
[![Total Downloads](https://img.shields.io/packagist/dt/appstract/laravel-artisan-scan.svg?style=flat-square)](https://packagist.org/packages/appstract/laravel-artisan-scan)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/appstract/laravel-artisan-scan/master.svg?style=flat-square)](https://travis-ci.org/appstract/laravel-artisan-scan)

# Work in progress

This package allows you to check several things in just one command, such as: 
- mixed content
- SSL certificate
- Minified assets 

However, keep in mind that this is still a work in progress, feel free to check it out tho.


## Installation

You can install the package via composer:

``` bash
composer require appstract/laravel-artisan-scan
```

## Usage

``` bash
php artisan scan:launch
```

![Screenshot](screenshot.png?raw=true)

## Testing

``` bash
$ composer test
```

## Contributing

Contributions are welcome, [thanks to y'all](https://github.com/appstract/laravel-blade-directives/graphs/contributors) :)

## About Appstract

Appstract is a small team from The Netherlands. We create (open source) tools for webdevelopment and write about related subjects on [Medium](https://medium.com/appstract). You can [follow us on Twitter](https://twitter.com/teamappstract), [buy us a beer](https://www.paypal.me/teamappstract/10) or [support us on Patreon](https://www.patreon.com/appstract).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
