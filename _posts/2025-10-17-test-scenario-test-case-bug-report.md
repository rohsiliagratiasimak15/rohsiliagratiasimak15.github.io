---
title : "Test Scenario, Test Case dan Bug Report"
date : 2025-10-17 
image : /assets/images/kelompok4.png
categories :  [Software Testing & Quality Assurance]
tags : [Software Testing, scenario, bug]
---

# Pengantar

Test Scenario, Test Case, dan Bug Report adalah tiga elemen penting dalam proses pengujian perangkat lunak. Tujuannya untuk memastikan aplikasi berjalan sesuai harapan dan bebas dari kesalahan.

| Elemen | Pengertian | Fungsi | 
|----|------|------|
| Test Scenario  | Gambaran umum tentang apa yang diuji untuk memastikan fungsi aplikasi sesuai kebutuhan. | Memberi panduan umum pengujian. | 
| Test Case  | Langkah detail pengujian yang mencakup input, proses, dan hasil yang diharapkan. | Memberi petunjuk spesifik dalam pengujian. | 
| Bug Report  | Laporan resmi kesalahan atau masalah yang ditemukan saat pengujian. | Dokumentasi masalah dan dasar perbaikan. |

# Test Scenario dan Test Case

## A. Test Scenario

Menjelaskan apa yang diuji dan modul/fungsi yang terlibat. Biasanya berisi:
- ID Scenario
- Deskripsi singkat pengujian
- Modul/Fitur yang diuji

## B. Test Case 

Menjelaskan bagaimana pengujian dilakukan, termasuk langkah dan hasil yang diharapkan. Berisi:

- ID Test Case
- Deskripsi singkat
- Precondition (kondisi awal)
- Test Steps (langkah uji)
- Test Data (input)
- Expected Result (hasil yang diharapkan)
- Actual Result (hasil sebenarnya)
- Status (Lulus/Gagal)

## C. Bug Report 

Bug Report adalah dokumen untuk mencatat masalah yang ditemukan selama pengujian.
Berisi informasi penting seperti:

- Bug ID dan Judul Bug
- Langkah untuk mereproduksi (Steps to Reproduce)
- Hasil Aktual (Actual Result)
- Hasil yang Diharapkan (Expected Result)
- Severity (Tingkat Keparahan)
- Priority (Prioritas Perbaikan)
- Tanggal, Assignee, dan Reporter

## D. Kategori Bug 

#### 1. Berdasarkan Severity (Dampak)

- Low : Tidak berpengaruh besar terhadap sistem
- Minor (Medium) : Tidak memengaruhi fungsi utama tapi mengganggu tampilan
- Major (High) : Fungsi utama tidak berjalan tapi sistem masih bisa digunakan
- Critical : Sistem crash total atau data rusak

#### 2. Berdasarkan Priority (Tingkat Kepentingan)

- P1 (Urgent/Critical) :  Harus segera diperbaiki
- P2 (High) : Penting, memengaruhi banyak pengguna
- P3 (Medium)  : Bisa diperbaiki di rilis berikutnya
- P4 (Low)  : Minor atau kosmetik, tidak mendesak

## E. Cara Menghindari Bug 
1.  Pahami Persyaratan Sistem – pastikan semua anggota tim memahami kebutuhan dengan jelas.
2. Lakukan Unit Testing – deteksi bug sejak tahap awal pengembangan.
3. Code Review – minta rekan pengembang memeriksa kode.
4. Buat Test Plan yang Lengkap – agar pengujian terarah.
5. Gunakan Automation Testing – untuk efisiensi dan deteksi cepat.
6. Tingkatkan Kolaborasi Tim – jaga komunikasi antara developer dan tester.

# Kesimpulan

- Test Scenario menggambarkan apa yang diuji.
- Test Case menjelaskan bagaimana cara menguji.
- Bug Report mendokumentasikan masalah yang ditemukan selama testing.
Ketiganya saling terhubung dan berperan penting untuk menghasilkan software yang stabil, akurat, dan bebas bug.