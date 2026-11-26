# Ringkasan Laporan Proyek UTS Machine Learning

## Identitas
- **Nama:** I Made Yudik Pramana
- **NIM:** 2301010460
- **Judul Proyek:** Prediksi Harga Properti per Are Berdasarkan Karakteristik Bangunan, Akses, dan Lokasi

## Dataset
- **File Data:** `data/dataset_properti.csv` (20 baris, 8 kolom)
- **Target (`y`):** `harga_per_are_juta` (juta rupiah per are)
- **Fitur (`X`):** `luas_tanah_are`, `luas_bangunan_m2`, `kamar_tidur`, `kamar_mandi`, `lebar_jalan_m`, `jarak_pusat_km`, dan `lokasi` (kategorikal)

## Alur Pengerjaan di Notebook
1. **Pemahaman Masalah dan Data:** Memuat dataset langsung dari GitHub Raw URL dan memeriksa struktur data (`df.head()`, ukuran data, tipe data).
2. **Eksplorasi dan Visualisasi Data:** Meninjau statistik deskriptif, distribusi nilai, dan hubungan antar variabel.
3. **Pra-pemrosesan Data:** Menangani tipe data (encoding kolom `lokasi` dan scaling fitur numerik) serta membagi data menjadi data latih dan data uji.
4. **Pemodelan:** Melatih model regresi beserta model pembanding (*baseline*).
5. **Evaluasi dan Interpretasi:** Mengevaluasi performa prediksi menggunakan metrik regresi dan analisis residual.
