# Laravel — EDGE Training Exercises

PHP/Laravel coursework from the EDGE training program at RUET.

## Current implementation

- Laravel 11 skeleton with PHP 8.2 or later.
- `/` renders the welcome view.
- `/users` renders a small example user list through Blade.
- The `explore-views` branch preserves additional course work.

## Setup

Install PHP 8.2+, Composer and Node.js, then:

```bash
composer install
```

Copy `.env.example` to `.env`, configure a local database and run:

```bash
php artisan key:generate
php artisan migrate
npm ci
npm run dev
```

In another terminal run `php artisan serve`. This is training code, not a complete production application.

## Source map

- `routes/web.php`: web routes.
- `resources/views/`: Blade views.
- `app/Models/User.php`: Laravel user model.
- `tests/`: example test scaffolding.

The Laravel framework is MIT-licensed; original framework documentation is retained in `docs/README.previous.md`.
