# 🐦 Chirper

**Chirper** is a simple user chat and micro-posting application built with [Laravel](https://laravel.com/).  
Users can create posts (“chirps”) and engage by adding comments — similar to a minimalist social platform.

<img width="1512" height="982" alt="Screenshot 2025-10-04 at 8 24 03 AM" src="https://github.com/user-attachments/assets/cf891b50-379f-4d82-b1f2-a71b070ab0c7" />

## Features

- ✍️ **User Authentication** – Sign up, sign in, and manage user sessions securely.  
- 💬 **Post Creation** – Users can share short posts (“chirps”).  
- 💭 **Comments** – Users can comment on other posts for interaction.  
- 👤 **User Profiles** – View posts made by individual users.  
- 🧱 **Responsive UI** – Clean and modern interface built with Laravel Breeze or Inertia.  

## Tech Stack

- **Framework:** Laravel 11  
- **Frontend:** Blade / Inertia.js (React)  
- **Database:** SQLite  
- **Authentication:** Laravel Breeze or Jetstream  
- **Styling:** Tailwind CSS and Daisy UI

## Installation

Follow these steps to get the app running locally:

### Clone the repository
```bash
git clone https://github.com/danielsarkwa/laravel-chirper-app.git
cd chirper
```

### Install dependencies
```bash
composer install
npm install
npm run dev
```

### Configure environment
Copy .env.example to .env and update your environment variables:
```bash
cp .env.example .env
php artisan key:generate
```
Set up your database credentials in .env.

### Run migrations and seed data
```bash
php artisan migrate --seed
```

### Start the development server
```bash
composer run dev
```
Then open your browser and visit http://127.0.0.1:8000.
