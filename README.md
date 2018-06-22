# Artefakt Pattern Library Tool

## Prerequisites

* [PHP 7.2+](https://php.net)
* [Composer](http://getcomposer.org/) (PHP dependency manager)

I recommend using the latest available version of PHP as a matter of principle.

## Installation

Start a new Artefakt Pattern Library by running this on a command prompt (requires [Composer](http://getcomposer.org/) to be available as `composer`):

```bash
composer create-project apparat/artefakt <project-name>
cd <project-name>
```

Please make sure to replace `<project-name>` with the path and name of your project.

## Quality

The Artefakt set of libraries attempt to comply with [PSR-1][], [PSR-2][], and [PSR-4][]. If you notice compliance oversights, please send a patch for the respective library via pull request.

## Contributing

Found a bug or have a feature request? [Please have a look at the known issues](https://github.com/apparat/artefakt/issues) first and open a new issue if necessary. Please see [contributing](CONTRIBUTING.md) and [conduct](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email joschi@kuphal.net instead of using the issue tracker.

## Credits

- [Joschi Kuphal][author-url]
- [All Contributors](../../contributors)

## License

Copyright © 2018 [Joschi Kuphal][author-url] / joschi@kuphal.net. Licensed under the terms of the [MIT license](LICENSE).

[author-url]: https://jkphl.is

[PSR-4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
[PSR-2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
