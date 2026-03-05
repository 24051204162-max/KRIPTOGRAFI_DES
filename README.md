# 🔐 Implementasi Manual Data Encryption Standard (DES) Python

Program ini adalah implementasi murni algoritme kriptografi **Data Encryption Standard (DES)** menggunakan bahasa Python. Program ini dibuat dari awal (manual) tanpa menggunakan *library* kriptografi eksternal, sehingga sangat cocok untuk keperluan pembelajaran dan pemahaman cara kerja *Feistel Network* serta *Key Schedule* pada DES.

## ✨ Fitur Utama
- **Enkripsi & Dekripsi:** Mengubah teks biasa (Plaintext) menjadi teks sandi (Ciphertext) dan sebaliknya.
- **Tanpa Library Eksternal:** Murni menggunakan operasi logika matematika, manipulasi string, dan *array* (List) bawaan Python.
- **Interaktif (CLI):** Dilengkapi dengan antarmuka terminal/Command Line yang interaktif dan mudah digunakan.
- **Otomatisasi Padding:** Mampu memproses teks dengan panjang bebas (tidak harus kelipatan 8) menggunakan teknik PKCS5/PKCS7 Padding.
- **Output Bersih:** Hasil enkripsi (*Ciphertext*) dikonversi ke dalam format Heksadesimal agar rapi dan mudah di-copy/paste.

## 🚀 Cara Menjalankan Program

### Persyaratan
Pastikan Anda sudah menginstal **Python 3.x** di komputer Anda. Anda bisa mengeceknya dengan mengetikkan perintah berikut di terminal/Command Prompt:
```bash
python --version
