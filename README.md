# evaluasi_learning


# 📈 Analisis Dampak Pembelajaran 

## 📝 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis efektivitas intervensi pembelajaran berdasarkan kerangka evaluasi **Metode Kirkpatrick**, khususnya pada **Level 2 (Learning)**. Analisis dilakukan terhadap hasil pre-test dan post-test dari 30 peserta pelatihan yang berasal dari berbagai provinsi di Indonesia.

## 📊 Tujuan Analisis
- Mengukur kenaikan nilai peserta setelah mengikuti pembelajaran.
- Menilai seberapa besar efek pembelajaran menggunakan pendekatan statistik.
- Menggali hubungan antara demografi peserta (jenis kelamin, domisili, usia) dan hasil pembelajaran.
- Memberikan rekomendasi berbasis data untuk pengembangan program di masa depan.

## 🧾 Data yang Digunakan
- Jumlah peserta: 30 orang
- Variabel:
  - Nama Peserta
  - Domisili
  - Jenis Kelamin
  - Usia (18–24 tahun)
  - Nilai Pre-Test
  - Nilai Post-Test

## 📌 Hasil Utama
- **Kenaikan rata-rata nilai**: +15.67% (dari 7.67 ke 8.87)
- **Efektivitas program signifikan secara statistik** (Wilcoxon Signed Rank Test, p ≈ 0)
- **Efek pembelajaran besar** (Cliff’s Delta = 0.9)
- **Performa peserta lebih seragam** di post-test (penurunan standar deviasi dari 0.7 ke 0.38)
- Tidak ada perbedaan signifikan antara laki-laki dan perempuan
- Usia tidak berkorelasi signifikan dengan hasil belajar
- Peserta luar Jawa menunjukkan performa lebih baik

## 🧠 Tools & Library yang Digunakan
- Python
- Pandas
- SciPy (Wilcoxon, Shapiro-Wilk, Mann-Whitney U Test)
- NumPy
- Matplotlib / Seaborn (untuk visualisasi, jika ada)
