<p align="center">
    <h1 align="center">POS System Using Laravel</h1>
</p>


## Installation

### Requirements

Rename or copy `.env.example` file to `.env` 1.`php artisan key:generate` to generate app key.

1. Set your database credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file.

### Database

1. Migrate database table `php artisan migrate`
1. Generate config `php artisan db:seed`

### Install Node Dependencies(optional)

1. `npm install` to install node dependencies
1. `npm run dev` to build our javascript



### Create storage link

`php artisan storage:link`

### Run Server

1. `php artisan serve` or Laravel Homestead
1. Visit `localhost:8000` in your browser
1. Visit `/admin` if you want to access the admin. Email: `admin@mail.com`, Password: `admin`.

