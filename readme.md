Go to the folder using cmd.

1. composer:update
2. copy .env.example .env  ( create and edit env file and use your own database)
3. php artisan migrate
4. php artisan db:seed
5. php artisan key:generate
6. php artisan config:cache
7. php artisan serve
8. go to http://localhost:8000/todos and use the application

For a complete list of the routes use : php artisan route:list
