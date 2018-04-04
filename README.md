# Zend_Matrixcode

This is a fork of unmaintained module to Zend Framework 1 for generating QR codes.
More info on site: https://code.google.com/archive/p/zend-framework-matrixcode-module/ 

I just made one change in base code. I remove all "require_once" from the code and extend composer autoloader to handle loading classes.

## Installing

To install you need to just run composer locally

```
php composer.phar require kwojtas6/zend_matrixcode
```
or globally
```
composer require kwojtas6/zend_matrixcode
```

## License

This project is licensed under the BSD-3-Clause License - see the [LICENSE.md](LICENSE.md) file for details
