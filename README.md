## Laravel Realtime Chat

Just a simple laravel project about realtime chat to try out the new Laravel Reverb and laravel 11 😂.

### Setup

- Git Clone
- Create .env file from .env.example
  - Adjust your DB credential and other things you need
- Composer install (PHP 8.2)
- NPM install (node v20+)
- Run :
  - `php artisan key:generate`
  - `php artisan migrate`
  - `npm run build` or `npm run dev`
  - `php artisan queue:listen`
  - `php artisan reverb:start`
  - `php artisan serve`
- Register 2 or more user
- Start texting each other 😝!!!
