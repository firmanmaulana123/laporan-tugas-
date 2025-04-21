
# Laporan Exploratory Data Analysis (EDA)

## Dataset: Boston Housing
**Author:** Firman Maulana Putra  
**Repository:** [firmanmaulana123/eda-boston-housing](https://github.com/firmanmaulana123/eda-boston-housing)

---

## 🏠 Kasus
Dataset Boston Housing berisi data statistik perumahan di wilayah Boston, AS. Dataset ini sering digunakan sebagai bahan ajar dan studi kasus dalam analisis regresi. Tujuan dari analisis ini adalah untuk memahami variabel-variabel apa saja yang berpengaruh terhadap harga rumah (`MEDV`).

---

## 🔍 Analisis
Analisis dilakukan dengan pendekatan *Exploratory Data Analysis (EDA)*, meliputi:

1. **Pengenalan Data:**
   - Melihat jumlah fitur dan observasi.
   - Menampilkan tipe data.
   - Mendeskripsikan statistik dasar setiap kolom.

2. **Pembersihan Data:**
   - Mengecek nilai null atau missing.
   - Identifikasi dan observasi *outlier*.

3. **Visualisasi Data:**
   - Korelasi antar variabel menggunakan heatmap.
   - Scatter plot antara harga rumah dan fitur penting.
   - Distribusi dari target (`MEDV`).

4. **Analisis Korelasi:**
   - Korelasi Pearson untuk mengidentifikasi fitur yang paling memengaruhi harga rumah.

---

## 📊 Hasil

- Fitur **RM** (jumlah kamar) memiliki korelasi positif yang kuat terhadap `MEDV`. Rumah dengan jumlah kamar lebih banyak cenderung memiliki harga lebih tinggi.
- Fitur **LSTAT** (persentase populasi berstatus sosial rendah) memiliki korelasi negatif yang kuat dengan harga rumah.
- Fitur **CRIM** (tingkat kejahatan) memiliki korelasi negatif yang cukup signifikan dengan `MEDV`.
- Visualisasi menunjukkan bahwa distribusi harga rumah tidak simetris dan terdapat beberapa *outlier*.

---

## ✅ Kesimpulan

EDA berhasil mengidentifikasi fitur-fitur penting yang mempengaruhi harga rumah di Boston. Fitur `RM`, `LSTAT`, dan `CRIM` menjadi indikator utama. Distribusi harga rumah yang *skewed* dan keberadaan *outlier* juga menjadi catatan penting untuk tahapan pemodelan selanjutnya.

---

## 📌 Rekomendasi

1. Lakukan transformasi log terhadap fitur yang *skewed*, seperti `CRIM` atau `LSTAT`.
2. Tambahkan fitur turunan (feature engineering) untuk meningkatkan performa model.
3. Lanjutkan ke tahap pemodelan dengan algoritma regresi.
4. Validasi model dengan metode cross-validation dan gunakan metrik evaluasi seperti RMSE dan R².

---

> *Catatan:* Analisis ini dilakukan secara edukatif dan terbuka untuk kontribusi lebih lanjut.
