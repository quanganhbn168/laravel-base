# Laravel Base Project 🚀

A highly optimized, feature-rich base Laravel boilerplate with a fully integrated Filament v5 ecosystem, designed to streamline your development process and kickstart modern web applications.

## 🌟 Core Stack

- **Framework**: [Laravel 12+](https://laravel.com)
- **Frontend Processing**: [Vite](https://vitejs.dev/)
- **CSS Framework**: [Tailwind CSS v4](https://tailwindcss.com/)
- **JavaScript Framework**: [Alpine.js](https://alpinejs.dev/)
- **API Authentication**: [Laravel Sanctum](https://laravel.com/docs/11.x/sanctum)

## 🛠 Admin Panel & Packages (Filament v5 Ecosystem)

This boilerplate comes pre-configured with the complete [Filament](https://filamentphp.com/) web and administration ecosystem:

- **Filament Core v5**: Robust, dynamic admin panel setup out-of-the-box.
- **Filament Shield**: Advanced role and permission management using `spatie/laravel-permission`. Includes a pre-configured `super_admin` role.
- **Spatie Media Library Plugin**: Elegant file and media uploads integrated seamlessly into your Filament forms and tables.
- **Spatie Laravel Settings Plugin**: Global application settings manager stored in the database, integrated with Filament pages.

## 🚀 Getting Started

1. Clone this repository.
2. Ensure you have PHP 8.2+, Node, and MySQL installed.
3. Install dependencies:
    ```bash
    composer install
    npm install
    ```
4. Set up your `.env` file according to `.env.example` and run migrations along with the database seeders:
    ```bash
    php artisan migrate --seed
    ```

## 🔑 Default Credentials

To access the `/admin` filament panel, use the pre-seeded super-admin account (which is automatically generated when you run the seed command above):

- **Email:** `admin@example.com`
- **Password:** `password`

## ✨ Building Assets

With Tailwind CSS v4 and AlpineJS fully integrated, compile your assets by running:
```bash
npm run dev
# or for production:
npm run build
```

---
*Created by [quanganhbn168](https://github.com/quanganhbn168)*
