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