# 🛒 Aplikasi Lelang Barang

Aplikasi lelang barang berbasis **PHP Native** dengan sistem sederhana namun tetap fungsional.  
Aplikasi ini memungkinkan **penjual** untuk membuat lelang, **pembeli** untuk melakukan penawaran (bid), dan sistem akan menentukan **pemenang otomatis** setelah lelang ditutup.

---

## 🚀 Fitur Utama

### 🔐 Autentikasi Pengguna
- Login & Registrasi
- Role: Penjual & Pembeli

### 📦 Manajemen Lelang
- Tambah, edit, hapus lelang
- Upload gambar barang
- Atur harga awal & waktu mulai/berakhir

### 💸 Sistem Bidding
- Pembeli dapat memberikan penawaran harga
- Riwayat penawaran tersimpan
- Penawaran tertinggi diperbarui real-time (sederhana)

### 🏆 Penentuan Pemenang
- Lelang ditutup otomatis sesuai jadwal
- Pemenang = penawar dengan harga tertinggi

### 📊 Dashboard
- **Penjual**: Melihat daftar lelang & penawaran
- **Pembeli**: Melihat lelang yang diikuti & hasilnya

### ⭐ Review & Rating
- Memberi ulasan & penilaian terhadap penjual/pembeli

---

## 🗂️ Struktur Repository
- `config.php` → Konfigurasi database  
- `login.php` & `register.php` → Autentikasi  
- `buyer/` → Halaman khusus pembeli  
- `seller/` → Halaman khusus penjual  
- `assets/` → CSS, JS, dan gambar  
- `diagram.png` → Diagram sistem (ERD / Flow)  

---

## 📌 Diagram
![Diagram Sistem](diagram.png)

---

## ⚙️ Teknologi yang Digunakan
- **PHP Native**
- **MySQL/MariaDB**
- **Bootstrap 5** (UI sederhana & responsif)

---

## 🎯 Tujuan
Proyek ini dibuat sebagai implementasi sistem lelang online sederhana, yang dapat dikembangkan lebih lanjut menjadi platform skala besar.

---

✍️ *Dibuat dengan semangat belajar & berbagi* 🚀
