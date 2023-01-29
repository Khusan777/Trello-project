## Quick start

#### 1. Clone project

```
git clone git@gitlab.alifshop.uz:alifuz/app-hr-laravel.git
```

#### 2. Install composer and npm:

```
composer update
composer install
```

#### 3. Generate unique application key:

```
php artisan key:generate
```

#### 4. Now we need to fill this fields in .env as in your local db. For Example:

`DB_DATABASE=trello`
`DB_USERNAME=root`
`DB_PASSWORD=`

#### 5.Run migrations and seeds:

```
php artisan migrate:fresh --seed
```


#### 6. Run npm and local server:

```
php artisan serve
```

#### 7. Run npm and local server:

```
npm install && npm run dev
```

#### 7. Dependencies in project:

```
composer require laravel/breeze --dev
php artisan breeze:install vue
```

