
# E-Commerce Platform

[![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)](https://vuejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

A full-stack e-commerce web application developed as part of the Web Technology Laboratory course. This repository includes both standard frontend web templates (HTML, CSS, JavaScript) and a backend framework implementation powered by Laravel.

---

## 🛠 Tech Stack

* **Backend:** PHP, [Laravel](https://laravel.com/)
* **Frontend:** HTML5, CSS3, JavaScript, [Tailwind CSS](https://tailwindcss.com/), [Vue.js](https://vuejs.org/)
* **Build Tool:** [Vite](https://vitejs.dev/)
* **Testing:** PHPUnit

---

## 📁 Repository Structure

```text
├── app/                  # Laravel application logic (Controllers, Models, Middleware)
├── bootstrap/            # Framework bootstrap & auto-loading configuration
├── config/               # Configuration files for database, services, app, etc.
├── database/             # Database migrations, seeders, and factories
├── public/               # Public assets (images, compiled CSS/JS)
├── resources/            # Uncompiled assets, Blade views, CSS, and JS components
├── routes/               # Application route definitions (web.php, api.php, etc.)
├── storage/              # Compiled templates, file uploads, session data, and logs
├── tests/                # Automated tests (Feature and Unit tests)
│
├── index.html            # Main landing/home page template
├── shop.html             # Product catalog page template
├── product.html          # Individual product details page
├── cart1.html            # Shopping cart page
├── Checkout.html         # Checkout page template
├── about.html            # About page template
└── contact.html          # Contact page template

```

---

## 🚀 Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

Ensure you have the following installed on your environment:

* **PHP** `>= 8.0`
* **Composer**
* **Node.js** & **npm**
* **MySQL** or **PostgreSQL**

---

### Installation & Setup

1. **Clone the repository:**
```bash


```


2. **Install PHP dependencies:**
```bash
composer install

```


3. **Install Node.js dependencies:**
```bash
npm install

```


4. **Environment Configuration:**
Copy the `.env.example` file to create your `.env` configuration file:
```bash
cp .env.example .env

```


5. **Generate Application Key:**
```bash
php artisan key:generate

```


6. **Configure Database:**
Update the database settings in your `.env` file to match your local setup:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=wt_lab_db
DB_USERNAME=root
DB_PASSWORD=

```


7. **Run Database Migrations:**
```bash
php artisan migrate

```



---

## 💻 Running the Application

1. **Start the Vite development server:**
```bash
npm run dev

```


2. **Start the Laravel local development server:**
```bash
php artisan serve

```


3. Open your browser and navigate to `http://127.0.0.1:8000`.

---

## 🧪 Running Tests

To run the automated PHPUnit test suite, execute:

```bash
php artisan test

```

---

## 📄 License

This project is open-source software licensed under the [MIT License](https://www.google.com/search?q=LICENSE).

```

```
