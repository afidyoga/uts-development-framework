# How to Use

1. Clone Repository:
```
git clone https://github.com/afidyoga/uts-development-framework
```

2. Go into the repository:
```
cd uts-development-framework
```

3. Install Packages:
```
composer install
```

4. Copy ``.env`` file:
```
cp .env.example .env
```

5. Generate app key:
```
php artisan key:generate
```

6. Setting up your database credentials in your ``.env`` file.

7. Seed Database:
```
php artisan migrate:fresh --seed
```

8. Create Storage Link:
```
php artisan storage:link
```

9. Install NPM dependencies:
```
npm install && npm run dev
```

10. Run:
```
php artisan serve
```

11. Try login with email:
```
admin@admin.com
```
and password:
```
password
```
