# Pertemuan 05 Perulangan Python

Nama: Nuril Ilmy
NIM: 2225250066
Kelas: Pendidikan Matematika

## Tujuan

Menggunakan perulangan `for` dan `while` untuk menyelesaikan masalah iteratif, melakukan validasi input, menggunakan seleksi di dalam perulangan, serta melakukan pengujian program.

## Struktur Folder

```text
pertemuan-05-perulangan-2225250066/
│
├── README.md
├── .gitignore
│
├── latihan/
│   ├── 01_tabel_perkalian.py
│   ├── 02_jumlah_bilangan.py
│   ├── 03_validasi_input.py
│   └── 04_hitung_genap.py
│
└── kuis/
    └── kuis2_deret_aritmetika.py
```

## Cara Menjalankan

Pastikan terminal VS Code berada di folder utama proyek.

### Latihan 1

```bash
python latihan/01_tabel_perkalian.py
```

### Latihan 2

```bash
python latihan/02_jumlah_bilangan.py
```

### Latihan 3

```bash
python latihan/03_validasi_input.py
```

### Latihan 4

```bash
python latihan/04_hitung_genap.py
```

### Kuis 2

```bash
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

1. Membaca suku pertama `a`.
2. Membaca beda `d`.
3. Membaca banyak suku `n`.
4. Jika `n <= 0`, program meminta input `n` kembali sampai valid.
5. Mengatur `total = 0`.
6. Menggunakan `for` untuk menghasilkan suku sebanyak `n` kali.
7. Menghitung setiap suku dengan rumus:

```text
suku = a + i × d
```

8. Menambahkan setiap suku ke dalam `total`.
9. Menampilkan nomor suku dan nilai suku.
10. Menampilkan jumlah seluruh suku setelah perulangan selesai.

## Hasil Pengujian

### Latihan 1 — Tabel Perkalian

**Test case 1**

Input:

```text
4
```

Program menampilkan tabel perkalian 4 dari 1 sampai 10.

**Test case 2**

Input:

```text
-3
```

Program menampilkan tabel perkalian -3 dari 1 sampai 10.

Jumlah baris keluaran tetap 10.

### Latihan 2 — Jumlah Bilangan

| Input | Hasil yang Diharapkan |
| ----: | --------------------: |
|     1 |                     1 |
|     5 |                    15 |
|    10 |                    55 |

### Latihan 3 — Validasi Input

Input:

```text
120
-5
75
```

Hasil:

```text
Nilai tidak valid.
Nilai tidak valid.
Nilai diterima: 75.0
```

Program menolak nilai 120 dan -5 karena berada di luar rentang 0 sampai 100, kemudian menerima nilai 75.

### Latihan 4 — Menghitung Bilangan Genap

| Input n | Hasil yang Diharapkan |
| ------: | --------------------: |
|       1 |                     0 |
|       2 |                     1 |
|       5 |                     2 |
|      10 |                     5 |

### Kuis 2 — Deret Aritmetika

**Test case 1**

```text
a = 2
d = 3
n = 5
```

Hasil:

```text
Suku ke-1: 2.00
Suku ke-2: 5.00
Suku ke-3: 8.00
Suku ke-4: 11.00
Suku ke-5: 14.00
Jumlah = 40.00
```

**Test case 2**

```text
a = 10
d = -2
n = 4
```

Hasil:

```text
Suku ke-1: 10.00
Suku ke-2: 8.00
Suku ke-3: 6.00
Suku ke-4: 4.00
Jumlah = 28.00
```

**Test case 3**

```text
a = 1.5
d = 0.5
n = 3
```

Hasil:

```text
Suku ke-1: 1.50
Suku ke-2: 2.00
Suku ke-3: 2.50
Jumlah = 6.00
```

## Refleksi

Pada pertemuan ini saya mempelajari penggunaan perulangan `for` dan `while` dalam Python. `for` digunakan ketika jumlah iterasi sudah diketahui atau ketika program mengunjungi suatu urutan nilai. `while` digunakan ketika perulangan dikendalikan oleh suatu kondisi.

Kesalahan yang perlu diperhatikan dalam perulangan adalah batas `range`, pembaruan variabel pada `while`, dan posisi akumulator. Jika variabel kontrol pada `while` tidak diperbarui, program dapat mengalami infinite loop. Jika `total = 0` diletakkan di dalam loop, nilai total akan terus di-reset.

Saya juga belajar melakukan pengujian menggunakan beberapa test case dan memeriksa perubahan nilai variabel pada setiap iterasi.

## Kesimpulan

Perulangan `for` dan `while` dapat digunakan untuk menjalankan proses secara berulang. Pemilihan jenis perulangan harus disesuaikan dengan masalah yang dikerjakan. Pengujian dan tracing diperlukan untuk memastikan perulangan berhenti pada kondisi yang benar dan menghasilkan output yang sesuai.

## Sumber

* Materi Pertemuan 05 Algoritma dan Pemrograman, Perulangan `for` dan `while` dalam Python di VS Code dan Pengumpulan melalui GitHub.
* Python Software Foundation — Python 3 Documentation.
* Visual Studio Code Documentation — Python in Visual Studio Code.
* GitHub Docs — Creating a New Repository dan Adding Locally Hosted Code to GitHub.
