<div align="center">

[![Laravel](https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg)](https://laravel.com)

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

</div>

# Laravel-todo-app

This is a basic to-do app with authentication created as part of a tutorial for beginners to understand and learn Laravel concepts. You can find the tutorial [here](https://www.parthpatel.net/laravel-tutorial-for-beginner/).

Assuming you have already installed composer in your system (your local computer or server), you can clone this app by running the following command:

```bash
git clone https://github.com/parthp1808/Laravel-todo-app.git
```

Alternatively, you can simply download the zip file and unzip it.

Once you're inside the folder, run composer by executing:

```bash
composer install
```

Then, run the following command:

```bash
cp .env.example .env
```

Now, you'll need to edit the `.env` file. Replace the following lines:

```plaintext
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret
```

With this:

```plaintext
DB_CONNECTION=sqlite
```

Next, go to the database folder and create a new file named `database.sqlite` (ensure the extension is `.sqlite`, not `.txt`).

Finally, run:

```bash
php artisan migrate
```
