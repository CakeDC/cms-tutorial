# CakePHP CMS Tutorial

The completed CMS tutorial application created during
https://book.cakephp.org/5/en/tutorials-and-examples/cms/installation.html

## Installation

1. Download [Composer](https://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Download this source code.
3. Install dependencies with composer

```bash
composer install
```

## Configuration

* Update the `'Datasources'` configuration by:
  * editing `config/app.php` or `config/app_local.php` for your local database or
  * edit `config/bootstrap.php` to enable use of a `.env` file (uncomment the section that loads the `.env` file) (and provide the `config/.env` file.
* Create a database if needed.
* Run `bin/cake migrations migrate` to create the database tables.

