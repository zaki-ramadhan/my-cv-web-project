# Website Portfolio Pribadi

Ini adalah website portfolio pribadi untuk Zaki Ramadhan, seorang Web Developer Intern. Website ini dibuat dengan fokus pada desain yang bersih, performa, dan pengalaman pengguna yang profesional.

## Fitur Utama

*   **Desain Responsif**: Tampilan website dapat beradaptasi di semua ukuran layar, baik di desktop maupun mobile.
*   **Navigasi Lancar**: Header yang tetap di atas saat di-scroll dengan link yang mengarah ke setiap bagian halaman.
*   **Struktur File Modular**: Kode HTML dipecah menjadi beberapa file terpisah agar lebih rapi dan mudah dikelola.
*   **Tampilan Interaktif**: Dilengkapi animasi sederhana dan efek hover untuk membuat website lebih menarik.
*   **Formulir Kontak**: Formulir kontak dengan validasi di sisi klien untuk memudahkan pengunjung mengirim pesan.

## Teknologi yang Digunakan

*   **HTML5**: Sebagai struktur utama website.
*   **Tailwind CSS**: Untuk semua styling dan layout, dengan pendekatan utility-first yang responsif.
*   **JavaScript**: Untuk fitur interaktif seperti menu mobile dan validasi formulir.
*   **Google Fonts**: Untuk tipografi yang modern dan mudah dibaca.

## Cara Menjalankan

Tidak ada instalasi khusus yang diperlukan. Cukup buka file `index.html` di browser Anda untuk melihat website.

Untuk pengembangan, disarankan menggunakan server lokal yang mendukung *Server-Side Includes* (SSI) agar file-file HTML parsial (seperti `_head.html`, `_header.html`, dll.) dapat digabungkan dengan benar ke `index.html`.

## Struktur File

Proyek ini disusun dengan memisahkan setiap komponen ke dalam file HTML parsial agar kode lebih bersih dan mudah dikelola.

```
.
├── index.html                  # File utama website
├── _head.html                  # Berisi semua konten <head> (meta, CSS, font)
├── _header.html                # Komponen header dan navigasi
├── _hero.html                  # Komponen section hero
├── _about.html                 # Komponen section tentang saya
├── _projects.html              # Komponen galeri proyek
├── _contact.html               # Komponen formulir kontak
├── _footer.html                # Komponen footer
├── _scripts.html               # Berisi semua kode JavaScript
└── assets/                     # Direktori untuk menyimpan gambar dan aset lainnya
```

Struktur ini memisahkan setiap bagian, sehingga memudahkan saat ingin memperbarui salah satu section tanpa mengganggu bagian lainnya.