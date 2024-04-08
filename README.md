# Laravel 11 Rest API Demo

This is a demonstration project showcasing the implementation of a RESTful API using Laravel 11. Laravel is a popular PHP framework known for its elegant syntax and powerful features, making it an excellent choice for building APIs.

## Features

- CRUD Operations: Demonstrates Create, Read, Update, and Delete operations on resources.
- Authentication: Utilizes Laravel's built-in authentication system for securing endpoints.
- Validation: Implements request validation to ensure data integrity.
- Resourceful Routing: Utilizes Laravel's resourceful routing for defining API endpoints.
- Database Integration: Interacts with a MySQL database for data persistence.

## Prerequisites

Before running this demo, ensure you have the following installed:

- PHP (>=7.4)
- Composer
- MySQL (or any other database supported by Laravel)
- Laravel CLI

## Installation

1. Clone this repository:

```bash
git clone  https://github.com/sandeep0108/laravel11-rest-api-crud-demo.git

cd laravel-11-rest-api-demo

composer install

cp .env.example .env

php artisan key:generate

php artisan migrate

php artisan db:seed

php artisan serve



## Reference
https://www.itsolutionstuff.com/post/laravel-11-rest-api-authentication-using-sanctum-tutorialexample.html
https://medium.com/@1415sandalanka/laravel-11-rest-api-crud-with-best-practices-fcc26505e0d2
