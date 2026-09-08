# Personal Website — Qeisya Dwi Hermawan

Website pribadi sederhana yang dibangun menggunakan **HTML dasar** (tanpa CSS/JavaScript) sebagai media untuk memperkenalkan diri, menampilkan portofolio project, dan menyediakan sarana kontak.

## 📖 Tentang Project

Website ini dibuat sebagai bagian dari latihan pembelajaran HTML, dengan struktur multi-halaman yang saling terhubung melalui navigasi. Setiap halaman berdiri sendiri namun tetap konsisten dalam layout dan gaya penulisan.

## 🗂️ Struktur Halaman

| Halaman | File | Deskripsi |
|---|---|---|
| Home | `home.html` | Halaman utama berisi sambutan, perkenalan singkat, dan daftar hal yang sedang dipelajari |
| About | `about.html` | Profil singkat, data diri (NIM, program studi, semester, email), hobi, dan riwayat pendidikan |
| Project | `project.html` | Daftar portofolio project yang pernah dikerjakan beserta tabel ringkasan teknologi dan status |
| Contact | `contact.html` | Form kontak (nama, email, telepon, topik pesan, dll.) untuk keperluan diskusi atau kerja sama |

Navigasi antar halaman tersedia di bagian atas setiap halaman:
`Home | About | Project | Contact`

## 👤 Profil

- **Nama:** Qeisya Dwi Hermawan
- **NIM:** 2501675
- **Program Studi:** Pendidikan Sistem dan Teknologi Informasi
- **Semester:** 3
- **Universitas:** Universitas Pendidikan Indonesia
- **Email:** qeisyadwihermawan@student.upi.edu

## 💻 Teknologi yang Digunakan

- HTML
- CSS
- Python
- MySQL
- Java
- Git
- Figma
- Sensor (untuk project berbasis hardware)

## 📁 Daftar Project yang Ditampilkan

1. **Game Kreswara** — Game interaktif edukatif seputar problem solving dan pemrograman (peran: tim administrasi)
2. **Vending Machine** — Prototype alat penjual makanan ringan sederhana
3. **Prototype Miniatur Taman dengan Lampu Otomatis Berbasis LDR** — Sistem lampu otomatis berdasarkan sensor cahaya
4. **Westra** — Sistem belanja online oleh-oleh khas Jawa Barat (peran: tim administrasi)
5. **Sistem Data Pribadi** — Latihan penyimpanan dan penampilan data pribadi *(dalam pengembangan)*

## 🚀 Cara Menjalankan

Karena website ini murni HTML statis, tidak diperlukan instalasi atau server khusus:

1. Clone atau download repository ini
2. Buka file `home.html` langsung menggunakan browser (Chrome, Firefox, Edge, dll.)
3. Navigasikan ke halaman lain melalui menu di bagian atas

```bash
git clone <url-repository-ini>
cd <nama-folder>
# buka home.html di browser
```

## ⚠️ Catatan

- Website ini dibuat murni menggunakan HTML tanpa styling CSS, sehingga tampilan masih sangat sederhana (default browser).
- Form pada halaman **Contact** belum terhubung ke server/database, sehingga input pesan belum benar-benar terkirim.
- Beberapa gambar pada halaman Home dan Project masih menggunakan path lokal (`C:\Users\...`) sehingga **tidak akan tampil** saat dibuka dari komputer lain atau di-hosting online. Disarankan memindahkan gambar ke dalam folder project (misalnya `assets/images/`) dan mengubah path menjadi relatif, contoh:
  ```html
  <img src="assets/images/game.png" width="250">
  ```

## 📌 Rencana Pengembangan

- [ ] Menambahkan styling CSS agar tampilan lebih menarik
- [ ] Memperbaiki path gambar menjadi relatif agar bisa tampil di GitHub Pages
- [ ] Menghubungkan form contact ke backend/database
- [ ] Menambahkan responsive design untuk tampilan mobile

## 📄 Lisensi

© 2026 Qeisya Dwi Hermawan. Project ini dibuat untuk keperluan pembelajaran.
