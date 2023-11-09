> Workaround for [issue #6](https://github.com/elegantthemes/marketplace-phpcs/issues/6) until elegant themes fixes the official [PHPCS module](https://github.com/elegantthemes/marketplace-phpcs/).
>
> Also enabled PHP 7 syntax [issue #7](https://github.com/elegantthemes/marketplace-phpcs/issues/7)

# Prerequisites

[Git](https://git-scm.com/downloads)  (Distributed version-control system)

[Composer](https://getcomposer.org/download/) (PHP Dependency Manager)

# Usage

1. Clone this repository `git clone https://github.com/divimode/marketplace-phpcs/`
2. Inside the `marketplace-phpcs` directory, run `composer install`
3. Then run `./vendor/bin/phpcs --standard=ruleset.xml /full/path/to/your/product`
4. To only show errors add `-n` to the command above.
