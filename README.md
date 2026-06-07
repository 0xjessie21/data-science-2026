# 📊 Data Science 2026 — UNSIA
 
> Repository ini mendokumentasikan seluruh aktivitas praktikum mata kuliah **Pengantar Data Science** dari Pertemuan 1 hingga 7, sebagai portofolio pembelajaran dan bahan pengumpulan UTS.
 
---
 
## 🪪 Identitas
 
| Field | Detail |
|---|---|
| **Nama Lengkap** | Mohammad Riyan Syaifunahar |
| **NIM** | 240401010292 |
| **Kelas** | IF401 |
| **Program Studi** | Informatika |
| **Mata Kuliah** | Pengantar Data Science (200302305) |
| **Koordinator** | Syahid Abdullah, S.Si, M.Kom |
 
---
 
## 📖 Deskripsi Repository
 
Repository ini berisi kumpulan notebook Jupyter (`.ipynb`) hasil praktikum mata kuliah Pengantar Data Science semester 2026. Setiap notebook mencerminkan satu pertemuan dengan topik yang saling berkesinambungan — mulai dari pengenalan ekosistem Data Science, eksplorasi dan pembersihan data, visualisasi, hingga membangun model Machine Learning pertama menggunakan Regresi Linear.
 
Tujuan utama: membangun fondasi yang kuat dalam siklus kerja data scientist, dari data mentah hingga insight yang dapat diinterpretasikan.
 
---
 
## 📂 Daftar Pertemuan & Notebook
 
| # | Topik | Notebook |
|---|---|---|
| P1 | Pengenalan Data Science, CRISP-DM, Setup Google Colab & GitHub, Python Dasar | [Pertemuan1_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan1_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| P2 | Struktur Data Python, NumPy, Pandas (Series, DataFrame, Filtering, GroupBy) — Dataset Titanic | [Pertemuan2_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan2_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| P3 | Data Cleaning: Missing Values, Duplikat, Outlier (IQR/Z-Score/Winsorization), JSON & REST API — Dataset `housing_dirty.csv` | [Pertemuan3_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan3_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| P4 | Statistika Deskriptif (Mean/Median/Modus/Std/Skewness/Kurtosis), Distribusi, Analisis Univariat & Bivariat, Korelasi Pearson/Spearman — Dataset Iris | [Pertemuan4_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan4_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| P5 | Visualisasi Data dengan Matplotlib & Seaborn, Framework What–So What–Now What, Dashboard Statis | [Pertemuan5_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan5_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| P6 | Persiapan Data ML: Encoding (Label/OHE/Ordinal), Scaling (MinMax/Standard/Robust), Train-Test Split, Stratified Split, Data Leakage — Dataset Titanic | [Pertemuan6_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan6_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| P7 | Pengantar Machine Learning: Regresi Linear (Supervised vs Unsupervised, Simple/Multiple Regression, MSE, Gradient Descent, Scikit-Learn, MAE/RMSE/R²) | [Pertemuan7_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb](./Pertemuan7_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
 
---
 
## 🛠️ Tools & Library
 
| Kategori | Tools |
|---|---|
| **Bahasa** | Python 3 |
| **Environment** | Google Colaboratory, Jupyter Notebook |
| **Manipulasi Data** | NumPy, Pandas |
| **Visualisasi** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn (sklearn) |
| **Lainnya** | Requests (REST API), json, os |
 
---
 
## ▶️ Cara Menjalankan Notebook
 
**Via Google Colab (direkomendasikan):**
1. Klik link notebook pada tabel di atas
2. Klik tombol **"Open in Colab"** di bagian atas halaman GitHub
3. Pilih `Runtime → Run all` untuk menjalankan seluruh sel
**Via Lokal (Jupyter):**
```bash
git clone https://github.com/0xjessie21/data-science-2026.git
cd data-science-2026
jupyter notebook
```
 
---
 
## 💡 Kesimpulan Perjalanan Belajar (P1–P7)
 
Selama tujuh pertemuan ini, saya membangun pemahaman menyeluruh tentang siklus kerja seorang data scientist menggunakan framework CRISP-DM sebagai panduan.
 
Dimulai dari **fondasi Python dan Pandas** (P1–P2), saya belajar memanipulasi data tabular secara efisien. Di **P3**, tantangan terbesar adalah data kotor di dunia nyata — missing values, outlier, dan inkonsistensi format — yang harus diselesaikan sebelum analisis apapun dapat dilakukan. **P4** membuka perspektif statistik: bagaimana distribusi, korelasi, dan skewness memberikan narasi tersembunyi dalam data. **P5** mengajarkan bahwa visualisasi bukan sekadar grafik, melainkan alat komunikasi — framework What–So What–Now What membantu mengubah chart menjadi insight yang actionable.
 
Pertemuan **P6** adalah turning point: memahami bahwa preprocessing yang salah (data leakage, scaling sebelum split) bisa merusak seluruh model secara diam-diam. Terakhir, **P7** menyatukan semua materi sebelumnya dalam satu pipeline end-to-end Machine Learning, mengimplementasikan Regresi Linear dan mengevaluasinya dengan MAE, RMSE, dan R².
 
**Temuan utama:** Kualitas data jauh lebih menentukan performa model dibanding pilihan algoritma. Garbage in, garbage out.
 
**Keterbatasan & pertanyaan terbuka:** Regresi Linear bekerja baik untuk hubungan linear, namun bagaimana menangani data dengan hubungan non-linear? Apa batasan R² sebagai metrik tunggal? Topik ini menjadi motivasi untuk pertemuan-pertemuan berikutnya.
 
---
 
<p align="center">
  <sub>© 2026 Mohammad Riyan Syaifunahar · UNSIA · Pengantar Data Science</sub>
</p>
 
---
 
*Repository ini dibuat untuk keperluan pembelajaran akademik — Mata Kuliah Pengantar Data Science, UNSIA 2026.*
