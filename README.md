# 📊 Data Science 2026 — Portofolio Praktikum
 
**Nama:** Mohammad Riyan Syaifunahar
**NIM:** 240401010292
**Kelas:** PJJ Informatika
**Program Studi:** Informatika — Universitas Siber Asia (UNSIA)
**Mata Kuliah:** Pengantar Data Science (Kode: 200302305, 3 SKS, Semester 4)
**Koordinator:** Syahid Abdullah, S.Si, M.Kom
 
---
 
## 👋 Perkenalan
 
Repository ini merupakan kumpulan notebook hasil praktikum mata kuliah **Pengantar Data Science** yang saya tempuh di Universitas Siber Asia (UNSIA).
 
Selama 7 pertemuan, saya membangun pemahaman Data Science dari fondasi hingga implementasi model Machine Learning pertama. Perjalanan belajar ini dimulai dari pengenalan Python dan ekosistem tools-nya, dilanjutkan dengan eksplorasi dan pembersihan data, statistika deskriptif, visualisasi, persiapan data untuk Machine Learning, hingga membangun dan mengevaluasi model Regresi Linear secara end-to-end. Repository ini mencerminkan perjalanan belajar saya secara lengkap, terstruktur, dan terdokumentasi.
 
---
 
## 📚 Daftar Pertemuan & Notebook
 
| # | Topik | Dataset | Notebook |
|---|-------|---------|----------|
| 1 | Pengenalan Data Science — Python, Variabel, Tipe Data, List & Fungsi | — | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan1_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| 2 | Struktur Data Python, NumPy & Pandas | Titanic (CSV) | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan2_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| 3 | Data Cleaning — Missing Values, Outlier & Ekstraksi Data | housing_dirty.csv + JSONPlaceholder API | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan3_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| 4 | Statistika Deskriptif & Analisis Eksploratori Data (EDA) | Seaborn built-in | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan4_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| 5 | Visualisasi Data — Matplotlib & Seaborn | Tips / Iris / Titanic | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan5_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| 6 | Persiapan Data — Encoding, Scaling & Train-Test Split | Titanic (Seaborn) | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan6_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| 7 | Pengantar Machine Learning — Regresi Linear | Sintetis Prediksi Gaji (300 baris) | [📓 Buka Notebook](https://github.com/0xjessie21/data-science-2026/blob/main/Pertemuan7_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
 
---
 
## 🛠️ Tools & Library yang Digunakan
 
| Kategori | Tools / Library |
|----------|----------------|
| Bahasa Pemrograman | Python 3 |
| Struktur Data & Komputasi Numerik | NumPy, Python built-in (list, dict, tuple, set) |
| Manipulasi & Analisis Data | Pandas |
| Visualisasi | Matplotlib, Seaborn |
| Data Cleaning | missingno, scipy.stats, scipy.stats.mstats |
| Encoding & Scaling | scikit-learn (`LabelEncoder`, `OneHotEncoder`, `OrdinalEncoder`, `MinMaxScaler`, `StandardScaler`, `RobustScaler`) |
| Machine Learning | scikit-learn (`LinearRegression`, `train_test_split`, `KNNImputer`) |
| Evaluasi Model | scikit-learn (`mean_absolute_error`, `mean_squared_error`, `r2_score`) |
| Ekstraksi Data | `requests`, `json`, `pandas.json_normalize` |
| Lingkungan Kerja | Google Colaboratory, Jupyter Notebook |
| Version Control & Portofolio | Git, GitHub |
 
---
 
## ▶️ Cara Menjalankan Notebook
 
### Opsi 1 — Google Colab (Direkomendasikan)
1. Klik link **📓 Buka Notebook** pada tabel di atas
2. Di halaman GitHub, klik tombol **"Open in Colab"** di bagian atas file
3. Jalankan semua sel: **Runtime → Restart & Run All**
4. Pastikan semua sel berjalan tanpa error dari atas ke bawah
### Opsi 2 — Lokal (Jupyter Notebook)
```bash
# Clone repository
git clone https://github.com/0xjessie21/data-science-2026.git
cd data-science-2026
 
# Install semua dependensi
pip install numpy pandas matplotlib seaborn scikit-learn \
            scipy missingno requests jupyter
 
# Jalankan Jupyter
jupyter notebook
```
 
---
 
## 📝 Kesimpulan Perjalanan Belajar Data Science Pertemuan 1–7
 
Tujuh pertemuan ini membentuk satu pipeline Data Science yang utuh dan saling berkaitan:
 
**Fondasi (Pertemuan 1–2):** Pertemuan 1 membangun dasar Python yang solid — memahami tipe data, struktur kontrol, fungsi, dan ekosistem tools (Colab, GitHub). Pertemuan 2 memperdalam kemampuan teknis dengan NumPy untuk komputasi numerik yang efisien dan Pandas sebagai tulang punggung manipulasi data tabular, termasuk filtering, groupby, dan analisis dataset Titanic.
 
**Kualitas & Pemahaman Data (Pertemuan 3–4):** Pertemuan 3 mengajarkan bahwa kualitas data adalah segalanya — prinsip *Garbage In, Garbage Out* menjadi landasan seluruh proses. Teknik penanganan missing values (imputasi statistik, KNN Imputer), deteksi dan penanganan outlier (IQR Fence, Z-Score, Winsorization), serta ekstraksi data dari JSON dan REST API dipraktikkan langsung pada dataset `housing_dirty.csv`. Pertemuan 4 membangun pemahaman statistika deskriptif sebagai dasar berpikir kuantitatif dalam menganalisis distribusi dan hubungan antar variabel.
 
**Komunikasi Visual (Pertemuan 5):** Pertemuan 5 membuktikan bahwa kemampuan memvisualisasikan data sama pentingnya dengan kemampuan menganalisisnya. Menggunakan Matplotlib untuk grafik dasar (bar, line, scatter) dan Seaborn untuk grafik statistik (histogram, boxplot, violin, pair plot), serta kerangka *What? So what? Now what?* untuk menarik insight yang bermakna dan actionable dari setiap grafik.
 
**Persiapan Model (Pertemuan 6):** Pertemuan 6 mengintegrasikan semua pembelajaran sebelumnya dalam pipeline preprocessing yang benar: Encoding kategorikal (Label, One-Hot, Ordinal), Feature Scaling (MinMaxScaler, StandardScaler, RobustScaler), dan Train-Test Split dengan stratifikasi — semuanya dalam urutan yang tepat untuk menghindari *data leakage*.
 
**Machine Learning (Pertemuan 7):** Pertemuan 7 mengintegrasikan seluruh pembelajaran dalam pipeline *end-to-end* Machine Learning pertama menggunakan Regresi Linear. Dari generate dataset → EDA → preprocessing → fit model → evaluasi (MAE, RMSE, R²) → visualisasi Actual vs Predicted dan Residual Plot. Model berhasil mencapai **R² ≈ 0.95**, membuktikan bahwa pipeline yang benar menghasilkan model yang dapat dipercaya.
 
Perjalanan ini menegaskan bahwa Data Science bukan sekadar kumpulan teknik dan alat, melainkan cara berpikir sistematis dalam mengekstrak pengetahuan dari data untuk menjawab pertanyaan nyata dan mendorong pengambilan keputusan yang lebih baik.
 
---
 
*Repository ini dibuat untuk keperluan pembelajaran akademik — Mata Kuliah Pengantar Data Science, UNSIA 2026.*
