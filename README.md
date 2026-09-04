# 📚 Perpustakaan Digital Daerah (PERPPUS DAERAH)

Website landing page dan dokumentasi untuk **Sistem Manajemen Perpustakaan Digital Daerah** - aplikasi web untuk pengelolaan perpustakaan sekolah modern.

🌐 **Live Demo:** https://farahquinn14528-ui.github.io/

📦 **Repository Utama:** https://github.com/farahquinn14528-ui/perppus_daerahukk

## 📖 Tentang

PERPPUS DAERAH adalah sistem manajemen perpustakaan berbasis web yang dirancang khusus untuk kebutuhan perpustakaan sekolah. Dengan fitur-fitur lengkap dan user interface yang intuitif, sistem ini memudahkan pengelolaan:

- 📚 Koleksi buku
- 👥 Data anggota/siswa
- 🔄 Peminjaman & pengembalian
- 💰 Manajemen denda
- 📊 Laporan transaksi
- ⭐ Rating & komentar buku

## ✨ Fitur Utama

### 👨‍🎓 Untuk Siswa
- Registrasi & login akun
- Cari buku di katalog
- Pinjam dan kembalikan buku
- Lihat riwayat peminjaman
- Rating & komentar buku
- Bayar denda online
- Lihat profil & status peminjaman

### 👨‍💼 Untuk Petugas
- Manajemen data buku (CRUD)
- Persetujuan peminjaman
- Kelola anggota/siswa
- Cetak struk & laporan
- Monitor transaksi
- Set kondisi fisik buku

### 👨‍💻 Untuk Admin
- Kelola semua transaksi
- Atur tarif denda
- Manajemen petugas & admin
- Dashboard statistik lengkap
- Laporan komprehensif
- Pengaturan sistem

## 🛠️ Tech Stack

| Bagian | Teknologi |
|--------|----------|
| **Backend** | PHP (MVC Framework) |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Database** | MySQL / MariaDB |
| **Security** | Authentication, CSRF Protection, Password Hashing |

## 🚀 Quick Start

### Prasyarat
- PHP >= 7.4
- MySQL / MariaDB
- Composer (opsional)
- Git

### Instalasi Lokal

```bash
# Clone repository
git clone https://github.com/farahquinn14528-ui/perppus_daerahukk.git
cd perppus_daerahukk

# Setup database
# 1. Buat database baru
# 2. Import file schema dari folder database/
# 3. Update konfigurasi koneksi di app/Config/database.php

# Jalankan aplikasi
php -S localhost:8000
# Akses: http://localhost:8000
```

## 📁 Struktur Project

```
perppus_daerahukk/
├── app/
│   ├── Core/          # Framework core (Router, Request, Response, etc)
│   ├── Config/        # Konfigurasi aplikasi
│   ├── Controllers/   # Request handlers
│   ├── Models/        # Database models
│   ├── Services/      # Business logic
│   ├── Repositories/  # Data access
│   ├── Middleware/    # Route middleware
│   ├── Helpers/       # Helper functions
│   └── Exceptions/    # Custom exceptions
├── routes/            # Route definitions
├── public/            # Static files (CSS, JS, images)
├── resources/         # Views & templates
├── database/          # Schema & migrations
├── storage/           # Cache, logs, sessions
├── tests/             # Unit & integration tests
└── docs/              # Documentation
```

## 🔐 Security

- ✅ Password hashing dengan bcrypt
- ✅ CSRF protection untuk form
- ✅ Authentication & authorization
- ✅ Input validation
- ✅ SQL injection prevention
- ✅ XSS protection

## 📝 Lisensi

Proyek ini open source dan tersedia untuk penggunaan pendidikan.

## 👤 Penulis

**farahquinn14528-ui** - [GitHub Profile](https://github.com/farahquinn14528-ui)

## 📞 Support

Untuk pertanyaan atau laporan bug, silakan buka [issue](https://github.com/farahquinn14528-ui/perppus_daerahukk/issues) di repository utama.

---

**Made with ❤️ for Digital Library**