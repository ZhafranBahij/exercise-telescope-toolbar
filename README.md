# Laravel Telescope Toolbar

This repo is not Telescope Toolbar, but only me who want to try it.s

[https://x.com/MadeWithLaravel/status/1886023011960049888](https://x.com/MadeWithLaravel/status/1886023011960049888)

## Step by Step

```bash
composer require laravel/telescope
```

![image.png](readme-img//image.png)

```bash
php artisan telescope:install
```

![image.png](readme-img//image%201.png)

```bash
php artisan vendor:publish --tag=telescope-migrations
```

![image.png](readme-img//image%202.png)

If you have this case, please delete one of duplicate migration

![Please delete one of migration if duplicate](readme-img//image%203.png)

Please delete one of migration if duplicate

```bash
php artisan migrate
```

![image.png](readme-img//image%204.png)

```bash
composer require fruitcake/laravel-telescope-toolbar --dev
```

![image.png](readme-img//image%205.png)

```bash
php artisan vendor:publish --provider="Fruitcake\\TelescopeToolbar\\ToolbarServiceProvider"
```

![image.png](readme-img//image%206.png)

So, you can check it

![image.png](readme-img//image%207.png)

## Feature

![Check URL](readme-img//image%208.png)

Check URL

![Duration and memory](readme-img//image%209.png)

Duration and memory

![Check session](readme-img//image%2010.png)

Check session

![Account](readme-img//image%2011.png)

Account

![Model](readme-img//image%2012.png)

Model

![How many query in one page](readme-img//image%2013.png)

How many query in one page

![How many model in one page](readme-img//image%2014.png)

How many model in one page

![Web version and environment](readme-img//image%2015.png)

Web version and environment

## Source

[https://github.com/ZhafranBahij/exercise-telescope-toolbar](https://github.com/ZhafranBahij/exercise-telescope-toolbar)

[https://github.com/fruitcake/laravel-telescope-toolbar](https://github.com/fruitcake/laravel-telescope-toolbar)
