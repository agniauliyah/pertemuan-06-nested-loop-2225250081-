# Algoritma dan Pemrograman – Pertemuan 06

## Nested Loop, Pola, Akumulasi, dan Pencacahan

**Nama:** Agnia Ul Auliyah
**NIM:** 2225250081
**Kelas:** 3E

### Tujuan

Mempelajari penggunaan nested loop dalam Python untuk membuat pola, melakukan akumulasi nilai, dan melakukan pencacahan berdasarkan kondisi tertentu.

### Cara Menjalankan

1. Buka folder project di Visual Studio Code.
2. Buka file Python yang ingin dijalankan.
3. Jalankan file menggunakan Python.
4. Masukkan nilai `n` sesuai dengan pengujian yang dilakukan.

### Algoritma Tugas 3

1. Memasukkan nilai `n`.
2. Memastikan `n` bernilai positif menggunakan `while`.
3. Menggunakan nested loop untuk membuat tabel perkalian dari 1 sampai `n`.
4. Menghitung jumlah setiap baris.
5. Menghitung total seluruh hasil perkalian.
6. Menghitung banyak hasil perkalian yang bernilai genap.
7. Menampilkan tabel dan hasil statistik.

### Hasil Pengujian

| n | Total Seluruh Hasil | Banyak Hasil Genap |
| - | ------------------: | -----------------: |
| 1 |                   1 |                  0 |
| 2 |                   9 |                  3 |
| 3 |                  36 |                  5 |

Semua hasil pengujian sesuai dengan hasil yang diharapkan.

### Analisis Efisiensi

Program menggunakan nested loop sebanyak `n × n`, sehingga jumlah operasi utama bertambah sebanding dengan `n²`. Kompleksitas waktu program adalah **O(n²)**.

### Refleksi

Pada pertemuan ini saya mempelajari penggunaan nested loop untuk melakukan perulangan di dalam perulangan. Saya juga memahami cara menggunakan akumulasi untuk menghitung jumlah dan pencacahan untuk menghitung banyaknya hasil yang memenuhi kondisi tertentu.