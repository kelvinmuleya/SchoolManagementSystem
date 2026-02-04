<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# School Management System

A **Laravel 10** web application for managing school operations.  
This system allows administrators and staff to manage:

- Students  
- Teachers  
- Classes  
- User authentication and roles  

It provides a clean, intuitive interface for day-to-day school management tasks.

---

## Features

- **User Authentication**: Register, login, and manage user roles  
- **Students Management**: Add, update, delete, and list students  
- **Teachers Management**: Add, update, delete, and list teachers  
- **Class Management**: Assign students and teachers to classes  
- **Database-backed**: Powered by MySQL (configurable in `.env`)  
- **Responsive Frontend**: Built with Laravel Breeze and Tailwind CSS  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/kelvinmuleya/SchoolManagementSystem.git
cd SchoolManagementSystem

2. Install dependencies
composer install
npm install
npm run dev

3. Copy .env.example to .env and configure your database:
cp .env.example .env
php artisan key:generate

4. Run
Run migrations:
php artisan migrate

5.Start the local development server:
php artisan serve
