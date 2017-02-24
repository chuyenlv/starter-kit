# Drupal 7 - Starter kit

## Requirements
- [Composer](https://getcomposer.org/download/)
- PHP 5.6

## Install
- Build repo in local.
  `composer install --no-dev -o`
- Add package to repo (drupal contrib, php libraries, ...).
  `composer require "<package/name>"`, for example: `composer require "drupal/ctools"` or `composer require "guzzle/guzzle"`
- Remove package from repo.
  ` composer remove "<package/name>"`
