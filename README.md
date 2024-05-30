# How to Use

1. Clone Repositori:
```
git clone https://github.com/afidyoga/uts-development-framework
```

2. Masuk ke Repositori::
```
cd uts-development-framework
```

3. Install Paket:
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

6. Setting kredensial database Anda di file ``.env`` Anda.

8. Seed Database:
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

11. Coba login dengan email::
```
admin@admin.com
```
dan password:
```
password
```
