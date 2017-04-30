# Language
[![License](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
![Downloads](https://img.shields.io/packagist/dt/wpbp/language.svg) 

Wrap specific methods to get string or register it or get the language for Ceceppa Multilingua, Polylang and WPML plugins.

## Install

`composer require wpbp/language:dev-master`

[composer-php52](https://github.com/composer-php52/composer-php52) supported.

## Example

```php
echo get_language();

register_string( 'Test Wrapper', 'Test in progress', 'You are testing this wrapper' );

echo get_string( 'Test Wrapper', 'Test in progress', 'You are testing this wrapper' );

//Uncomment this after checked that in the plugin settings the string exist
deregister_string( 'Test Wrapper', 'Test in progress' );
```
