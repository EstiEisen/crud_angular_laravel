installation- crud app angular+laravel

git clone https://github.com/EstiEisen/crud_angular_laravel.git

the backend-laravel

cd laravel/laravel-7-crud-app

composer install

npm install

cp .env.example .env

php artisan key:generate

Add the database config in the .env file (DB_DATABASE=root DB_USERNAME=root password="")

php artisan migrate

php artisan serve 

the frontEnd-angular

cd app-crud

npm install

ng serve
