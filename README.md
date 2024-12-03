# laravel-docker
- docker compose run --rm composer create-project laravel/laravel . --prefer-dist
- Take settings for db from mysql env and add it to env file for laravel, also change dbhost to DB_HOST = mysql
- docker compose run --rm php chmod -R 777 /var/www/laravel/storage
- docker-compose up nginx -d 
- docker compose run --rm artisan key:generate
- docker compose run --rm artisan migrate

