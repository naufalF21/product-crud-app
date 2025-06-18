<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Instalasi Project Product Crud App (Laravel 12)

## Prasyarat
- Git terinstal pada sistem Anda
- Composer terinstal pada sistem Anda
- PHP 8.2 atau yang lebih baru
- Server database (MySQL)
- Node.js dan NPM

## Langkah-langkah Instalasi

### 1. Clone Repository
```bash
git clone https://github.com/naufalF21/product-crud-app.git
cd product-crud-app
```

### 2. Install Dependency PHP
```bash
composer install
```

### 3. Konfigurasi Environment
```bash
cp .env.example .env
```

### 4. Generate Application Key
```bash
php artisan key:generate
```

### 5. Konfigurasi Database
Buka file `.env` dan sesuaikan pengaturan database:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=username
DB_PASSWORD=password
```

### 6. Jalankan Migrasi Database
```bash
php artisan migrate
```

### 7. Jalankan Database Seeders (opsional)
```bash
php artisan db:seed
```

### 8. Install Dependency Frontend
Menggunakan NPM:
```bash
npm install
```

Atau menggunakan Yarn:
```bash
yarn install
```

### 9. Jalankan Server Development
```bash
composer run dev
```

Aplikasi sekarang berjalan di [http://localhost:8000](http://localhost:8000)
