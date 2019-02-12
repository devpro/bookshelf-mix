# Symfony API

## Requirements

### PHP

- PHP version: 7.2

- Edit `php.ini`

- MongoDB driver installation on [php.net](https://secure.php.net/manual/en/mongodb.installation.php)

## Update history

### API creation

- Create a new application from `symfony/skeleton` template

```bash
composer create-project symfony/skeleton api-symfony
cd api-symfony
```

- Add dev server and launch it ([http://127.0.0.1:8000](http://127.0.0.1:8000))

```bash
composer require server --dev
php bin/console server:run
```

- Add API recipe

```bash
composer require api
```

- Review `config/packages/doctrine.yaml` and create `.env.local`.

```bash
composer require mongodb/mongodb
```
