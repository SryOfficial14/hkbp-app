# Sistem Informasi Manajemen Gereja (HKBP Immanuel Kemang)

Aplikasi web berbasis PHP (Custom MVC) dan MySQL untuk mengelola administrasi jemaat, warta gereja, serta pencatatan keuangan (pelean & gotilon) di **HKBP Immanuel Kemang**.

🌐 **Live Demo:** [https://hkbpimmanuelkemang.web.id](https://hkbpimmanuelkemang.web.id)

  test
  username : admin
  password : 123
---

## ✨ Fitur Utama

- **Manajemen Data Jemaat:** Pengelolaan data keluarga (*data_keluarga*) dan anggota jemaat (*anggota_jemaat*).
- **Warta Jemaat Digital:** Publikasi dan arsip warta mingguan gereja (*warta*).
- **Pencatatan Keuangan:** Rekapitulasi persembahan ibadah (*pelean*) dan persembahan syukur tahunan (*gotilon*).
- **Manajemen Pengguna & Hak Akses:** Autentikasi admin/pengurus gereja (*users*).

---

## 🛠️ Teknologi yang Digunakan

- **Backend:** PHP Native (Arsitektur Custom MVC)
- **Database:** MySQL / MariaDB
- **Frontend:** HTML5, CSS3, JavaScript
- **Web Server & Routing:** Apache (`.htaccess` URL Rewriting ke direktori `public/`)
- **Infrastruktur & Keamanan:** Cloudflare (DNS & SSL/TLS Full) + InfinityFree Hosting

---

## 📁 Struktur Direktori

```text
hkbp-app/
├── app/
│   ├── config/          # Konfigurasi koneksi database (database.php)
│   ├── controllers/     # Logika pemrosesan request
│   ├── models/          # Query dan interaksi database MySQL
│   └── views/           # Antarmuka pengguna (UI)
├── public/
│   ├── assets/          # File CSS, JavaScript, dan gambar
│   └── index.php        # Entry point utama aplikasi
└── .htaccess            # Pengalihan rute otomatis ke folder public/
