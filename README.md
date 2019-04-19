


## Installation

```
composer require zngue/laravel_create_composer_plugin
```

Register the service provider to the current project (Not needed if using laravel 5.5+):

```
ConsoleTVs\Bootpack\BootpackServiceProvider::class
```

Publish the configuration:

```
php artisan vendor:publish
```

## Usage

Can't be more simple... rename test/package to the vendor/packagename notation you wish to create.

Example: consoletvs/bootpack

```
php artisan zng:add test/package
```


