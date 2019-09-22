### Install existing laravel project
```
$ composer install
```

### Update Composer
```
$ composer update
```

### Composer uninstall
```
$ composer remove vender/PACKAGE_NAME
```

### Composer install any package
```
$ composer require PACKAGE_NAME
```

### Create new Laravel project with composer
```
$ composer create-project --prefer-dist laravel/laravel blog "5.8.*"
```

### Install laravel installer
```
$ composer global require laravel/installer
```

### Create new project with laravel installer
```
$ laravel new blog
```


### Local development server (http://localhost:8000)
```
$ php artisan serve
```

### Generate App key (system specific)
```
$ php artisan key:generate
```

### Migrate
```
php artisan migrate
```
