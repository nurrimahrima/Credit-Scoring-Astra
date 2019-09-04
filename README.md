# Study-Case-Astra-Creditscore

## Informasi Data
Data berisi informasi terkait pelanggan kartu kredit di suatu negara pada periode Januari-Maret 2015.
Informasi meliputi latar belakang pelanggan, jumlah tagihan, jumlah pembayaran, lama terlambat bayar
dan status pembayaran bulan berikutnya (April 2015).

## Tujuan Pemodelan
Memprediksi apakah pelanggan kartu kredit beresiko terlambat bayar pada bulan Mei berdasarkan data
pada bulan Februari-April 2015 pada data testing.

## Deskripsi Feature

Terdapat 16 peubah yang terdiri dari ID, 14 prediktor dan 1 target.

| Nama Peubah   | Deskripsi                  | Tipe & Satuan   |       Keterangan          |
| ------------- |:-------------------------: |:---------------:|--------------------------:|
| ID            | Nomor urut                 | character       |                           |
| AGE           | Umur                       | Kontinyu (tahun)|                           |
| LIMIT_BAL     | Batas maksimal kredit      | Kontinyu (USD)  |                           |
| EDUCATION     | Tingkat pendidikan         |    Kategorik    | 1: S2/S3                  |
|               |                            |                 | 2: Dipl/S1                |
|               |                            |                 | 3: SMA                    |
|               |                            |                 | 4: Lainnya                |
| MARRIAGE      | Status Pernikahan          |    Kategorik    | 1: Belum Menikah          |
|               |                            |                 | 2: Menikah                |
|               |                            |                 | 3: Lainnya                |
| SEX           | Nomor urut                 |    Kategorik    | 1: Pria                   |
|               |                            |                 | 2: Wanita                 |
| PAY_1 … 3     | Umur                       |    Kategorik    | 0: Tepat waktu            |
|               |                            |                 | 1: Terlambat 1 bulan, dst |
| BILL_AMT1 … 3 | Batas maksimal kredit      |  Kontinyu (USD) |                           |
| PAY_AMT1 …3   | Nomor urut                 |  Kontinyu (USD) |                           |
| TARGET        | Umur                       |    Kategorik    | 1: Terlambat              |
|               |                            |                 | 0: Tidak terlambat        |

Sumber data: UCI Learning Machine Repository “Default of credit card clients data set”.
Data dimodifikasi untuk keperluan botdcamp.

## Penilaian mencakup
- Memahami kasus dan tujuan pemodelan
- Memahami makna setiap feature
- Memahami pola data
- Dapat menjelaskan hubungan antara feature dengan label
- Identifikasi data ekstrim / outliers
- Memahami tujuan transformasi data
- Mengetahui teknik-teknik transformasi data
- Dapat mengidentifikasi dampak dari transformasi data
- Dapat melakukan pemodelan (model klasifikasi) 
- Memahami ukuran kebaikan model
- Dapat membandingkan ukuran kebaikan antara beberapa model
