📘 SISTEM INFORMASI SISWA — Web Akademik Sekolah

Sistem Informasi Siswa adalah aplikasi berbasis Laravel yang dirancang untuk membantu sekolah mengelola data siswa, guru, kelas, mata pelajaran, jadwal, dan nilai secara modern, cepat, dan terstruktur.

Aplikasi ini dibuat agar proses administrasi sekolah menjadi lebih efisien, rapi, aman, dan memiliki tampilan UI yang nyaman digunakan.


---

✨ Fitur Utama

🧑‍🏫 Manajemen Siswa

CRUD siswa (tambah, edit, hapus, detail)

Statistik gender otomatis

Statistik jumlah siswa per kelas



🏫 Manajemen Kelas

CRUD kelas

Menampilkan daftar siswa per kelas


📚 Manajemen Mata Pelajaran

CRUD mata pelajaran

Relasi mapel ↔ guru & jadwal


🗓️ Manajemen Jadwal Pelajaran

CRUD jadwal

Penjadwalan otomatis berdasarkan kelas & mapel


📊 Dashboard Statistik

Grafik jumlah siswa

Statistik gender

Rekap data akademik sekolah



---

💻 Teknologi yang Digunakan

Teknologi	Keterangan

Laravel 10+	Framework utama backend
PHP 8.2+	Bahasa pemrograman
MySQL / MariaDB	Database
Blade Template	Sistem view
Bootstrap 5	UI & styling
Chart.js	Grafik dashboard
Composer	Dependency manager



---

🛠️ Cara Clone & Menjalankan Sistem

1️⃣ Install Git

Download Git:
https://git-scm.com/downloads

Cek instalasi:

git --version


---

2️⃣ Install Composer

Composer diperlukan untuk dependency Laravel.
Download:
https://getcomposer.org/download/

Cek:

composer --version


---

3️⃣ Install PHP & XAMPP

Download:
https://www.apachefriends.org/

Gunakan PHP 8.2 atau lebih baru

Aktifkan Apache & MySQL



---

4️⃣ Clone Repository

git clone https://github.com/HADY2006-hdy/Sistem-Informasi-Siswa.git
cd Sistem-Informasi-Siswa


---

5️⃣ Install Dependency Laravel

composer install


---

6️⃣ Konfigurasi Environment

Copy file .env:

cp .env.example .env

Edit .env:

DB_DATABASE=db_siswa
DB_USERNAME=root
DB_PASSWORD=

Buat database: db_siswa di phpMyAdmin.


---

7️⃣ Generate Key Laravel

php artisan key:generate


---

8️⃣ Migrasi & Seeder

php artisan migrate --seed

Seeder akan membuat akun admin otomatis.

🔐 Default Login Admin

Email: admin@gmail.com

Password: 12345678



---

9️⃣ Jalankan Server

php artisan serve

Buka pada browser:
http://127.0.0.1:8000


---

🔧 Perintah Tambahan (Jika Terjadi Error)

php artisan optimize:clear
php artisan view:clear
php artisan migrate:fresh --seed


---

👨‍💻 Kontributor

Developer Utama

HADYNATA YUSUF PRATAMA


Support & Contributor

Fidya Rahayu

Melin Oktafiani

I Made Aditya Pramana

Irpandi
