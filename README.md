# 🏝 Wisata Kebumen

Aplikasi Android modern untuk informasi wisata, pemesanan tiket digital, QR Code, review, dan validasi tiket berbasis **Google Apps Script**.

---

## 📱 Screenshot

> Tambahkan screenshot aplikasi di sini.

---
# 📲 Cara Running Aplikasi
1. Clone repository dari Github
2. Buka Project menggunakan Android Studio
3. Tunggu proses Gradle Sync selesai
4. Hubungkan emulator atau perangkat Android
5. Klik tombol run
6. Aplikasi Wisata Kebumen akan dijalankan

---

# Daftar Tech Stack dan Library

## 🛠️ TECH STACK

Frontend
- Kotlin
- Jetpack Compose
- Material Design 3

Backend
- Google Apps Script (JavaScript)
- REST API (JSON)

Database
- Google Spreadsheet

Cloud Storage
- Google Drive

Networking
- Retrofit
- OkHttp
- Gson Converter

Maps & Location
- Google Maps Compose
- Google Maps SDK
- Google Maps Intent
- GPS Location
- Distance Calculation

Camera & QR Code
- CameraX
- Google ML Kit Barcode Scanning
- ZXing Core

## 📚 Library

AndroidX
- androidx.compose
- androidx.activity.compose
- androidx.lifecycle
- androidx.navigation.compose

UI
- Material Design 3
- Jetpack Compose

Networking
- Retrofit
- OkHttp
- Gson Converter

Maps
- Google Maps Compose
- Google Maps SDK
- Google Play Services Location

Camera
- CameraX Core
- CameraX Camera2
- CameraX Lifecycle
- CameraX View

QR Code
- ZXing Core
- Google ML Kit Barcode Scanning

Backend Integration
- Google Apps Script
- Google Drive API (via Apps Script)
- Google Sheets API (via Apps Script)

# Demo Aplikasi
Link Video Demo Aplikasi : https://youtu.be/BgVSUr2yhug?si=HdBIxfBP-OaV0SXi

# ✨ Fitur

## 👤 User

- Login
- Register
- Auto Login
- Logout
- Session Login

---

## 🏝 Wisata

- Daftar Wisata
- Detail Wisata
- Search Wisata
- Filter Kategori
- Hero Image
- Rating
- Review
- Google Maps
- Navigasi
- Jarak dari lokasi pengguna

---

## ⭐ Review

- Rating Bintang
- Komentar
- Rata-rata Rating
- Total Review

---

## ❤️ Favorit

- Simpan wisata favorit
- Kelola daftar favorit

---

## 🎫 Tiket Digital

- Pemesanan Tiket
- Booking ID Otomatis
- Detail Tiket
- QR Code Tiket
- Riwayat Tiket
- Status Tiket

---

## 👮 Admin

- Login Admin
- Dashboard
- CRUD Wisata
- Upload Gambar Google Drive
- Pilih Lokasi Google Maps
- Scanner QR Code
- Validasi Tiket
- Riwayat Validasi
- Statistik Tiket

---

# 🚀 Teknologi

## Android

- Kotlin
- Jetpack Compose
- Material Design 3

## Backend

- Google Apps Script

## Database

- Google Spreadsheet

## Storage

- Google Drive

## Networking

- Retrofit
- Gson
- OkHttp

## Maps

- Google Maps Compose
- Google Maps Intent
- Google Play Location Services

## QR Code

- ZXing
- CameraX
- Google ML Kit Barcode Scanning

---

# 🗄 Struktur Database

## USER

| Kolom |
|-------|
| ID |
| Nama |
| Username |
| Password |
| Role |

---

## WISATA

| Kolom |
|-------|
| ID |
| Nama |
| Deskripsi |
| Latitude |
| Longitude |
| Image |
| Kategori |
| Harga |

---

## PEMESANAN

| Kolom |
|-------|
| Booking ID |
| Username |
| Nama Wisata |
| Nama Pemesan |
| Tanggal Kunjungan |
| Jumlah Tiket |
| Total Bayar |
| Status |
| Created At |
| Waktu Validasi |

---

## REVIEW

| Kolom |
|-------|
| ID |
| Wisata ID |
| Username |
| Nama |
| Rating |
| Komentar |
| Tanggal |

---

# 📡 API

## GET

- getWisata
- getReview
- getPemesanan
- getDetailTiket
- getSemuaTiket
- getStatistik
- getRiwayatValidasi
- getStatistikValidasi

---

## POST

- login
- register
- pesanTiket
- tambahReview
- upload
- addWisata
- updateWisata
- deleteWisata
- validasiTiket

---

# 🔐 Status Tiket

```
LUNAS
        ↓
SUDAH DIGUNAKAN
```

QR Code hanya dapat digunakan **satu kali**.

---

# 📊 Dashboard Admin

- Total Tiket
- Total Pendapatan
- Statistik Validasi
- Riwayat Scan Tiket
- CRUD Wisata
- Scanner QR

---

# ☁ Penyimpanan

- Google Spreadsheet sebagai Database
- Google Drive sebagai Storage Gambar
- Google Apps Script sebagai REST API

---

# 🎨 UI

- Material Design 3
- Jetpack Compose
- Modern Card
- Hero Image
- Responsive Layout
- Loading Animation
- Empty State
- Badge Status
- QR Ticket Screen

---

# ✅ Keunggulan

- Android Native (Kotlin)
- Backend Serverless
- Tanpa VPS
- Tanpa Hosting
- Database Gratis menggunakan Google Spreadsheet
- Upload Gambar ke Google Drive
- Google Maps Terintegrasi
- Review & Rating
- Tiket Digital QR Code
- Scanner QR Admin
- Validasi Tiket Sekali Pakai
- Dashboard Statistik
- Mudah Dikembangkan
- Biaya Operasional Sangat Rendah

---
👨‍💻 kelompok
1. Naehati Zullaikha TI1024007
2. Nova Tivany Zahro TI1024008
3. Tri Wahyudi TI1024025
4. Gilang Muhamad Arif TI1024016
5. Faiq Khusnudin TI1024014

Wisata Kebumen © 2026
