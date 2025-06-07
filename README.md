# Final Project Komputasi Numerik - Interpolasi Newton-Gregory Backward
## Kelompok A-20

| NRP        | Nama Lengkap                 |
| :--------- | :--------------------------- |
| 5025241070 | Azil Arliansyah Hidayat      |
| 5025241097 | Adriel Mahira Dharma         |
| 5025241119 | Naura Taqiyya Mazi           |
| 5025241120 | Raditya Zhafran P.           |
| 5025241121 | Riyannizaar Dwi A.           |

## Penjelasan Kode

Program ini bertujuan untuk mengestimasi nilai `y` pada suatu titik `x` yang tidak ada dalam data, berdasarkan sekumpulan titik (`x`, `y`) yang telah diketahui. Metode Newton-Gregory Backward sangat efektif ketika nilai `x` yang dicari berada di dekat akhir himpunan data.

**Cara Kerja Program:**

1.  **Input**: Program meminta user memasukkan:
    *   Sekumpulan titik `x` dan `y`.
    *   Titik acuan `x0`.
    *   Nilai `x` yang ingin dicari nilai `y`-nya.

2.  **Proses**:
    *   Kode akan secara otomatis membangun **Tabel Selisih Mundur (Backward Difference Table)** dari data `y`.
    *   Selanjutnya, program menghitung parameter `h` (jarak antar-x) dan `u`.
    *   Dengan menggunakan tabel selisih dan parameter tersebut, program menerapkan rumus interpolasi Newton-Gregory Backward untuk menghitung nilai `y`.

3.  **Output**: Program akan menampilkan Tabel Selisih Mundur yang telah dibuat, langkah-langkah perhitungan, dan hasil akhir dari nilai `y` yang diinterpolasi.
