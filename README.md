# Open

> Opens a file or URL in PHP, in a cross-platform way. This is a PHP port of [node-open](https://github.com/pwnall/node-open).

## Installation

```bash
$ composer require likesistemas/open
```

## Usage

### Utility

Use the `open()` method to open a file or URL using the default or a specific app

```php
use Open\Open;

Open::open('picture.jpg');

// It will use the default browser
Open::open('http://google.com');

// It will try to use Chrome
Open::open('http://google.com', 'chrome');
```

### Command

Open Google using your default browser

```php
$ php bin/open http://google.com
```

Open Google using the specified browser (firefox)

```php
$ php bin/open http://google.com firefox
```

## License

[MIT](https://github.com/likesistemas/open/blob/master/LICENSE)

[version-url]: https://packagist.org/packages/likesistemas/open
[version-image]: http://img.shields.io/packagist/v/likesistemas/open.svg?style=flat
