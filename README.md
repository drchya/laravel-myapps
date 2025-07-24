<h1 align="center">✨ Laravel MyApps ✨</h1>

<p align="center">
  A modern full-stack web application built with <strong>Laravel 12</strong> and <strong>Vue 3 Starter Kit</strong>, powered by <code>Vite</code> and <code>Tailwind CSS</code>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12.x-red?style=flat&logo=laravel" />
  <img src="https://img.shields.io/badge/Vue-3.x-4FC08D?style=flat&logo=vue.js" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-38B2AC?style=flat&logo=tailwind-css" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" />
</p>

---

## 📦 Tech Stack

- **Laravel 12** – Backend API & routing
- **Vue 3 + Vite** – Frontend SPA
- **Tailwind CSS** – Utility-first CSS styling
- **Authentication** – Built-in Login, Register, and Reset Password
- **RESTful Structure** – For scalable app development

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/drchya/laravel-myapps.git
cd laravel-myapps
```

### 2. Install Backend Dependencies

```bash
composer install
```

### 3. Install Frontend Dependencies

```bash
npm install && npm run dev
```

### 4. Configure Environment

```bash
cp .env.example .env
php artisan key:generate
```

Edit `.env` and set up your database connection:
```env
DB_CONNECTION=mysql
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### 5. Run Migrations

```bash
php artisan migrate
```

---

## 🧪 Development

Start the local server:

```bash
php artisan serve
```

Open your browser: [http://localhost:8000](http://localhost:8000)

---

## 📁 Project Structure (Short Overview)

```
├── app/Http/Controllers       → Backend logic
├── resources/js/              → Vue components
├── resources/views/           → Blade views (if needed)
├── routes/web.php             → Web routes
├── routes/api.php             → API routes
├── public/                    → Front-facing assets
```

---

## 📤 Deployment

To deploy for production:

```bash
composer install --no-dev --optimize-autoloader
npm run build
php artisan config:cache
php artisan route:cache
php artisan view:cache
```

---

## 🧠 Contribution

Feel free to fork, improve, or suggest features. Pull requests are welcome!

---

## 🙏 Credits

- Built by [**Rangga Dwi Cahya**](https://github.com/drchya)
- Based on the official [Laravel Vue Starter Kit](https://github.com/laravel/vue-starter-kit)

---

## 📜 License

This project is open-sourced under the [MIT license](LICENSE).
