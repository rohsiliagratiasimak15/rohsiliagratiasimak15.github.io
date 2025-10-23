---
title : "Pengantar Selenium Webdriver"
date : 2025-10-17 
image : /assets/images/kelompok7.png
categories :  [Software Testing & Quality Assurance]
tags : [Software Testing, Selenium]
---

# Apa itu Selenium? 
Selenium adalah framework open-source untuk
automasi browser. Digunakan untuk menguji aplikasi web dengan berbagai bahasa pemrograman. Mendukung banyak browser: Chrome, Firefox,
Edge, Safari.

# Apa itu Selenium WebDriver?
WebDriver adalah komponen inti Selenium. Berfungsi sebagai penghubung antara kode
kita dengan browser. Mengontrol browser (klik, input teks, navigasi,
validasi).

# Kenapa harus selenium?
1. Open-source dan gratis.
2. Mendukung banyak bahasa (Python, Java, C#, JS).
3. Multi-platform (Windows, macOS, Linux).
4. Bisa integrasi dengan framework testing seperti Pytest, JUnit, TestNG.
5. Komunitas besar dan dokumentasi lengkap.

## Instalasi Selenium dengan Python
Langkah umum untuk menggunakan Selenium di Python:
1. Instal Selenium :  `pip install selenium`
2. Instal WebDriver dari https://chromedriver.chromium.org dan pastikan versinya sesuai dengan browser Chrome yang kamu pakai.
3. Buat file Python, misalnya test_selenium.py.

## Membuka Browser dengan Selenium 
Contoh kode dasar untuk membuka browser dan membuka website:

`from selenium import webdriver`

`driver = webdriver.Chrome()`
`driver.get("https://www.saucedemo.com")`

## Interaksi dengan Element HTML
Kamu bisa mencari dan berinteraksi dengan elemen web seperti tombol, form input, atau teks menggunakan berbagai metode:

contoh : 

`from selenium.webdriver.common.by import By`

`driver.find_element(By.ID, "user-name").send_keys("standard_user")`
`driver.find_element(By.ID, "password").send_keys("secret_sauce")`
`driver.find_element(By.ID, "login-button").click()`

- By.ID → berdasarkan id
- By.NAME → berdasarkan name
- By.CLASS_NAME → berdasarkan class
- By.XPATH → berdasarkan struktur HTML

# Kesimpulan
- Selenium WebDriver adalah alat utama untuk pengujian otomatis aplikasi web.
- Dapat dijalankan dengan berbagai bahasa dan browser.
- Mendukung integrasi dengan framework testing populer.
- Penggunaan Selenium dapat menghemat waktu pengujian dan meningkatkan akurasi hasil tes.