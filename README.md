
# Install Laravel Project

First, open Terminal and run the following command to create a fresh laravel project:

```bash
laravel new laravel9-auth
```
OR
```bash
composer create-project --prefer-dist laravel/laravel laravel9-auth
```

# Configure Database Details
```bash
DB_CONNECTION=mysql 
DB_HOST=127.0.0.1 
DB_PORT=3306 
DB_DATABASE=
DB_USERNAME=root
DB_PASSWORD=
```
Now run the database migration command:

```bash
php artisan migrate
```

# Create Auth using Scaffold

Now, in this step, we will create auth scaffold command to create a login, register, and dashboard.

```bash
composer require laravel/ui
```

### Generate Basic Scaffolding

```bash
php artisan ui bootstrap
php artisan ui vue
php artisan ui react
```

### Generate Login / Registration Scaffolding

```bash
php artisan ui bootstrap --auth
php artisan ui vue --auth
php artisan ui react --auth
```

# Install NPM dependencies

```bash
npm install 
npm run dev
```

# Test the Authentication System

```bash
php artisan serve
```


Thank You.
