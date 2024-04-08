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
```

2. Navigate into the project directory:

```bash
cd laravel-11-rest-api-demo
```

3. Install dependencies:

```bash
composer install
```

4. Configure your environment variables by copying the .env.example file to .env:

```bash
cp .env.example .env
```

5. Generate application key:

```bash
php artisan key:generate
```

6. Update the database credentials in the .env file to match your local environment.
Then Run migrations to create the necessary tables:
7. 
```bash
php artisan migrate
```

```bash
php artisan db:seed
```

```bash
php artisan serve
```

# Usage
To start the development server, run:

```base 
php artisan serve
```
This will start a development server at http://localhost:8000.

You can now test the API endpoints using tools like Postman or cURL.

# API Endpoints
GET /api/products: Fetch all products
POST /api/products: Create a new product
GET /api/products/{id}: Fetch a specific product
PUT /api/products/{id}: Update a specific product
DELETE /api/products/{id}: Delete a specific product

Replace {id} with the ID of the product you want to perform operations on.

# Authentication

This demo includes basic authentication using Laravel's built-in authentication system. To access protected endpoints, you need to obtain a valid token by logging in:

POST /api/login: Authenticate user and receive token
Include the obtained token in the request headers with key Authorization and value Bearer {token} to access protected endpoints.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

# License
This project is open-sourced software licensed under the [MIT license](LICENSE).


This README provides a comprehensive guide for setting up, using, and contributing to the Laravel 11 Rest API demo project. Adjustments can be made as necessary depending on the specifics of your project.


# References
1. https://www.itsolutionstuff.com/post/laravel-11-rest-api-authentication-using-sanctum-tutorialexample.html
2. https://medium.com/@1415sandalanka/laravel-11-rest-api-crud-with-best-practices-fcc26505e0d2
