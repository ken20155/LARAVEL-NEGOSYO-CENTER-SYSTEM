Laravel Negosyo Center System

A Laravel-based web application designed to manage Negosyo Center operations, including MSME/client registration, business assistance tracking, reporting, and administrative workflows. The system aims to help Negosyo Centers efficiently organize data and improve service delivery.

✨ Features

MSME / Client Registration & Profiling

Business Assistance & Service Tracking

User Authentication & Authorization

Role-Based Access Control (Admin / Staff)

Dashboard with statistical summaries

Reports (Monthly, Quarterly, Yearly)

CRUD management for system modules

Secure data handling

🛠️ Technology Stack

Framework: Laravel

Language: PHP

Database: MySQL / SQL Server

Frontend: Blade Templates + Bootstrap 5

Authentication: Laravel Authentication

Server: Apache / IIS

📂 Project Structure

laravel-negosyo-center-system/

app/

Http/

Models/

Services/

Repositories/

bootstrap/

config/

database/

migrations/

seeders/

public/

resources/

views/

css/

js/

routes/

web.php

api.php

storage/

tests/

README.md

⚙️ System Requirements

PHP 8.1 or higher

Composer

Node.js & NPM

MySQL or SQL Server

Web Server (Apache / IIS)

🚀 Installation Guide
1. Clone the Repository
git clone https://github.com/your-username/laravel-negosyo-center-system.git
cd laravel-negosyo-center-system

2. Install Dependencies
composer install
npm install
npm run build

3. Environment Setup
cp .env.example .env
php artisan key:generate


Update the database credentials in the .env file.

4. Run Database Migrations
php artisan migrate


(Optional)

php artisan db:seed

5. Run the Application
php artisan serve


Access the application at:
👉 http://127.0.0.1:8000

👥 User Roles

Admin

Full system access

User and module management

Staff

Client registration

Business assistance tracking

Report generation

🔒 Security

CSRF protection

Encrypted password storage

Role-based authorization

Laravel built-in security features

🧪 Testing
php artisan test

📈 Future Enhancements

PDF and Excel report exports

Email and SMS notifications

Audit trail and activity logs

REST API integration

Mobile-friendly UI improvements

🤝 Contributing

Fork the repository

Create a feature branch

Commit your changes

Submit a pull request

📬 Contact

For questions, suggestions, or collaboration inquiries:

📧 kenneth.tanuron@gmail.com

📄 License

This project is licensed under the MIT License.
