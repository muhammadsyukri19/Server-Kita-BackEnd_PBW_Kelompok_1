# Server-Kita-BackEnd_PBW_Kelompok_1

**ServerKita** adalah sistem penyewaan server berbasis web yang dikembangkan sebagai proyek kelompok untuk mata kuliah Pemrograman Berbasis Web. Aplikasi ini menyediakan layanan CRUD dasar, termasuk pengelolaan akun, penyewaan server, dan pengelolaan profil pengguna.

## 📦 Teknologi yang Digunakan

- **Node.js** + **Express.js** (REST API)
- **MongoDB** (Database)
- **Mongoose** (ODM untuk MongoDB)
- **dotenv** (Pengelolaan environment variable)
- **CORS**, **Helmet**, dan middleware lainnya untuk keamanan dasar

## ⚙️ Fitur Utama

| Fitur | Role | Deskripsi |
|-------|------|-----------|
| 🧑‍💼 Tambah akun | Admin | Menambahkan akun pengguna baru ke sistem |
| 👁️ Lihat daftar server | User | Menampilkan daftar server yang tersedia |
| ❌ Hapus akun | Admin | Menghapus akun pengguna dari sistem |
| ✏️ Edit profil | User | Memperbarui data profil pribadi pengguna |
| 🏠 Landing Page | Umum | Halaman utama aplikasi saat pertama diakses |

## 📁 Struktur Folder

```bash
server-kita-backend/
│
├── config/           # Konfigurasi database dan environment
├── controllers/      # Logika dari setiap endpoint
├── models/           # Schema MongoDB
├── routes/           # Routing API
├── middlewares/      # Middleware tambahan (auth, logging, dll)
├── .env              # Environment variables
├── server.js         # Entry point aplikasi
└── README.md         # Dokumentasi ini
```

### Anggota Kelompok
- Muhammad Syukri - NPM: 2308107010060
- Muhammad Al Azizi- NPM: 2308107010044
- Muhammad Al-Hadziq Tarmizi - NPM: 2108107010022
- Thahira Riska - NPM: 2308107010024

