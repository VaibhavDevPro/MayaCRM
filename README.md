# Maya CRM

<p align="center">
  <img src="public/logo.png" alt="Maya CRM Logo" width="180">
</p>

<p align="center">
  <strong>Modern, Free & Open Source CRM built with Laravel and Vue.js</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12.x-red?style=for-the-badge&logo=laravel">
  <img src="https://img.shields.io/badge/Vue.js-3.x-42b883?style=for-the-badge&logo=vue.js">
  <img src="https://img.shields.io/badge/PHP-8.2+-777BB4?style=for-the-badge&logo=php">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge">
</p>

---

# 🚀 About Maya CRM

**Maya CRM** is a modern, scalable, and open-source Customer Relationship Management (CRM) platform designed for startups, SMEs, and enterprises.

Built using the latest technologies such as **Laravel** and **Vue.js**, Maya CRM helps businesses efficiently manage the complete customer lifecycle—from lead generation to customer support.

---

# ✨ Features

- 📊 Dashboard & Analytics
- 👥 Customer Management
- 📞 Lead Management
- 📈 Sales Pipeline
- 💼 Opportunity Tracking
- 📅 Task & Activity Management
- 📧 Email Integration
- 📁 Contact Management
- 📑 Quotations & Invoices
- 📂 File Management
- 🔔 Notifications
- 👨‍💼 User Roles & Permissions
- 🌙 Dark Mode
- 🌍 Multi-language Ready
- 📱 Responsive Design
- 🔒 Secure Authentication

---

# 🛠 Tech Stack

| Technology | Version |
|------------|----------|
| Laravel | 12+ |
| Vue.js | 3 |
| PHP | 8.2+ |
| MySQL | 8+ |
| Vite | Latest |
| Tailwind CSS | Latest |

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/maya-crm.git

cd maya-crm
```

## Install Dependencies

```bash
composer install

npm install
```

## Environment Setup

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Configure your database inside **.env**

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=maya_crm
DB_USERNAME=root
DB_PASSWORD=
```

Run migrations

```bash
php artisan migrate
```

(Optional)

```bash
php artisan db:seed
```

Build frontend

```bash
npm run dev
```

Start Laravel

```bash
php artisan serve
```

Visit

```
http://127.0.0.1:8000
```

---

# 📁 Project Structure

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/
vendor/
```

---

# 🔐 Default Credentials

> Create your own admin account during installation or via database seeding.

Example

```
Email:
admin@example.com

Password:
password
```

---

# 📸 Screenshots

| Dashboard | CRM |
|-----------|-----|
| Add your screenshots here | Add your screenshots here |

---

# 📚 Documentation

Detailed documentation is available in the **docs/** directory.

---

# 🤝 Contributing

Contributions are always welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add awesome feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 🐛 Reporting Issues

Found a bug?

Please open an issue with:

- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)
- Environment details

---

# ⭐ Support

If you like this project, don't forget to give it a ⭐ on GitHub.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ❤️ Built With

- Laravel
- Vue.js
- PHP
- Vite
- Tailwind CSS

---

<p align="center">
Made with ❤️ by the Maya CRM Team
</p>
