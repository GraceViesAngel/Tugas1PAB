# 🛒 Tugas 1 PAB - Shopping Cart Enhancement



### 👩‍🎓 Identitas
#### NAMA : GRACE VIES ANGEL  
#### NIM : 2409116005  
#### KELAS : A'2024
---
## 📌 Deskripsi Project

Project ini merupakan aplikasi Shopping Cart sederhana yang dibuat menggunakan Flutter sebagai bagian dari tugas Mini Project PAB.

Aplikasi ini mensimulasikan sistem belanja online dimana user dapat melihat daftar produk, menambahkan produk ke dalam keranjang, mengatur jumlah barang, hingga melakukan checkout.

Dalam project ini, saya menerapkan konsep state management menggunakan Provider agar data keranjang dapat berubah secara real-time ketika user menambahkan, mengurangi, atau menghapus barang. Selain itu, aplikasi ini juga dilengkapi dengan fitur pencarian produk, filter berdasarkan kategori, serta halaman checkout yang memiliki form input nama dan alamat dengan validasi.

Tujuan dari project ini adalah untuk memahami bagaimana alur data dalam aplikasi Flutter bekerja, bagaimana mengelola state dengan benar, serta bagaimana membuat tampilan yang interaktif dan responsif.

---

## 🎯 Fitur Wajib (70 Poin)

### ✅ 1. Add to Cart
Pada fitur ini, user bisa menambahkan produk ke dalam keranjang dengan menekan tombol Add pada halaman Product List. Setiap kali tombol ditekan, produk tersebut langsung masuk ke dalam cart. Jika produk yang sama ditambahkan lebih dari satu kali, maka sistem tidak membuat data baru, tetapi otomatis menambah jumlah (quantity) dari produk tersebut. Fitur ini memastikan proses belanja terasa seperti aplikasi e-commerce pada umumnya.


### ✅ 2. Show Cart Items dengan Quantity
Fitur ini menampilkan semua produk yang sudah dimasukkan ke dalam keranjang.

Di halaman Cart, user bisa melihat:

- Nama produk

- Harga produk

- Jumlah (quantity)

- Subtotal per produk

Dengan adanya quantity, user bisa langsung tahu berapa banyak produk yang sudah dipilih tanpa harus menghitung manual.


### ✅ 3. Update Quantity (+ / -)
User dapat menambah atau mengurangi jumlah produk langsung dari halaman Cart menggunakan tombol + dan −.

Jika tombol + ditekan, maka jumlah produk akan bertambah satu.
Jika tombol − ditekan, maka jumlah produk akan berkurang satu.

Apabila quantity dikurangi hingga 0, maka produk otomatis terhapus dari cart.

Fitur ini memudahkan user untuk mengatur jumlah belanja tanpa harus menghapus dan menambahkan ulang produk.


### ✅ 4. Remove Items
User dapat menghapus produk dari keranjang dengan menekan ikon delete. Saat tombol delete ditekan, produk langsung terhapus dari cart dan tampilan akan otomatis diperbarui. Fitur ini membantu user jika salah memilih barang atau ingin membatalkan pembelian suatu produk.


### ✅ 5. Display Total Price

Total harga dihitung secara otomatis berdasarkan jumlah (quantity) dan harga masing-masing produk. Setiap kali user menambah, mengurangi, atau menghapus produk, total harga langsung diperbarui tanpa perlu refresh manual. Hal ini membuat perhitungan menjadi lebih akurat dan meminimalkan kesalahan dalam penghitungan harga.\

---

## Fitur tambahan (Bonus 30 Poin)

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
## Alur Kerja Program

1. Tampilan Awal (Halaman Products)
Saat aplikasi dibuka, user langsung melihat daftar produk yang ditampilkan dalam bentuk grid agar lebih rapi dan mudah dibaca. Di bagian atas terdapat fitur pencarian, filter kategori, dan ikon keranjang untuk memudahkan navigasi.


<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/73a656f5-84a1-4427-8273-faafb5e22db1" />


2. Fitur Search dan Filter Kategori
User dapat mencari produk dengan mengetik nama barang pada kolom search sehingga produk yang tidak sesuai otomatis tersembunyi. Selain itu, user juga bisa memfilter produk berdasarkan kategori agar pencarian lebih cepat dan terarah.

<img width="500" height="700" alt="image" src="https://github.com/user-attachments/assets/09a5db0f-dec0-426b-9d0d-551850b8d04e" />




<img width="452" height="988" alt="image" src="https://github.com/user-attachments/assets/d1f7ac45-6942-4acd-85a8-85e1b1a869cf" />


3. Add to Cart
Ketika tombol Add ditekan, produk akan langsung masuk ke dalam keranjang belanja.


<img width="473" height="1000" alt="image" src="https://github.com/user-attachments/assets/41b38937-1707-401e-b881-d71981ab23f5" />

4. Halaman Shopping Cart
Di halaman ini user dapat melihat semua produk yang sudah dipilih lengkap dengan jumlah dan subtotalnya. User juga bisa menambah, mengurangi, atau menghapus produk sesuai kebutuhan.


<img width="452" height="992" alt="image" src="https://github.com/user-attachments/assets/cabe8fa9-486e-47a9-bf7c-de6b9be17442" />

5. Halaman Checkout
Saat tombol Checkout ditekan, user akan diarahkan ke halaman konfirmasi pesanan yang menampilkan ringkasan belanja. Di halaman ini user juga harus mengisi nama lengkap dan alamat sebagai data pengiriman.

<img width="469" height="1013" alt="image" src="https://github.com/user-attachments/assets/b3867910-6c00-46e6-a916-06b91aa4c2c6" />

6. Konfirmasi Pesanan
Jika semua data sudah diisi dengan benar, user dapat menekan tombol Confirm Order untuk menyelesaikan transaksi. Setelah berhasil, akan muncul pesan konfirmasi dan keranjang belanja akan dikosongkan secara otomatis.

<img width="466" height="999" alt="image" src="https://github.com/user-attachments/assets/688f1996-01cf-4c25-ac6f-f18f8e0ea290" />
