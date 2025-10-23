---
title : "Pengantar Unit Testing"
date : 2025-10-17 
image : /assets/images/kelompok5.png
categories :  [Software Testing & Quality Assurance]
tags : [Software Testing, Unit Testing]
---

# Unit Testing

Unit Testing adalah jenis pengujian perangkat lunak yang berfokus pada unit terkecil dalam sistem, seperti fungsi (function), metode (method), atau kelas (class).
Dilakukan oleh developer di tahap awal sebelum integration testing, functional testing, atau end-to-end testing.

Tujuan : memastikan setiap bagian kode berjalan dengan benar secara mandiri, tanpa bergantung pada bagian lain.

Analogi : Seperti memeriksa setiap komponen mobil (ban, mesin, lampu) sebelum mobil dirakit — jika semua bagian berfungsi, maka mobil utuh akan berjalan baik.

# Pentingnya Unit Testing

Unit testing memiliki banyak manfaat dalam pengembangan perangkat lunak, di antaranya:

| Manfaat | Penjelasan |
|----|----|
| Mendeteksi bug lebih awal | Kesalahan dapat ditemukan sejak tahap awal pengembangan. |
| Meningkatkan kualitas kode | Membantu menjaga stabilitas dan keandalan kode. |
| Menghemat waktu dan biaya | Mencegah perbaikan besar di tahap akhir proyek. |
| Meningkatkan kepercayaan diri developer | Developer lebih yakin dalam melakukan perubahan kode. |
| Mempermudah refactoring | Perubahan kode tidak akan merusak fungsi lain karena sudah diuji. |
| Memberikan dokumentasi hidup | Test case berfungsi sebagai dokumentasi aktif dari perilaku sistem. |


# Framework Populer untuk Unit Testing

Tiga framework paling sering digunakan di berbagai bahasa pemrograman:
1. JUnit 5 (Java) : digunakan untuk Java, Kotlin, atau Scala. Keunggulan: integrasi penuh dengan ekosistem Java, berbasis anotasi dan ekosistem yang matang dan banyak dokumentasi

2. Jest (JavaScript) : digunakan untuk React, Node.js, TypeScript, atau framework frontend modern.Keunggulan: Zero-configuration (langsung pakai tanpa setup rumit), Fitur snapshot testing dan Ringan dan mudah digunakan

3. Pytest (Python) :  digunakan untuk proyek Python apa pun (web, data science, API).
Keunggulan: Sintaks sederhana, Fixtures kuat untuk setup pengujian dan Laporan error sangat detail.

# Pola Dasar Unit Testing: AAA (Arrange, Act, Assert)

Pendekatan paling umum dalam menulis unit test, dibagi dalam tiga tahap:

| Tahap | Penjelasan | Contoh Singkat |
|----|----|----|
| Arrange | Menyiapkan kondisi awal tes | Buat objek, tetapkan nilai awal |
| Act | Menjalankan fungsi/metode yang diuji | Panggil fungsi `calculateTotal()` |
| Assert | Memverifikasi hasil sesuai ekspektasi | Periksa apakah hasil = nilai yang diharapkan |

Pola ini membuat kode test lebih terstruktur, mudah dibaca, dan konsisten.

# Contoh Implementasi Live Coding 

<img src="/assets/images/coding5_1.png" alt="Live Coding"
     style="display:block; margin-left:auto; margin-right:auto; width:80%; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.2);">

<img src="/assets/images/coding5_2.png" alt="Live Coding"
     style="display:block; margin-left:auto; margin-right:auto; width:80%; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.2);">

# Kesimpulan 

- Unit testing adalah fondasi kualitas software.
- Dilakukan di tahap awal oleh developer untuk memastikan fungsi dasar kode bekerja dengan benar.
- Dengan framework seperti JUnit, Jest, atau Pytest, pengujian menjadi lebih cepat, otomatis, dan akurat.
- Mengikuti pola Arrange – Act – Assert membantu menjaga struktur pengujian tetap rapi dan mudah dipahami.