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

### Initiate laravel default authentication
```
$ php artisan make:auth
```

### See route list
```
$ php artisan route:list
```

### Create new controller
```
$ php artisan make:controller NEW_CONTROLLER
```

### Create new model
```
$ php artisan make:model MODEL_NAME
```

### Create Migrations
```
$ php artisan make:migration create_users_table --create=users
```

### Fixing models
```
$ php artisan fix
```

### Running jobs from queue
```
$ php artisan queue:listen database --queue=agendas,polls,meetings,correspondences,emails,default,test --sleep=5 --tries=2
```
