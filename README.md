# CakePHP CMS Tutorial

The completed CMS tutorial application created during
https://book.cakephp.org/5/en/tutorials-and-examples/cms/installation.html

## Installation

1. Download [Composer](https://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Download this source code. `git clone https://github.com/cakephp/cms-tutorial.git`
3. Install dependencies with composer

```bash
cd cms-tutorial
composer install
```

## Configuration

You can use the default configuration, using a sqlite3 file based database. In that case, no configuration
is required.
If you want to use your own database, update the `'Datasources'` configuration in `config/app.php`.
You'll also need to create a database and run the SQL located in the tutorial.

## Running the project

```bash
bin/cake server
```

Then point your browser to http://localhost:8765

You will be redirected to the `/users/login` page. This is the behavior we configured to request a valid
username and password. The CMS Tutorial user Authentication and Authorization to identify the users.
