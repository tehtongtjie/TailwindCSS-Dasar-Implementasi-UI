# TailwindCSS Dasar - Implementasi UI
### Tahap Tes Kemampuan — Web Developer

Repositori ini berisi implementasi kode *Front-End* untuk pembuatan *Landing Page* platform edutainment anak bernama **Funtasya World**. Proyek ini dikembangkan menggunakan **Tailwind CSS** murni untuk memenuhi standar penilaian tahap tes kemampuan posisi Web Developer.

---

## 🚀 Fitur Utama & Struktur Halaman

Halaman ini dirancang secara modular dan responsif (*Mobile-First Approach*) dengan mencakup beberapa bagian (*section*) esensial berikut:

*   **Header & Navigation Bar:** Dilengkapi dengan sistem *topbar* info kontak, menu navigasi drop-down interaktif, pilihan bahasa (EN/ID), serta tombol unduh responsif.
*   **Hero Section:** Banner utama dengan latar belakang *radial pattern* yang ceria dan tata letak grid asimetris untuk teks promosi dan mockup perangkat seluler.
*   **Explore Educational Categories:** Grid 3 kolom horizontal yang menampilkan kategori belajar anak. Desain dibuat interaktif dengan mikro-animasi *hover* dinamis, pembesaran aset visual, serta tombol unduh (*download badge*) tematik.
*   **Top Educational Games:** Daftar game terpopuler menggunakan kartu visual (*card*) dengan rasio aspek gambar `16:9` konsisten, label rating bintang, informasi jumlah unduhan, dan tombol aksi (*CTA*) bervariasi warna.
*   **Newsletter Subscription:** Formulir berlangganan email dengan desain ringkas (*compact max-w-xl*) berlatar gradasi warna ceria (*pink-to-orange*) untuk menangkap data pengguna secara interaktif.
*   **FAQ Accordion:** Bagian tanya-jawab menggunakan interaksi murni komponen HTML5 (`<details>` & `<summary>`) tanpa beban skrip eksternal, memastikan performa halaman tetap instan dan ringan.
*   **Footer:** Navigasi bawah multi-kolom yang mengelompokkan profil ringkas, tautan legalitas perusahaan, peta kategori game, serta informasi detail kontak perusahaan.

---

## 🛠️ Teknologi & Fitur Kode yang Diimplementasikan

*   **HTML5 & Tailwind CSS V3:** Menggunakan integrasi Tailwind CDN untuk penyusunan utilitas gaya visual secara cepat dan efisien.
*   **Google Fonts Integration:** Menggunakan tipografi *Inter* untuk menjaga keterbacaan teks (*readability*) yang optimal pada berbagai ukuran layar.
*   **Micro-Interactions (CSS-Only):** Mengimplementasikan transisi animasi halus seperti efek naik-turun tombol (`active:scale-95`), efek elevasi bayangan (*hover shadow*), dan rotasi ikon panah accordion saat dibuka.
*   **Modularitas Folder:** Manajemen file diatur secara bersih untuk memisahkan logika aset gambar (`assets/img/`), skrip interaksi, dan komponen halaman demi kemudahan skalabilitas kode ke depan.

---

## 📁 Screenshoot Pengerjaan
(src/assets/img/ss/ss1.png)


## 📁 Struktur Folder Proyek

```text
.
├── index.html                  # Halaman utama (Landing Page)
├── README.md                   # Dokumentasi proyek
└── assets/                     # Direktori aset statis halaman
    └── img/                    # Penyimpanan gambar terstruktur
        ├── Navbar/             # Aset logo dan navigasi
        ├── Hero/               # Mockup perangkat utama
        ├── Kategori/           # Ikon kategori edukasi (foto1, foto2, foto3)
        └── Games/              # Gambar produk game (foto1, foto2, foto3)


