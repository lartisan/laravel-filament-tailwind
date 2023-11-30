## Install the template
```bash
composer install

cp .env.example .env

php artisan key:generate
```

## Create local DB
```bash
mysql -u root -p
```

```mysql
create database <db-name>;
exit;
```

## Migrate
```bash
php artisan migrate:fresh --seed
```

## Add first Filament Panel
```bash
php artisan filament:install --panels
```

## Create a user
```bash
php artisan make:filament-user
```