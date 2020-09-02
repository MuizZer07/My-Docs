### Create new project
```
$ php composer.phar create-project --prefer-dist cakephp/app:4.* PROJECT_NAME
```

### Run server
```
$ bin/cake server
```

## Following 3 commands will generate:
 - The Table, Entity, Fixture files.
 - The Controller
 - The CRUD templates.
 - Test cases for each generated class

### Create new model
```
$ bin/cake bake model MODEL_NAME
```

### Create new controller
```
$ bin/cake bake controller CONTROLLER_NAME
```

### Create new template
```
$ bin/cake bake template TEMPLATE_NAME
```

### Or, simply this one command
```
$ bin/cake bake all MODEL_NAME
```

### Create migrations
```
$ bin/cake bake migration CreateProduct name:string price:float created modified
```

### Run migrations
```
$ bin/cake migrations migrate
```

### Create a seed file (dummy data)
```
$ bin/cake seed --data Users
```

### Run seed file
```
$ bin/cake migrations seed
```

### Role back migrations
```
$ bin/cake migrations roleback
```

### Install new package
```
$ composer require PACKAGE_NAME
```

### load new plugin
```
$ bin/cake plugin load -b PLUGIN_NAME
$ bin/cake plugin load -b RestApi
```
