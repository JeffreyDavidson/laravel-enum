# Very short description of the package

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![StyleCI][ico-style]][link-style]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```:author_name``` ```:author_username``` ```:author_website``` ```:author_email``` ```:vendor``` ```:package_name``` ```:package_description``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practices by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```

## Installation

**Note:** Remove this paragraph if you are building a public package  
This package is custom built for [Mad Web](https://github.com/mad-web) projects and is therefore not registered on packagist. In order to install it via composer you must specify this extra repository in `composer.json`:

```json
"repositories": [ { "type": "composer", "url": "https://satis.mad-web.com/" } ]
```

You can install the package via composer:

```bash
composer require mad-web/:package_name
```

## Usage

``` php
$skeleton = new MadWeb\Skeleton();
echo $skeleton->echoPhrase('Hello, Mad Web!');
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email madweb.dev@gmail.com instead of using the issue tracker.

## Credits

- [:author_name](https://github.com/:author_username)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/mad-web/:package_name.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/mad-web/:package_name/master.svg?style=flat-square
[ico-style]: https://styleci.io/repos/:repo_id/shield
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/mad-web/:package_name.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/mad-web/:package_name.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/mad-web/:package_name.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/mad-web/:package_name
[link-travis]: https://travis-ci.org/mad-web/:package_name
[link-style]: https://styleci.io/repos/:repo_id
[link-scrutinizer]: https://scrutinizer-ci.com/g/mad-web/:package_name/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/mad-web/:package_name
[link-downloads]: https://packagist.org/packages/mad-web/:package_name
[link-author]: https://github.com/:author_username
[link-contributors]: ../../contributors