# AdminDashboard-Filament

This project is a Laravel-based Admin Dashboard using [Filament](https://filamentphp.com/). It provides a clean and powerful admin interface with role-based access control.

<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
    </a>
</p>

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
# Clone the repo
    git clone https://github.com/PhoeKae/AdminDashboard-Filament.git

# Go into the project directory
    cd AdminDashboard-Filament/

# Install PHP dependencies
    composer install

# Copy .env file & generate app key
    cp .env.example .env
    php artisan key:generate

# Setup database (edit .env accordingly)
    php artisan migrate --seed

# Start local server
    php artisan serve
