# README

### 1 Install composer
   composer install
### 2 Copy the example env file.
   cp .env.example .env
### 3 Generate a new application key
    php artisan key:generate
### 4 Generate a new JWT secret key
   php artisan jwt:generate
### 5 Install Mysql
   configration database info in .env.
### 6 run the database migrations.
   php artisan migrate
### 7 Make laravel controller and model
   php artisan make:model ExampleModel
   php artisan make:controller ExampleController --resource
### 8 make middleware
   php artisan make:middleware CheckExamepleMiddleware
### 9 run server
    php artisan serve
### 10 Database seeding.
    make database/seeds/Exampleseeder.php
    php artisan db:seed
