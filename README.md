# AdminDashboard-Filament

This project is a Laravel-based Admin Dashboard using [Filament](https://filamentphp.com/). It provides a clean and powerful admin interface with role-based access control.

## 📋 Features

- Filament Admin Panel UI
- Laravel 11 framework
- Role-based user access (Admin, Editor, User)
- User authentication (Login, Register)
- CRUD for:
  - Users
  - Categories
  - Posts

## 🛠 Installation

1. **Clone the Repository**
2. composer install
3. cp .env.example .env
   php artisan key:generate
4. php artisan migrate --seed
5. php artisan serve
6. Email: admin@example.com
   Password: password

```bash
git clone https://github.com/PhoeKae/AdminDashboard-Filament.git
```
    cd AdminDashboard-Filament
```
    composer install
```
    cp .env.example .env
    php artisan key:generate
```
    php artisan migrate --seed
```
    php artisan serve
