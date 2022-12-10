# API MICROSERVICE PHP


## Version Php and Composer

- Php 7.2.5
- Composer 1.10.10

## inicializar las composicion de dependecias

- docker-compose up --build
- docker-compose up -d --no-build

## Public

composer dump-autoload -o

php -S localhost:8000 -t api/public

php -S 0.0.0.0:8000 -t api/public

- php artisan make:migration create_users_table
- php artisan migrate
- php artisan db:seed

php artisan migrate:refresh
php artisan migrate:refresh --seed



## clean cache

php artisan cache:clear

pdfcrowd/pdfcrowd": "^4.11"
"nordsoftware/lumen-file-manager": "^2.2"
composer require ktquez/lumen-image

## Install package

sudo apt-get update
sudo apt-get install pgloader

sudo -u gitlab-psql pgloader commands.load

## Docker

docker build -t zayro/backend-service .

docker run -p 8080:8080 -d zayro/backend-service

## delete image

- docker rmi -f zayro/backend-service