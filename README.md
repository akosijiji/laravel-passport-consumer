# laravel-passport-consumer
Consumer app


Installation
Clone this repository. Run the following commands:

$ cd todos
$ cp .env.example .env
$ php artisan key:generate
Create your database and enter the details in your .env file. Now run the following commands:

$ php artisan migrate --seed
$ php artisan passport:install
You should see two client ID and secret pairs. Copy the secret key of the second client and paste it in the consumer/index.php file.

One final thing, make sure both directories are accessible using http. Now, if they are make sure the consumer/index.php file has the correct URLs listed.
