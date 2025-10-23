---
title : "UI/UX Testing"
date : 2025-10-17 
image : /assets/images/kelompok2.png
categories :  [Software Testing & Quality Assurance]
tags : [Software Testing, UI/UX]
---

## Perbedaan Dasar UI & UX Testing

- **UI (User Interface) Testing** 

Berfokus pada tampilan antarmuka aplikasi, seperti warna, ikon, ukuran tombol, layout, dan konsistensi tampilan di berbagai perangkat.
Contoh: Memastikan tombol Login tampil dengan benar di desktop maupun mobile.

- **UX (User Experience) Testing** 

Berfokus pada pengalaman pengguna saat berinteraksi dengan aplikasi.
Contoh: Menguji apakah pengguna bisa menemukan produk dan menyelesaikan pembelian dengan mudah.

## Fokus UI Testing

### a. Konsistensi Visual

Pastikan elemen visual seperti warna, ikon, font, dan ukuran tombol konsisten di semua halaman.

🧪 Tools: Percy, Applitools, Selenium (visual plugin).

### b. Responsivitas

Desain harus tetap nyaman digunakan di berbagai ukuran layar (HP, tablet, laptop).

🧪 Tools: BrowserStack, LambdaTest, Responsively App.

### c. Kompabilitas

UI harus berjalan baik di berbagai browser dan sistem operasi.

🧪 Tools: BrowserStack, Sauce Labs, LambdaTest.

## Fokus UX Testing

### a. Alur Kerja (Workflow)

UX Testing bersifat iteratif, umumnya melalui tahapan:
1. Perencanaan & penentuan peserta
2. Rekrutmen pengguna
3. Pelaksanaan (observasi/wawancara)
4. Analisis hasil
5. Iterasi desain berdasarkan temuan

Contoh:
Shopify menguji desain profil pengguna melalui card sorting dan tree testing untuk memahami preferensi pengguna.

### b. Kegunaan 
Menilai seberapa mudah pengguna berinteraksi dengan sistem.
Tujuannya agar desain mudah digunakan dan meningkatkan kepuasan pengguna.

Contoh:
Movista menggunakan remote usability testing dengan prototipe melalui Maze, untuk menemukan masalah pada alur pengiriman pesan.

### c. Aksesbilitas 

Menjamin aplikasi dapat digunakan oleh semua orang, termasuk penyandang disabilitas (gangguan penglihatan, pendengaran, motorik). Mengacu pada standar WCAG (Web Content Accessibility Guidelines).

Contoh:
Menguji kontras warna teks terhadap latar belakang agar mudah dibaca pengguna dengan gangguan penglihatan.

## Metode & Tools UI/UX Testing

| Metode | Tujuan | Tools | 
|----|------|------|
| Heatmaps  |Melihat area yang sering diklik pengguna | Hotjar, Crazy Egg, Microsoft Clarity | 
| A/B Testing  | Membandingkan dua versi desain untuk mengetahui mana yang lebih efektif | Google Optimize, Optimizely | 
| Checklist Manual & Prototype Testing  | Mengecek tampilan dan alur interaksi secara langsung | Figma, Zeplin |

### Heuristic Evaluation (Evaluasi Heuristik)

Metode evaluasi berdasarkan 10 prinsip usability dari Jakob Nielsen:
1. Visibilitas status sistem – Sistem memberi umpan balik jelas tentang apa yang sedang terjadi.
2. Kecocokan antara sistem & dunia nyata – Menggunakan bahasa dan ikon yang mudah dipahami pengguna.
3. Kontrol & kebebasan pengguna – Memungkinkan pengguna membatalkan tindakan dengan mudah.
4. Konsistensi & standar – Desain, istilah, dan navigasi harus konsisten.
5. Pencegahan kesalahan – Desain mencegah pengguna melakukan kesalahan sejak awal.
6. Mengenali daripada mengingat – Objek dan tindakan harus terlihat jelas agar pengguna tidak perlu mengingat langkah-langkah.
7. Fleksibilitas & efisiensi penggunaan – Dukungan untuk pengguna pemula maupun ahli (misalnya, pintasan).
8. Desain estetis & minimalis – Tampilan tidak boleh penuh informasi yang tidak relevan.
9. Pesan kesalahan yang jelas – Gunakan bahasa yang mudah dimengerti, sertakan solusi.
10. Bantuan & dokumentasi – Panduan mudah diakses dan relevan dengan kebutuhan pengguna.

## 📘Kesimpulan 

UI/UX Testing adalah langkah penting untuk memastikan tampilan dan pengalaman pengguna berjalan optimal.
- UI Testing menekankan konsistensi visual, responsivitas, dan kompatibilitas tampilan.
- UX Testing fokus pada kegunaan, aksesibilitas, dan pengalaman pengguna secara menyeluruh.
- Evaluasi heuristik dan penggunaan tools testing modern membantu meningkatkan kualitas produk digital serta kepuasan pengguna.