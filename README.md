# 🏠 Boston Housing EDA

Repositori ini berisi proses *Exploratory Data Analysis (EDA)* pada dataset Boston Housing, sebuah dataset klasik yang sering digunakan untuk pembelajaran analisis regresi dan eksplorasi data.

## 📂 Dataset
Dataset digunakan dari library `sklearn.datasets`, berisi informasi seperti:
- Jumlah kamar
- Tingkat kejahatan
- Pajak properti
- Jarak ke fasilitas umum
- Harga rumah (`MEDV`) sebagai target

## 📊 Tools & Library
Proyek ini menggunakan:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Tahapan Analisis
1. **Pembersihan Data**
   - Cek missing value
   - Deteksi outlier

2. **Analisis Statistik**
   - Deskripsi dasar tiap fitur
   - Korelasi antar variabel

3. **Visualisasi**
   - Histogram dan scatter plot
   - Heatmap korelasi

4. **Insight**
   - Fitur `RM`, `LSTAT`, dan `CRIM` sangat memengaruhi harga rumah.

## ✅ Hasil Utama
- `RM` berkorelasi positif terhadap `MEDV`
- `LSTAT` dan `CRIM` berkorelasi negatif
- Distribusi harga rumah tidak normal dan memiliki beberapa outlier

## 📌 Rekomendasi
- Gunakan transformasi log untuk fitur skewed
- Buat fitur turunan untuk eksplorasi lanjutan
- Lanjutkan ke tahap regresi linier atau model prediktif lainnya

## 📁 File
- `EDA_Boston_Housing.ipynb` – Notebook utama analisis
- `laporan_eda_boston.md` – Laporan eksplorasi data lengkap

## ✍️ Author
Firman Maulana Putra  
GitHub: [@firmanmaulana123](https://github.com/firmanmaulana123)
