<h1 align="center">Welcome to SIAKAD! 🤗</h1>

 **Github ini digunakan untuk belajar demi memenuhi tugas akhir mata kuliah Enterprise Resource Planning. 
 
## Apa itu Ticket?

 **Sistem Informasi Akademik (SIAKAD) adalah sistem informasi yang digunakan untuk mengelola data akademik di sebuah lembaga pendidikan, baik sekolah maupun perguruan tinggi. SIA berbasis web adalah SIA yang diakses melalui internet..**

## Note 🙏

 **Source Code ini bukan asli milik saya, Namun saya menggunakan Source Code milik https://github.com/adhiariyadi/Ticket-Laravel
	
## Fitur apa saja yang tersedia di Ticket?

-   Autentikasi Admin
-   User & CRUD
-   Rute & CRUD
-   Transportasi & CRUD
-   Category & CRUD
-   Pemesanan Ticket
-   Dan lain-lain



## Default Account for testing

**Admin Default Account**

-   username: admin
-   Password: admin123

---

## Install

1. **Clone Repository**

```bash
git clone https://github.com/fadiiyah/MyTicket.git
cd MyTicket
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```

SELAMAT MENCOBA 😊

