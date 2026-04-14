# 🛒 ReveList - Point of Sale (POS) System

[![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)](https://vuejs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

**ReveList** adalah prototipe aplikasi *Point of Sale* (POS) berbasis web yang dirancang untuk menyederhanakan operasional ritel, memanajemen inventaris produk, dan menyediakan analitik bisnis secara *real-time*. 

Aplikasi ini dibangun menggunakan pendekatan *Single Page Application* (SPA) untuk memastikan navigasi kasir yang cepat dan mulus tanpa perlu *reload* halaman, menjadikannya efisien untuk transaksi harian.

🔗 **[Lihat Live Demo di Sini](Masukkan Link Vercel Anda di sini, contoh: https://revelist-pos.vercel.app)**

## ✨ Fitur Utama

- 📊 **Real-time Business Dashboard:** Memantau metrik performa bisnis utama (Revenue, Total Cost, Gross Profit) secara dinamis. Angka hanya akan terakumulasi dari invoice dengan status *Paid*.
- 📦 **Smart Inventory Management:** - CRUD (Create, Read, Update, Delete) produk dengan mudah.
  - Peringatan stok kritis dan pemotongan stok otomatis saat transaksi.
  - **Auto-Image Compress:** Gambar produk yang diunggah akan otomatis dikompresi ukurannya langsung di sisi *client* untuk menghemat memori.
- 🛒 **Seamless POS Cart:** Proses *checkout* yang intuitif dengan fitur penyesuaian kuantitas dan manajemen status pembayaran (Paid/Pending).
- 🧾 **Invoice Management & Smart Delete:** Riwayat transaksi tercatat rapi dengan opsi ubah status. Jika invoice dihapus, sistem akan otomatis mengembalikan stok produk (*restocking*) ke dalam katalog.
- 🖨️ **Client-Ready Print Invoices:** Menghasilkan format cetak struk yang rapi. Secara otomatis menyembunyikan Harga Modal (HPP) dan Keuntungan pada versi cetak agar aman diberikan kepada pelanggan.

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun murni di sisi *Frontend* (Client-side) tanpa memerlukan setup server/backend tambahan untuk kemudahan demonstrasi:
- **HTML5 & Vue.js (v3)**: Mengatur reaktivitas data, *state management*, dan logika bisnis.
- **Tail
