# 🛒 Tugas 1 PAB - Shopping Cart Enhancement



### 👩‍🎓 Identitas
**NAMA : GRACE VIES ANGEL**  
**NIM : 2409116005**  
***KELAS : A'2024***
---
## 📌 Deskripsi Project

Project ini merupakan aplikasi Shopping Cart sederhana yang dibuat menggunakan Flutter sebagai bagian dari tugas Mini Project PAB.

Aplikasi ini mensimulasikan sistem belanja online dimana user dapat melihat daftar produk, menambahkan produk ke dalam keranjang, mengatur jumlah barang, hingga melakukan checkout.

Dalam project ini, saya menerapkan konsep state management menggunakan Provider agar data keranjang dapat berubah secara real-time ketika user menambahkan, mengurangi, atau menghapus barang. Selain itu, aplikasi ini juga dilengkapi dengan fitur pencarian produk, filter berdasarkan kategori, serta halaman checkout yang memiliki form input nama dan alamat dengan validasi.

Tujuan dari project ini adalah untuk memahami bagaimana alur data dalam aplikasi Flutter bekerja, bagaimana mengelola state dengan benar, serta bagaimana membuat tampilan yang interaktif dan responsif.
---

## 🎯 Fitur Wajib (70 Poin)

### ✅ 1. Add to Cart
User dapat menambahkan produk dari halaman Product List ke dalam keranjang.

### ✅ 2. Show Cart Items dengan Quantity
Menampilkan daftar produk di dalam cart beserta jumlah (quantity).

### ✅ 3. Update Quantity (+ / -)
User dapat menambah atau mengurangi jumlah produk di dalam cart.

### ✅ 4. Remove Items
User dapat menghapus produk dari cart.

### ✅ 5. Display Total Price
Total harga dihitung otomatis berdasarkan quantity dan harga produk.

---

## ⭐ Fitur Bonus (30 Poin)

### 🔎 1. Search Produk
User dapat mencari produk berdasarkan nama.

### 🏷 2. Filter Berdasarkan Kategori
User dapat memfilter produk berdasarkan kategori:
- All
- Computer
- Mobile
- Camera
- Audio

### 🧾 3. Checkout Page (Order Summary + Form)
Halaman checkout menampilkan:
- Ringkasan total item
- Total harga
- Form input:
  - Nama lengkap
  - Alamat
- Validasi form
- Konfirmasi pesanan
- Cart otomatis kosong setelah checkout

---

## 🛠 Teknologi yang Digunakan

- Flutter
- Dart
- Provider (State Management)
- Material 3 UI

---

## 📚 Konsep yang Dipelajari

- Stateful & Stateless Widget
- State Management menggunakan Provider
- Navigation antar halaman
- Form Validation
- Dynamic UI Update
- Filtering dan Searching Data

---

## 🚀 Cara Menjalankan Project

1. Clone repository ini
2. Jalankan perintah:
   ```bash
   flutter pub get
