# docker-laravel

## Constitution
* nginx:1.17-alpine
* php:7.3-fpm-alpine
* mysql:8.0
* phpmyadmin/phpmyadmin

## What to do after cloning
1. Change directory to app　`composer install` 

2. `docker-compose exec php bash`,`php artisan key:generate`

3. Change .env of db

## port
* http://localhost:8000 (Laravel) 
* http://localhost:3000 (phpmyadmin)
