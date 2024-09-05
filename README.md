# NULL Laravel Shop

## Overview

Welcome to the **NULL Laravel Shop** repository. This project represents a fully functional e-commerce website developed using the Laravel framework. It was originally created as part of my IT graduation internship, focusing on delivering a comprehensive online shopping experience. 

The project includes essential features such as product display, shopping cart management, online payment integration, AI-powered sales analysis and customer consulting, and user account management.

## Features

- **Product Management**: Add, edit, and delete products, complete with images, descriptions, and prices.
- **Shopping Cart**: Users can add items to their cart, modify quantities, and proceed to checkout.
- **Order Management**: Manage customer orders with options to view, confirm, and cancel orders.
- **Payment Gateway Integration**: Support for secure online payments.
- **AI Integration**: Leverage AI for customer consulting (recommendations, assistance) and sales analysis.
- **User Authentication**: Registration, login, and account management for customers.
- **Admin Dashboard**: Admin access to manage products, users, and monitor sales performance.
- **Responsive Design**: Optimized for use on mobile and desktop devices.

## Requirements

- PHP >= 7.4
- Composer
- MySQL >= 5.7
- Web server (Apache/Nginx)

## Installation

1. **Clone the repository**:
   ```
   git clone <repository_url>
   ```

2. **Navigate into the project directory**:
   ```
   cd NULL-LaravelShop
   ```

3. **Copy `.env.example` to `.env`**:
   ```
   cp .env.example .env
   ```

4. **Configure your environment**: 
   Update the `.env` file with your database credentials and other environment settings.

5. **Install dependencies**:
   ```
   composer install
   ```

6. **Generate an application key**:
   ```
   php artisan key:generate
   ```

7. **Run database migrations**:
   ```
   php artisan migrate
   ```

8. **Seed the database** (optional):
   ```
   php artisan db:seed
   ```

9. **Start the application**:
    ```
    php artisan serve
    ```

## Project Structure

- **app/**: Core business logic, models, and services.
- **config/**: Configuration files for various services and the application.
- **database/**: Migrations and seeds.
- **public/**: Frontend assets accessible to users (CSS, JS, images).
- **resources/**: Blade templates, Sass, and frontend files.
- **routes/**: Application routes.
- **storage/**: File storage, including logs and uploaded files.
- **tests/**: Unit and feature tests.

## Demos

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/1.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/2.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/3.png)

![Demo](hhttps://null-command.github.io/NULL-LaravelShop/demos_resources/4.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/5.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/6.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/7.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/8.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/9.png)

![Demo](https://null-command.github.io/NULL-LaravelShop/demos_resources/10.png)