# Skripsi Matching Berbobot

Repository ini berisi kode program yang digunakan dalam penelitian mengenai matching berbobot pada graf bipartit komplit.

## Algoritma yang Digunakan

Penelitian ini mengimplementasikan dan membandingkan empat algoritma:

1. Greedy Standar
2. Regret
3. Regret Terpusat (RT)
4. Hungarian sebagai solusi optimal acuan.

## Struktur Program

Kode program disusun dalam 13 bagian (cell) sebagai berikut:

| Cell | Keterangan |
|---|---|
| 1 | Pengaturan |
| 2 | Kondisi eksperimen dan seed |
| 3 | Fungsi dasar |
| 4 | Algoritma dan pemeriksaan |
| 5 | Eksperimen |
| 6 | Ringkasan, reproduksi, uji statistik, waktu |
| 7 | Ekspor |
| 8 | Spesifikasi sistem |
| 9 | Muat ulang data final |
| 10 | Baris vs kolom |
| 11 | Ablasi potensial kolom |
| 12 | Instans terstruktur |
| 13 | Pencarian lokal kasus buruk |

## File Program

File utama dalam repository ini:

- `kode program matching berbobot.ipynb`

File tersebut merupakan notebook Jupyter yang dapat dibuka melalui Google Colab atau Jupyter Notebook.

## Cara Mengakses

Klik file notebook pada repository untuk melihat kode program.

Untuk menjalankan program, unduh notebook atau buka melalui Google Colab.

## Spesifikasi Lingkungan Komputasi

Eksperimen dijalankan menggunakan lingkungan komputasi dengan spesifikasi berikut:

| Komponen | Spesifikasi |
|---|---|
| Sistem Operasi | Linux 6.6.122+ x86_64 |
| Versi Python | 3.13.16 |
| NumPy | 2.1.3 |
| SciPy | 1.16.3 |
| pandas | 2.2.3 |
| Jumlah Inti CPU | 2 |
| Prosesor | Intel(R) Xeon(R) CPU @ 2.20GHz |
| Memori | 12.67 GiB |

## Cara Menjalankan Program

1. Buka file notebook `kode program matching berbobot.ipynb`.
2. Unduh notebook atau buka melalui Google Colab.
3. Jalankan cell secara berurutan sesuai susunan notebook.
4. Pastikan pustaka yang diperlukan tersedia pada lingkungan Python.

Notebook terdiri atas 13 cell yang mencakup pengaturan eksperimen, implementasi algoritma, pelaksanaan eksperimen, hingga analisis tambahan.
