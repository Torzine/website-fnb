# ☕ MAHIS SPACE — Hidden Coffee Shop Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Design-success?style=for-the-badge&logo=responsive-design&logoColor=white)]()

Sebuah halaman website profil bisnis (UMKM) kuliner modern untuk **MAHIS SPACE**, sebuah *hidden gem coffee shop* yang berlokasi di Kalijambe, Sragen. Website ini dibangun sepenuhnya responsif menggunakan HTML5 murni, CSS3 modern dengan variabel kustom, tata letak Flexbox, serta Media Query tanpa menggunakan framework CSS eksternal (seperti Bootstrap/Tailwind).

Project ini diajukan untuk memenuhi nilai *Mini Project* pada mata kuliah **Pemrograman Web I** di **Universitas Surakarta**.

---

## ✨ Fitur Utama Website

Website ini dilengkapi dengan arsitektur antarmuka modern yang interaktif bagi calon pelanggan:
* **🛡️ Sticky Transparent Navigation:** Navbar elegan dengan efek transisi blur (`backdrop-filter`) yang otomatis berubah warna latar belakang secara dinamis saat pengguna melakukan *scroll* ke bawah.
* **📱 Responsive Hamburger Menu:** Menu navigasi adaptif khusus untuk tampilan mobile layar sentuh.
* **✨ Scroll Reveal Animation:** Animasi pemuatan konten yang halus dan interaktif menggunakan *Intersection Observer API* saat halaman digeser ke bawah.
* **🍱 Dynamic Menu Filter (Tab System):** Sistem filter menu makanan dan minuman berbasis JavaScript tanpa *reload* halaman, memudahkan navigasi katalog produk (Coffee, Non-Coffee, Food, Snacks).
* **🗺️ Integrated Business Call-to-Action:** Tombol interaktif yang terhubung langsung ke Google Maps lokasi kedai, Instagram, dan TikTok bisnis.

---

## 🎨 Palet Warna & Desain (Ocean Aesthetic)

Website ini menerapkan sistem pewarnaan kustom (*CSS Variables*) dengan tema samudera yang menenangkan, kontras, dan profesional:

| Variabel CSS | Kode Hex | Representasi Visual |
| :--- | :--- | :--- |
| `--ocean` | `#0a4f7a` | Warna identitas utama (Deep Ocean) |
| `--ocean-mid` | `#1a7ab5` | Aksentuasi tombol aktif & interaksi hover |
| `--ocean-light`| `#5fb3e4` | Elemen dekoratif dan teks sekunder |
| `--ocean-pale` | `#e8f4fd` | Latar belakang komponen kartu (Card) |
| `--white` | `#ffffff` | Kebersihan tata letak dasar |
| `--ink` | `#0d1b2a` | Keterbacaan teks utama (High Contrast) |

### 🖋️ Tipografi
* **Playfair Display** (Serif) — Digunakan khusus pada elemen *Display Headings* (h1, h2) untuk memberikan kesan premium, klasik, dan estetik ala *coffee shop*.
* **DM Sans** (Sans-serif) — Digunakan pada elemen navigasi, deskripsi, teks menu, dan footer demi menjaga keterbacaan (*readability*) teks yang maksimal di semua ukuran layar.

---

## 📱 Responsivitas (Media Queries)

Arsitektur tata letak didesain adaptif menggunakan *breakpoints* CSS Media Query yang presisi:

1. **Desktop View (`> 968px`):** Tampilan penuh dengan struktur grid multi-kolom horizontal, banner hero yang megah, navigasi berjejer rapi, dan kartu menu tersusun simetris.
2. **Tablet View (`577px - 968px`):** Penyesuaian ukuran teks, kartu katalog produk mengecil secara proporsional dan bertransisi menjadi susunan 2 kolom (*fluid layout*).
3. **Mobile View (`<= 576px`):** Layout runtuh secara vertikal secara elegan. Menu navigasi desktop disembunyikan dan digantikan oleh *hamburger menu toggle*, teks rata tengah, serta ukuran gambar teroptimalisasi penuh untuk layar ponsel.

---

## 📁 Struktur File Project

Sesuai dengan standarisasi tugas, arsitektur file diatur sebagai berikut:
```text
mahis-space-project/
├── gambar/              # Folder penyimpanan aset foto menu dan banner
├── index.html           # Struktur HTML, inline CSS, dan JS interaktif
├── style.css            # (Opsional) Jika CSS dipisah di masa mendatang
└── README.md            # Dokumentasi project GitHub (File ini)# website-fnb
