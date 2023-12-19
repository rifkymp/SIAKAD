<h1 align="center">Welcome to SIAKAD! 🤗</h1>

 **Github ini digunakan untuk belajar demi memenuhi tugas akhir mata kuliah Enterprise Resource Planning. 
 
## Apa itu SIAKAD?

 **Sistem Informasi Akademik (SIAKAD) adalah sistem informasi yang digunakan untuk mengelola data akademik di sebuah lembaga pendidikan, baik sekolah maupun perguruan tinggi. SIA berbasis web adalah SIA yang diakses melalui internet..**

## Note 🙏

 **Source Code ini bukan asli milik saya, Namun saya menggunakan Source Code milik https://github.com/adhiariyadi/Ticket-Laravel
	
## Fitur apa saja yang tersedia di Ticket?

-   Autentikasi Admin
-   User & CRUD
-   Jadwal & CRUD
-   Kelas & CRUD
-   Mata Pelajaran & CRUD
-   Guru & CRUD
-   Siswa & CRUD
-   Rapot
-   Dan lain-lain



## Default Account for testing

**Admin Default Account**

-   username: admin@gmail.com
-   Password: 12345678

---

## Install

1. **Clone Repository**

```bash
git clone https://github.com/rifkymp/SIAKAD.git
cd Sistem-Informasi-Akademik-Sekolah-Laravel
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel9
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

