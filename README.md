# ☕ CafePOS — Cafe Management System

<div align="center">

**Sistem Point of Sale (POS) Fullstack untuk Kafe dan UMKM**

[![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react\&logoColor=white)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Build-Vite-646CFF?logo=vite\&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Style-Tailwind_CSS-38B2AC?logo=tailwind-css\&logoColor=white)](https://tailwindcss.com/)
[![Laravel](https://img.shields.io/badge/Backend-Laravel_11-FF2D20?logo=laravel\&logoColor=white)](https://laravel.com/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql\&logoColor=white)](https://www.mysql.com/)

</div>

---

## 📖 Tentang Proyek

**CafePOS** adalah aplikasi **Point of Sale (POS)** berbasis web yang dikembangkan untuk membantu operasional **kafe, coffee shop, dan UMKM**. Repository ini berisi **frontend (React + Vite)** dan **backend API (Laravel 11)** dalam satu proyek sehingga mudah dijalankan dan dikembangkan secara bersamaan.

---

## ✨ Fitur Utama

* 🔐 **Autentikasi** menggunakan Laravel Sanctum
* 👤 **Role Admin & Kasir**
* 🛒 **Manajemen transaksi penjualan**
* 📦 **Pengurangan stok otomatis**
* 📋 **Manajemen menu dan bahan baku**
* 📊 **Dashboard penjualan**
* 🧾 **Riwayat transaksi**
* 🕒 **Absensi karyawan (check-in/check-out)**
* 📱 **Desain responsif**

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* React Router DOM
* Axios

### Backend

* Laravel 11
* PHP 8.2+
* Laravel Sanctum
* MySQL

---

## 📁 Struktur Repository

<CodeBlock language="text" content="cafe-management-system/
├── frontend/        # React + Vite
├── backend/         # Laravel API
└── README.md"/>

---

# 🚀 Instalasi

## Clone Repository

<CodeBlock language="bash" content="git clone https://github.com/johanes-dotcom/cafe-management-system.git
cd cafe-management-system"/>

---

## Menjalankan Backend

<CodeBlock language="bash" content="cd backend
composer install
cp .env.example .env
php artisan key:generate"/>

### Konfigurasi database (`.env`)

<CodeBlock language="env" content="DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_cafepos
DB_USERNAME=root
DB_PASSWORD="/>

### Migrasi dan jalankan server

<CodeBlock language="bash" content="php artisan migrate
php artisan db:seed
php artisan serve"/>

Backend berjalan di: **http://127.0.0.1:8000**

---

## Menjalankan Frontend

Buka terminal baru:

<CodeBlock language="bash" content="cd frontend
npm install
npm run dev"/>

Frontend berjalan di: **http://localhost:5173**

---

## 📌 API Endpoint Utama

<Table columnSizing="equal" rowDivider={{"size":1,"color":"default"}}><Table.Row header><Table.Cell>Method</Table.Cell><Table.Cell>Endpoint</Table.Cell><Table.Cell>Akses</Table.Cell></Table.Row><Table.Row><Table.Cell><Code value="POST"/></Table.Cell><Table.Cell><Code value="/api/login"/></Table.Cell><Table.Cell>Publik</Table.Cell></Table.Row><Table.Row><Table.Cell><Code value="POST"/></Table.Cell><Table.Cell><Code value="/api/logout"/></Table.Cell><Table.Cell>Terautentikasi</Table.Cell></Table.Row><Table.Row><Table.Cell><Code value="POST"/></Table.Cell><Table.Cell><Code value="/api/transactions"/></Table.Cell><Table.Cell>Kasir, Admin</Table.Cell></Table.Row><Table.Row><Table.Cell><Code value="GET"/></Table.Cell><Table.Cell><Code value="/api/transactions"/></Table.Cell><Table.Cell>Admin</Table.Cell></Table.Row><Table.Row><Table.Cell><Code value="GET"/></Table.Cell><Table.Cell><Code value="/api/menus"/></Table.Cell><Table.Cell>Terautentikasi</Table.Cell></Table.Row><Table.Row><Table.Cell><Code value="POST"/></Table.Cell><Table.Cell><Code value="/api/menus"/></Table.Cell><Table.Cell>Admin</Table.Cell></Table.Row></Table>

---

## 👨‍💻 Developer

**Johanes Kelvin Ge'e**

* 🌐 GitHub: https://github.com/johanes-dotcom
* 📧 Email: [johanesgee@gmail.com](mailto:johanesgee@gmail.com)

---

## 📄 License

Project ini menggunakan **MIT License** dan dikembangkan untuk keperluan pembelajaran serta pengembangan sistem Point of Sale (POS).

---

<div align="center">

⭐ **Jika proyek ini bermanfaat, jangan lupa beri Star di GitHub!**

</div>
