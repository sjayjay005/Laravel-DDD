# Laravel-DDD
Laravel Domain Driven Design base structure

Laravel version 6.*

## Installation
1. Change the default app namespace
```php artisan app:name NAME```

## PHP artisan commands

When you want to use php artisan commands, include the namespace.

<strong>Example commands:</strong>
```
php artisan make:event APPNAME\Domain\Auth\Events\UserRegistered
php artisan make:listener APPNAME\Domain\Auth\Listeners\SendWelcomeEmail
```


