# Drupal 8 - Starter kit

## Requirements
- [Composer](https://getcomposer.org/download/)

## Install
- Build repo in local.
  `composer install --no-dev -o`
- Add package to repo (drupal contrib, php libraries, ...).
  `composer require "<package/name>"`, for example: `composer require "drupal/ctools"` or `composer require "guzzle/guzzle"`
- Remove package from repo.
  ` composer remove "<package/name>"`

## Provision dev
- Require [fin](http://docksal.readthedocs.io/en/master/getting-started/env-setup/#linux)
- `git clone https://github.com/chuyenlv/starter-kit project-name`
- `cd project-name`
- `composer install --no-dev -o`
- `fin init`
