![actiry-pos](https://user-images.githubusercontent.com/68384962/115121239-bb106480-9fdb-11eb-9076-731d4181988b.png)

## About Actiry POS

Actiry POS is an open source project by actiry. Implementation from https://github.com/emsifa/tailwind-pos. Using different technology. Which is laravel for backend and react js for front end UI. And plus laravel authentication.

## How to run the project

- First, clone the repo.
- Run "composer install" for installing laravel packages
- Copy .env.example file to .env
- Run php artisan key:generate
- Change the database credential on .env file
- Run "php artisan migrate" command
- Run "php artisan db:seed" command
- Run "npm install" for installing npm packages
- Run "npm run dev" for development, or "npm run production" for production
- Serve the app using "php artisan serve" or using webserver like apache
- And done. App ready to use. With default credential { username: heri, password: asdf } ( created by seeder )
- 

