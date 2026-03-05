# 🔐 Implementasi Manual Data Encryption Standard (DES) Python

Program ini adalah implementasi murni algoritme kriptografi **Data Encryption Standard (DES)** menggunakan bahasa Python. Program ini dibangun dari awal (manual) tanpa menggunakan *library* kriptografi eksternal, sehingga sangat cocok untuk tujuan edukasi dan memahami logika *Feistel Network* di balik layar.

---

## 📥 Cara Mengakses dan Mengunduh Program

### Menggunakan Git (Bagi yang sudah menginstal Git)
Buka Terminal atau Command Prompt di komputer Anda, lalu ketikkan perintah berikut:
```bash
git clone [https://github.com/USERNAME_ANDA/NAMA_REPOSITORI_ANDA.git](https://github.com/USERNAME_ANDA/NAMA_REPOSITORI_ANDA.git)
```

## 🚀 Cara Menjalankan Program

### Persyaratan
Pastikan Anda sudah menginstal **Python 3.x** di komputer Anda. Anda bisa mengeceknya dengan mengetikkan perintah berikut di terminal/Command Prompt:
```bash
python --version
```

## Langkah 1: Membuka Program

Jalankan program dengan perintah:

```bash
python nama_file_anda.py
```

## Langkah 2: Melakukan Enkripsi (Plaintext ke Ciphertext)
Saat program berjalan, Anda akan melihat menu utama. Mari kita enkripsi sebuah pesan rahasia.

1. Ketik 1 pada Pilih menu (1/2/3): lalu tekan Enter.

2. Program akan meminta Kunci Rahasia. Kunci ini wajib tepat 8 karakter.

   Contoh input: KUNCI123

3. Program akan meminta Teks (pesan asli/Plaintext) yang ingin Anda rahasiakan.

   Contoh input: Halo, ini pesan sangat rahasia!

4. Program akan memproses data dan mengeluarkan hasil Ciphertext dalam format karakter Heksadesimal.

   Contoh output: 4a8f9c2e... (kombinasi angka dan huruf).

5. PENTING: Blok dan Copy (salin) hasil teks sandi (Ciphertext) tersebut untuk digunakan pada langkah selanjutnya.

## Langkah 3: Melakukan Dekripsi (Ciphertext kembali ke Plaintext)
Sekarang, mari kita buktikan bahwa algoritme DES ini bekerja dengan cara mengembalikan teks sandi tadi menjadi pesan aslinya. Program akan kembali menampilkan Menu Utama.

1. Ketik 2 pada Pilih menu (1/2/3): lalu tekan Enter.

2. Program akan kembali meminta Kunci Rahasia. Anda wajib memasukkan kunci yang sama persis dengan yang digunakan saat enkripsi tadi.
    ```
   Contoh input: KUNCI123
    ```
3. Program akan meminta Teks Sandi (Chiper). Paste (tempelkan) teks heksadesimal yang sudah Anda copy pada Langkah 2 tadi.
```
Contoh input: 4a8f9c2e...
```
4. Tekan Enter, dan program akan membalikkan proses Feistel Network secara otomatis.

5. Selesai! Anda akan melihat Plaintext Anda kembali secara utuh.
