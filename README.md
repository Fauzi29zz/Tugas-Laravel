Berikut adalah versi `README.md` yang **lebih elegan dan rapi** dengan **penekanan visual menggunakan emoji, heading yang bersih, dan pemisahan konten per langkah** — **tanpa mengubah gambar** yang kamu gunakan:

```markdown
# 🚀 Panduan Instalasi Laravel di Laragon

Panduan langkah demi langkah untuk menginstall Laravel menggunakan **Laragon** sebagai web server lokal.

---

## ✅ Prasyarat

Sebelum memulai, pastikan hal-hal berikut sudah tersedia di komputer kamu:

- 🧰 Web Server seperti **[Laragon](https://laragon.org/)** atau XAMPP
- 📦 Composer - PHP Dependency Manager (**[Download Composer](https://getcomposer.org/download/)**)

---

## 🛠️ Langkah-Langkah Instalasi Laravel

### 📌 1. Pastikan Web Server Terinstal

Sebelum menginstall Laravel, pastikan kamu sudah memiliki **Laragon** atau **XAMPP**.

---

### 📌 2. Install Composer

Unduh dan install Composer melalui file `composer-setup.exe`.

> Composer akan memungkinkan kamu menjalankan perintah PHP melalui terminal.

---

### 📌 3. Buka Terminal dari Laragon

Buka aplikasi **Laragon**, lalu pilih menu **Terminal / Shell**.

![image](https://github.com/user-attachments/assets/ccafb4e9-23c2-4ef8-a04c-62b9c5bd5307)

---

### 📌 4. Cek Instalasi Composer

Untuk memastikan Composer berhasil diinstal, ketik perintah berikut di terminal:

```bash
composer --version
```

![image](https://github.com/user-attachments/assets/8d46d4df-bc55-4f0c-ad91-fcbcac437271)

Jika versi Composer muncul seperti gambar di atas, maka Composer siap digunakan.

---

### 📌 5. Arahkan ke Folder Proyek Laravel

Pindah ke folder `www` milik Laragon dengan perintah:

```bash
cd C:\laragon\www
```

![image](https://github.com/user-attachments/assets/b6bb5135-1ede-45af-8d4f-03f25b1ba644)

---

### 📌 6. Install Laravel

Untuk mengunduh Laravel dan membuat project baru bernama `pelatihan`, jalankan perintah:

```bash
composer create-project --prefer-dist laravel/laravel pelatihan
```

![image](https://github.com/user-attachments/assets/ad78fc15-d900-4c67-9c68-14a00f3f5775)

Tunggu proses instalasi hingga selesai.

---

### 📌 7. Jalankan Project Laravel

Setelah instalasi selesai, masuk ke folder `pelatihan` dan jalankan server Laravel:

```bash
cd pelatihan
php artisan serve
```

![image](https://github.com/user-attachments/assets/1b3ae780-3680-4bb3-885d-d0983709a425)

---

### 📌 8. Laravel Siap Digunakan 🎉

Jika berhasil, kamu akan melihat tampilan default Laravel di browser:

```
http://127.0.0.1:8000
```

![image](https://github.com/user-attachments/assets/11c58b84-809a-44dd-afbb-bcb1ce5b8a39)

---

## 🎯 Penutup

Laravel sekarang sudah berhasil dijalankan dan siap digunakan untuk membangun aplikasi sesuai kebutuhan proyekmu.

Happy coding! 💻🚀
