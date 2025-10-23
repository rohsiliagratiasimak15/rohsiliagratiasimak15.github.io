---
title : "API Testing"
date : 2025-10-17 
image : /assets/images/kelompok6.png
categories :  [Software Testing & Quality Assurance]
tags : [Software Testing, API Testing]
---

# API Testing

API Testing adalah proses pengujian yang dilakukan
pada Application Programming Interface (API) untuk
memastikan bahwa API berfungsi sesuai dengan
spesifikasi, dapat menangani berbagai skenario dengan
benar, serta menghasilkan output yang benar ketika
menerima input tertentu.

## Keunggulan dan Pentingnya API Testing

API Testing memiliki banyak manfaat dalam proses pengembangan perangkat lunak, antara lain:

| Keunggulan | Penjelasan |
|----|----|
| Memastikan fungsionalitas API | Menjamin API memberikan output sesuai spesifikasi dan menangani error dengan benar. |
| Meningkatkan keandalan sistem | Bug dapat dideteksi lebih awal sebelum sampai ke tahap integrasi. |
| Menjamin keamanan API | Menguji apakah API terlindungi dari akses tidak sah dan potensi serangan. |
| Mengukur performa API | Menilai kecepatan dan kestabilan API saat menerima banyak request. |
| Mendukung otomatisasi pengujian | Mempercepat siklus pengembangan dan integrasi berkelanjutan (CI/CD). |
| Mendukung integrasi sistem | API testing memastikan data dan layanan antar sistem berjalan dengan lancar. |

## Tools Populer untuk API Testing

### 1. POSTMAN
Tool paling umum digunakan untuk pengujian API berbasis HTTP.

Fitur Utama:
1. Antarmuka user-friendly
2. Mendukung berbagai metode HTTP (GET, POST, PUT, DELETE)
3. Manajemen koleksi request dan environment
4. Mendukung autentikasi (API key, OAuth, Token)
5. Dapat digunakan untuk testing otomatis, mock server, dan monitoring
6. Menyediakan visualisasi hasil response

### 2. SOAPUI 
Tool pengujian profesional untuk API berbasis SOAP maupun REST.

Fitur Utama: 
1. Mendukung functional testing, security testing, dan load testing
2. Mampu melakukan data-driven testing (menggunakan data dari Excel atau database)
3. Dapat digunakan untuk pengujian enterprise dengan skenario kompleks
4. Kuat untuk pengujian berbasis XML dan layanan SOAP API

## Anatomi Request dan Response API

### Request API
Request adalah permintaan yang dikirimkan dari
klien ke server untuk mengakses atau
memanipulasi data melalui API. Contoh : 
- Method (HTTP Verb): Menentukan aksi yang ingin
dilakukan, contohnya GET, POST, PUT, DELETE.
- URL (Uniform Resource Locator): Alamat dari
resource yang ingin diakses atau dimodifikasi.

### Response API 
Response adalah balasan yang diberikan oleh
server setelah memproses request. Contoh : 
- Status Code: Kode numerik untuk
menandakan hasil eksekusi, misal 200 (OK),
404 (Not Found), 401 (Unauthorized).

# Kesimpulan 
- API Testing memastikan fungsi, performa, dan keamanan layanan antar sistem.
- Tools seperti Postman dan SOAPUI membantu melakukan pengujian otomatis maupun manual.
- Pemahaman tentang request & response sangat penting agar integrasi antar sistem berjalan sukses.
