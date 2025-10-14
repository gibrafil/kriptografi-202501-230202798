# Laporan Praktikum Kriptografi
Minggu ke-: 2
Topik: Cryptosystem 
Nama: Ahmad Galif Ganendra
NIM: 2312020798
Kelas: 5IKRA  

---

## 1. Tujuan
(Tuliskan tujuan pembelajaran praktikum sesuai modul.)

---

## 2. Dasar Teori
Kriptosistem merupakan suatu sistem keamanan informasi yang dirancang untuk melindungi pesan atau data agar tidak dapat dipahami oleh pihak yang tidak berhak. Secara umum, kriptosistem mencakup empat komponen utama yaitu pesan asli (plaintext), pesan tersandi (ciphertext), algoritma kriptografi, dan kunci (key). Algoritma kriptografi berfungsi sebagai prosedur matematis untuk melakukan proses enkripsi dan dekripsi. Enkripsi mengubah plaintext menjadi ciphertext agar pesan tidak terbaca selama proses transmisi, sedangkan dekripsi mengembalikan ciphertext ke bentuk semula menggunakan kunci tertentu.

Dalam implementasinya, kriptosistem dibagi menjadi dua kategori utama berdasarkan cara penggunaan kuncinya, yaitu kriptosistem kunci simetris (symmetric key cryptosystem) dan kriptosistem kunci asimetris (asymmetric key cryptosystem). Pada kriptosistem simetris, kunci yang digunakan untuk enkripsi dan dekripsi adalah sama. Keamanan sistem ini sangat bergantung pada kerahasiaan kunci yang digunakan oleh kedua belah pihak. Contoh algoritma simetris antara lain DES (Data Encryption Standard), AES (Advanced Encryption Standard), dan RC4. Sistem ini efisien dari segi waktu dan sumber daya komputasi, namun memiliki kelemahan pada proses distribusi kunci yang berisiko bocor.

Sementara itu, kriptosistem asimetris menggunakan dua kunci yang berbeda namun saling berhubungan secara matematis, yaitu public key dan private key. Public key dapat disebarkan secara bebas untuk mengenkripsi data, sedangkan private key harus dijaga kerahasiaannya dan digunakan untuk mendekripsi pesan. Contoh algoritma yang menerapkan konsep ini adalah RSA (Rivest–Shamir–Adleman) dan ElGamal. Kriptosistem asimetris memiliki tingkat keamanan lebih tinggi dalam distribusi kunci dan cocok digunakan untuk autentikasi digital, tanda tangan elektronik, serta pertukaran kunci pada sistem hybrid.

Dalam praktik modern, kedua jenis kriptosistem ini sering digunakan secara bersamaan untuk membentuk sistem kriptografi hybrid. Kriptografi simetris digunakan untuk proses enkripsi data dalam jumlah besar karena kecepatannya, sedangkan kriptografi asimetris digunakan untuk mengamankan pertukaran kunci simetris tersebut. Dengan demikian, kombinasi keduanya mampu memberikan keseimbangan antara efisiensi dan keamanan dalam sistem komunikasi digital.

## 3. Alat dan Bahan
(- Python 3.x  
- Visual Studio Code / editor lain  
- Git dan akun GitHub  
- Library tambahan (misalnya pycryptodome, jika diperlukan)  )

---

## 4. Langkah Percobaan
(Tuliskan langkah yang dilakukan sesuai instruksi.  
Contoh format:
1. Membuat file `caesar_cipher.py` di folder `praktikum/week2-cryptosystem/src/`.
2. Menyalin kode program dari panduan praktikum.
3. Menjalankan program dengan perintah `python caesar_cipher.py`.)

---

## 5. Source Code
(Salin kode program utama yang dibuat atau dimodifikasi.  
Gunakan blok kode:

```python
# contoh potongan kode
def encrypt(text, key):
    return ...
```
)

---

## 6. Hasil dan Pembahasan
(- Lampirkan screenshot hasil eksekusi program (taruh di folder `screenshots/`).  
- Berikan tabel atau ringkasan hasil uji jika diperlukan.  
- Jelaskan apakah hasil sesuai ekspektasi.  
- Bahas error (jika ada) dan solusinya. 

Hasil eksekusi program Caesar Cipher:

![Hasil Eksekusi](screenshots/output.png)
![Hasil Input](screenshots/input.png)
![Hasil Output](screenshots/output.png)
)

---

## 7. Jawaban Pertanyaan
(Jawab pertanyaan diskusi yang diberikan pada modul.  
- Pertanyaan 1: …  
- Pertanyaan 2: …  
)
---

## 8. Kesimpulan
(Tuliskan kesimpulan singkat (2–3 kalimat) berdasarkan percobaan.  )

---

## 9. Daftar Pustaka
(Cantumkan referensi yang digunakan.  
Contoh:  
- Katz, J., & Lindell, Y. *Introduction to Modern Cryptography*.  
- Stallings, W. *Cryptography and Network Security*.  )

---

## 10. Commit Log
(Tuliskan bukti commit Git yang relevan.  
Contoh:
```
commit abc12345
Author: Nama Mahasiswa <email>
Date:   2025-09-20

    week2-cryptosystem: implementasi Caesar Cipher dan laporan )
```
