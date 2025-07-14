# 🩸 HemoSphere – Laravel Blood Bank Project

![Laravel](https://img.shields.io/badge/Laravel-11.x-red)
![PHP](https://img.shields.io/badge/PHP-8.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Under%20Development-orange)

> A modern blood bank platform built using Laravel 11, connecting blood donors and receivers with real-time chat.

---

## 🚀 Features

- 👤 User registration & login
- 📢 Post blood donation requests
- 💬 Real-time donor-receiver chat (using Pusher)
- 🔒 Admin login & donor management
- 📧 Email notifications for blood requests
- 📊 Admin dashboard with user stats
- 🌐 Social-style homepage with donation stories

---

## 🛠️ Built With

- **Laravel 11** (Backend Framework)
- **MySQL** (Database)
- **Blade** (Frontend Templating)
- **Pusher** (Real-Time Messaging)
- **HTML/CSS/JavaScript**

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Abubakar721/Hemoshphere-blood-bank-project-.git
cd Hemoshphere-blood-bank-project-
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
