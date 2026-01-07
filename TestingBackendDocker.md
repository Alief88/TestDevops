# DevOps Implementation
Aplikasi ini telah dikontainerisasi untuk kemudahan deployment.

# Cara Menjalankan
1. Pastikan Docker Desktop terinstal dan berjalan.
2. Jalankan perintah: `docker-compose up --build`
3. Akses API di: `http://localhost:5001/api/books`

# Fitur DevOps yang Diterapkan
- **Docker**: Menggunakan Python 3.9-slim untuk efisiensi image.
- **Docker Compose**: Orkestrasi container untuk manajemen port dan env.
- **Environment Variables**: Konfigurasi dinamis melalui file `.env`.
- **CI/CD**: GitHub Actions otomatis untuk pengecekan build.