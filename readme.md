# Laravel 5.5 / Vue 2 (VueRouter) / Bootstrap 3.3.7 SPA (NOT COMPLETED)

This is an example of [Single-Page Application](https://en.wikipedia.org/wiki/Single-page_application) site built on Laravel 5.5 and VueJS 2. Webpack used via laravel-min plugin.

## Installation

For installing you should run next commands:

* `git clone https://github.com/NMFES/laravel-vue-workers-management.git`
* `cd laravel-vue-workers-management`
* `cp .env.example .env`
* `composer install`
* `npm install`
* `php artisan key:generate`
* `php artisan storage:link`
* Edit .env and set your database connection params. Also you need to change charset=utf8 and collation=utf8_general_ci in config/database.php
* `php artisan migrate`
* `php artisan db:seed` if you want to seed database with random data

... and something else you need to do. If i forgot something :)

## Usage

``` bash
# build and watch
npm run watch (or "npm run watch-poll")

# build for production
npm run prod
```
