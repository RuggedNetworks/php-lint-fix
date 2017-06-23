# Style check and fixer for PHP

[![Docker Pulls](https://img.shields.io/docker/pulls/sixlive/php-lint-fix.svg)](https://hub.docker.com/r/sixlive/php-lint-fix)
[![Docker Stars](https://img.shields.io/docker/stars/sixlive/php-lint-fix.svg)](https://hub.docker.com/r/sixlive/php-lint-fix)
[![Docker Automated buil](https://img.shields.io/docker/automated/sixlive/php-lint-fix.svg)](https://hub.docker.com/r/sixlive/php-lint-fix)
[![Docker Build Statu](https://img.shields.io/docker/build/sixlive/php-lint-fix.svg)](https://hub.docker.com/r/sixlive/php-lint-fix)

This container is aimed at providing the ability to fix and lint PHP code via Docker. The primary goal was to provide a way to lint and fix code in a Dockerized CI pipeline. The container provides [phpcs](https://github.com/squizlabs/PHP_CodeSniffer) and [php-cs-fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

## Installation

```shell
docker pull sixlive/php-lint-fix
```

## Usage
### php-cs-fixer
```shell
docker run -it --rm -v `pwd`:/app sixlive/php-lint-fix php-cs-fixer
```

### phpcs
```shell
docker run -it --rm -v `pwd`:/app sixlive/php-lint-fix phpcs
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email oss@tjmiller.co instead of using the issue tracker.

## Credits

- [TJ Miller](https://github.com/sixlive)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
