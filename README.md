
# Laravel 8 Authentication with Breeze Tutorial

## Steps

    Installation of Laravel Application
    Install Breeze
    Run Migration
    Breeze Authentication Controllers
    Breeze Authentication Routes
    Breeze Authentication Views
    Application Testing

### Installation of Laravel Application

  Laravel Installer

	$ composer global require laravel/installer
    $ laravel
    $ laravel new blog

        OR

  By using composer

  	$ composer create-project --prefer-dist laravel/laravel blog

To start the development server of Laravel 
  	
  	$ php artisan serve

  	This command outputs: -

  	Starting Laravel development server: http://127.0.0.1:8000

Assuming laravel already installed at system.

Database also configured with application.

## Install Breeze

	$ composer require laravel/breeze --dev

Now, to install laravel breeze for simple auth scaffolding.

	$ php artisan breeze:install

After this command need to run the command

	$ npm install && npm run dev

## Run Migration

	$ php artisan migrate

Look and check in project:

Breeze Authentication Controllers

	Authentication controller we can find into the path /app/Http/Controllers/Auth

Breeze Authentication Routes

	Application routes configuration we can find into the directory /routes. File name is auth.php. 

Have a look.

web.php -> require DIR.’/auth.php’;

Breeze Authentication Views

Blade template files after generating breeze scaffolding we can find at path /resources/views/auth

### Application Testing
	$ php artisan serve

On Browser type: 
   URL – 127.0.0.1:8000

In Last check 'Login' & 'Register'


:+1:
