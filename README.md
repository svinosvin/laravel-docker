# laravel-docker
- docker compose run -rm composer create-project laravel/name-project . 
- Take settings for db from mysql env and add it to env file for laravel, also change dbhost to DB_HOST = mysql
- docker compose run artisan key:generate
- exec -T php chmod -R 777 /var/www/laravel/storage
- docker compose run -rm artisan migrate

