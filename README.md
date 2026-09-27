# CRUD Project – Manage Posts and Pages

A simple Laravel CRUD application for managing posts and pages using standard **Create, Read, Update, and Delete (CRUD)** operations.

## 🚀 Features

* **Create** – Add new posts.
* **Read** – View existing posts.
* **Update** – Edit and update posts.
* **Delete** – Remove posts.
* Simple and clean Laravel structure.
* MySQL database integration.
* Blade templates for the user interface.

## 🛠️ Technologies

* **PHP**
* **Laravel**
* **MySQL**
* **Blade**
* **Vite**
* **HTML / CSS / JavaScript**

## 💻 Quick Start

### 1. Clone the Repository

```bash
git clone git@github.com:Hejran2004/Manage-Postsand-Page.git
cd Manage-Postsand-Page
```

### 2. Install PHP Dependencies

```bash
composer install
```

### 3. Install Frontend Dependencies

```bash
npm install
```

### 4. Configure Environment

Copy the `.env.example` file and create a `.env` file:

```bash
cp .env.example .env
```

On Windows, you can also create a copy manually:

```text
.env.example → .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Configure Database

Open the `.env` file and configure your MySQL database:

```env
DB_DATABASE=db_belajar_laravel
DB_USERNAME=root
DB_PASSWORD=
```

Make sure the database below exists in MySQL:

```text
db_belajar_laravel
```

### 7. Run Database Migrations

```bash
php artisan migrate
```

### 8. Start the Laravel Development Server

```bash
php artisan serve
```

The application will be available at:

```text
http://127.0.0.1:8000
```

### 9. Open the Posts Page

Posts can be accessed at:

```text
http://127.0.0.1:8000/posts
```

## 🗄️ Database Information

| Setting         | Value                         |
| --------------- | ----------------------------- |
| Database Name   | `db_belajar_laravel`          |
| Database Type   | MySQL                         |
| Application URL | `http://127.0.0.1:8000/posts` |

## 📁 Project Structure

```text
Manage-Postsand-Page/
├── app/
│   ├── Http/
│   └── Models/
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   └── seeders/
├── public/
├── resources/
│   ├── css/
│   ├── js/
│   └── views/
│       └── posts/
├── routes/
├── storage/
├── tests/
├── artisan
├── composer.json
├── package.json
└── vite.config.js
```

## 🔗 Application

**Posts URL:**

```text
http://127.0.0.1:8000/posts
```

**Database:**

```text
db_belajar_laravel
```

## 👨‍💻 Author

**Nasir Hejran**

GitHub: `Hejran2004`

