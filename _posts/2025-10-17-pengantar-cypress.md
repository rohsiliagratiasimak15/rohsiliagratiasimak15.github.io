---
title : "Pengantar Cypress"
date : 2025-10-17 
image : /assets/images/kelompok8.png
categories :  [Software Testing & Quality Assurance]
tags : [Software Testing, Cypress]
---

# Cypress 
Cypress adalah framework end-to-end testing untuk
aplikasi web modern (React, Vue, Angular, dll).

Posisi Cypress dalam testing:
- Unit Testing
- Integration Testing
- End-to-End Testing

Cypress ada di level End-to-End, tapi juga bisa dipakai
untuk Integration dan Component Testing.

## Setup Cypress 
Untuk mulai menggunakan Cypress, dibutuhkan Node.js sebagai prasyarat utama.

1. Instalasi Cypress
- `npm init -y`
- `npm install cypress --save-dev`

2. Menjalakan Cypress
- Open Cypress : `npx cypress open`
- Jalankan melalui browser : `npx cypress run` 

## Perintah Dasar Cypress

Cypress menyediakan perintah sederhana dan intuitif untuk mengontrol browser layaknya pengguna.

| Perintah | Fungsi | Contoh |
|----|----|----|
| cy.visit('URL') | Membuka halaman web | `cy.visit('https://saucedemo.com')` |
| cy.get('selector') | Mengambil elemen berdasarkan selector | `cy.get('#username')` |
| cy.type('text') | Mengetik teks ke input field | `cy.get('#password').type('secret_sauce')` |
| cy.click() | Mengklik tombol atau link | `cy.get('#login-button').click()` |
| cy.contains('text') | Mencari elemen berdasarkan teks | `cy.contains('Logout').click()` |
| cy.url() | Mengecek URL aktif saat ini | `cy.url().should('include', '/inventory')` |

## Keunggulan Cypress
Cypress berbeda dari framework testing lain seperti Selenium atau Playwright karena:

| Keunggulan | Penjelasan |
|----|----|
| Arsitektur modern | Dibangun menggunakan Node.js dan berjalan langsung di browser. |
| Test Runner interaktif | Memungkinkan melihat eksekusi tes secara real-time. |
| Time Travel | Dapat memutar ulang langkah-langkah pengujian untuk debugging. |
| Automatic Waits | Cypress otomatis menunggu elemen muncul sebelum melanjutkan langkah berikutnya. |
| Integrasi mudah | Bisa dihubungkan dengan CI/CD pipeline seperti Jenkins atau GitHub Actions. |

# Kesimpulan
- Cypress adalah framework modern untuk automated end-to-end testing pada aplikasi web.
- Fitur seperti Test Runner interaktif, Time Travel, dan Automatic Waits membuat proses pengujian cepat dan efisien.
- Struktur tes yang jelas dan perintah intuitif memudahkan developer menulis dan memahami skrip uji.
- Berdasarkan live demo pengujian login di saucedemo.com, Cypress terbukti efektif dalam menangani berbagai skenario pengujian UI.