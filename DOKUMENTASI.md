# Dokumentasi Proyek: Deops Dev Portfolio

Halaman ini adalah situs portfolio pribadi untuk **Deops Dev** (Anjab), yang menampilkan informasi tentang keahlian dan proyek-proyek yang telah dikerjakan.

## 🛠️ Arsitektur Proyek

Situs ini dibangun dengan pendekatan minimalis menggunakan teknologi web murni (Vanilla HTML & CSS) dengan sedikit bantuan JavaScript untuk responsivitas skala.

### 1. Struktur File
- `index.html`: Struktur utama halaman, navigasi, dan konten portfolio.
- `styles.css`: Gaya visual, tata letak grid untuk proyek, dan efek hover.
- `logo.svg`: Logo brand Deops Dev.

## ✨ Fitur Utama

### 1. Skala Responsif (Automatic Scaling)
Situs ini menggunakan teknik unik di mana konten utama memiliki lebar tetap `800px` dan diskalakan secara dinamis menggunakan properti CSS `transform: scale()` melalui JavaScript. Ini memastikan tampilan tetap konsisten di berbagai ukuran layar desktop. Di layar mobile (<= 600px), sistem skala dimatikan dan beralih ke tata letak tumpuk (stack) standar.

### 2. Preview Proyek Interaktif
Menggunakan `iframe` untuk menampilkan cuplikan hidup dari proyek-proyek (seperti Komodoc AI). Iframe ini dikonfigurasi untuk menampilkan versi situs yang diperkecil (scaled down) sehingga memberikan gambaran nyata tentang tampilan proyek tersebut tanpa harus membukanya terlebih dahulu.

### 3. Navigasi Halus
Implementasi `scroll-behavior: smooth` pada CSS memungkinkan transisi antar bagian halaman (Tentang, Proyek, Kontak) menjadi lebih nyaman bagi pengguna.

## 🚀 Pengembangan

### Menambah Proyek Baru
Untuk menambah proyek baru ke dalam daftar:
1. Tambahkan blok `<div class="project-item">` di dalam `.project-grid`.
2. Masukkan URL proyek ke dalam atribut `href` pada link dan `src` pada `iframe`.

### Kustomisasi Gaya
Warna utama dan gradien dapat diubah pada file `styles.css` di bagian `.header` dan `.nav a`.

---
**Pemilik:** [Anjab / Deops Dev](mailto:deops.dev@gmail.com)
**URL:** [https://deopsdev.github.io](https://deopsdev.github.io)
