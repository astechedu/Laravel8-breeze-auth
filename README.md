
# Laravel 8 Authentication with Breeze

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmukjdZSQOQUSjRdzZNUXkcIhZFEFDar1wrA&usqp=CAU" width="140" height="80" alt="Laravel8 Breeze Auth">


| SNo.     | Steps      |
| ------------- | ------------- |
| 1         | Installation of Laravel Application        | 
| 2           | Install Breeze        |
| 3           | Run Migration        |
| 4           | Breeze Authentication Controllers        |
| 5           | Breeze Authentication Routes        |
| 6           | Breeze Authentication Views        |
| 7           | Application Testing        |


### 1. Installation of Laravel Application

  By Laravel Installer

	$ composer global require laravel/installer
    
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

## 2. Install Breeze

	$ composer require laravel/breeze --dev

Now, to install laravel breeze for simple auth scaffolding.

	$ php artisan breeze:install

After this command need to run the command

	$ npm install && npm run dev

## 3. Run Migration

	$ php artisan migrate

Look and check in project:

## 4. Breeze Authentication Controllers

	Authentication controller we can find into the path /app/Http/Controllers/Auth

## 5. Breeze Authentication Routes

	Application routes configuration we can find into the directory /routes. File name is auth.php. 

Have a look.

web.php -> require DIR.’/auth.php’;

## 6. Breeze Authentication Views

Blade template files after generating breeze scaffolding we can find at path /resources/views/auth

### 7. Application Testing

	$ php artisan serve

On Browser type: 
   URL – 127.0.0.1:8000

In Last check 'Login' & 'Register' links or pages


:+1:
