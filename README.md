## Grapql Server with Laravel

set up databse connection 

composer install

php artisan migrate

php artisan tinker

\App\Models\User::factory(10)->create()

\App\Models\Post::factory(10)->create()

\App\Models\Comment::factory(10)->create()


php artisan serve

open browser type:

{your-domain}/graphql-playground