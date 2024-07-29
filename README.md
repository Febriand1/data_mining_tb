# Analisis Klaster Pelanggan Pada Toko Online

## Anggota Kelompok 1

|No | Nama                                   | NPM     |
|---|----------------------------------------|---------|
| 1 | Dirga Febrian                          | 1214039 |
| 2 | Rizkyria Angelina Pandapotan Hutabarat | 1214023 |
| 3 | Juwita Stefany Hutapea                 | 1214026 |
| 4 | Marlina Magdalena Lubis                | 1214040 |

## Pendahuluan

Tugas ini merupakan proses dari pembuatan buku **"Tutorial Analisis Klaster Pelanggan Toko Online"**. Pada buku ini di berikan panduan lengkap bagaimana melakukan analisis klaster pelanggan pada toko online menggunakan algoritma model K-Means dan evaluasi model Silhouette Score.

## Tahapan Analisis Klaster

Proses analisis klaster pelanggan menggunakan metodologi CRISP-DM.
1. **Business Understanding (Pemahaman Bisnis)**
    - Tujuan: Mengidentifikasi tujuan bisnis dan menentukan tujuan analisis.
    - Langkah-langkah: 
        - Diskusikan dengan anggota yang kepentingan untuk memahami kebutuhan analisis. Misalnya, tujuan analisis ini mungkin untuk memahami segmentasi pelanggan dan meningkatkan strategi pemasaran

2. **Data Understanding (Pemahaman Data)**
    - Tujuan: Mengumpulkan dan memahami data yang ada.
    - Langkah-langkah:
        - Mengumpulkan data pelanggan yang relevan (misalnya, data transaksi, demografi, p2) erilaku pembelian.
        - Melakukan eksplorasi data awal untuk memahami struktur data dan mencari anomali.

3. **Data Preparation (Persiapan Data)**
    - Tujuan: Memilih, membersihkan, dan mengubah data menjadi format yang sesuai untuk pemodelan.
    - Langkah-langkah: 
        - Mengatasi missing values
        - Menghapus atau mengimputasi outlier
        - Standarisasi dan encode/mapping data

4. **Modeling (Pemodelan)**
    - Tujuan: Membuat dan melatih model K-Means
    - Langkah-langkah: 
        - Menentukan jumlah cluster (k) menggunakan metode seperti Elbow Method.
        - Melatih model K-Means dan membuat prediksi.

5. **Evalution (Evalusai)**
    - Tujuan: Mengevalusi kualitas model 
    - Langkah-langkah: 
        - Menggunakan metrik evaluasi seperti Silhouette Score untuk menilai kualitas clustering.
        - Melakukan validasi model dengan data yang berbeda jika memungkinkan.

6. **Deployment (Implementasi)**
    - Tujuan: Mengimplementasikan hasil analisis ke dalam operasional bisnis.
    - Langkah-langkah: 
        - Menyusun laporan hasil analisis dan memberikan rekomendasi bisnis berdasarkan hasil clustering.
        - Mengintegrasikan hasil clustering ke dalam sistem yang digunakan untuk kegiatan pemasaran atau personalisasi layanan.