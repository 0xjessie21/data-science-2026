<div align="center">

# 📊 Data Science 2026

### `Pengantar Data Science · 200302305 · UNSIA 2026`

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![GitHub](https://img.shields.io/badge/Repo-Public-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/0xjessie21/data-science-2026)

<br/>

> *"In God we trust. All others must bring data."*
> — W. Edwards Deming

</div>

---

## 👤 Identitas

<table>
  <tr><td><b>Nama Lengkap</b></td><td>Mohammad Riyan Syaifunahar</td></tr>
  <tr><td><b>NIM</b></td><td>240401010292</td></tr>
  <tr><td><b>Kelas</b></td><td>IF401</td></tr>
  <tr><td><b>Program Studi</b></td><td>Informatika</td></tr>
  <tr><td><b>Mata Kuliah</b></td><td>Pengantar Data Science (200302305)</td></tr>
  <tr><td><b>Koordinator</b></td><td>Syahid Abdullah, S.Si, M.Kom</td></tr>
</table>

---

## 📌 Tentang Repository

Repository ini mendokumentasikan **7 pertemuan praktikum** mata kuliah Pengantar Data Science secara lengkap dan terstruktur — mulai dari setup environment hingga membangun model Machine Learning pertama. Setiap notebook merupakan rekam jejak pembelajaran yang autentik, mengikuti framework **CRISP-DM** sebagai tulang punggung alur kerja.

```
RAW DATA  ──▶  CLEANING  ──▶  EDA  ──▶  VISUALISASI  ──▶  PREPROCESSING  ──▶  MODEL  ──▶  EVALUASI
   P3              P3          P4           P5                  P6              P7           P7
```

---

## 🗂️ Daftar Notebook

| Pertemuan | Topik Utama | Dataset | Notebook |
|:---------:|-------------|:-------:|:--------:|
| **P1** | Pengenalan Data Science · CRISP-DM · Setup Colab & GitHub · Python Dasar | — | [📓 Buka](./Pertemuan1_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| **P2** | NumPy · Pandas · Series & DataFrame · Filtering · GroupBy | 🚢 Titanic | [📓 Buka](./Pertemuan2_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| **P3** | Data Cleaning · Missing Values · Outlier (IQR / Z-Score / Winsorization) · REST API | 🏠 housing_dirty | [📓 Buka](./Pertemuan3_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| **P4** | Statistika Deskriptif · Distribusi · Korelasi Pearson & Spearman · Univariat & Bivariat | 🌸 Iris | [📓 Buka](./Pertemuan4_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| **P5** | Visualisasi Matplotlib & Seaborn · Framework What–So What–Now What · Dashboard Statis | 🌸 Iris | [📓 Buka](./Pertemuan5_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| **P6** | Encoding (Label / OHE / Ordinal) · Scaling (MinMax / Standard / Robust) · Train-Test Split · Data Leakage | 🚢 Titanic | [📓 Buka](./Pertemuan6_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |
| **P7** | Linear Regression · Cost Function MSE · Gradient Descent · Scikit-Learn · MAE / RMSE / R² | 💼 Salary Synthetic | [📓 Buka](./Pertemuan7_MOHAMMAD_RIYAN_SYAIFUNAHAR_240401010292.ipynb) |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-2CA5E0?style=for-the-badge&logoColor=white)

---

## ▶️ Cara Menjalankan

**☁️ Google Colab** *(direkomendasikan)*
```
1. Klik link notebook di tabel atas
2. Klik "Open in Colab" di header GitHub
3. Runtime → Restart and Run All
```

**💻 Lokal**
```bash
git clone https://github.com/0xjessie21/data-science-2026.git
cd data-science-2026
pip install numpy pandas matplotlib seaborn scikit-learn requests
jupyter notebook
```

---

## 💡 Kesimpulan Perjalanan Belajar

Tujuh pertemuan ini membentuk satu pipeline penuh dari **raw data → model**. Beberapa insight paling berharga:

- **P3 → Data adalah segalanya.** Sebelum model apapun bisa dibangun, data harus bersih — missing values dan outlier yang tidak ditangani akan mencemari seluruh analisis downstream.
- **P4 → Statistik adalah bahasa data.** Skewness, kurtosis, dan korelasi bukan sekadar angka — mereka adalah sinyal yang mengarahkan keputusan fitur.
- **P5 → Visualisasi adalah komunikasi.** Framework *What–So What–Now What* mengubah grafik menjadi narasi yang bisa dipresentasikan ke stakeholder.
- **P6 → Preprocessing yang salah = model yang bohong.** Data leakage adalah bug yang tidak terlihat tapi mematikan — scaling harus terjadi *setelah* train-test split, bukan sebelumnya.
- **P7 → Semua bermuara di sini.** Linear Regression membuktikan bahwa pipeline yang benar menghasilkan model yang bisa dipercaya, dievaluasi, dan dijelaskan.

> **Temuan utama:** *Garbage in, garbage out* — kualitas data 10x lebih menentukan hasil akhir dibanding pilihan algoritma.

> **Pertanyaan terbuka:** Bagaimana menangani hubungan non-linear? Kapan R² menyesatkan? → Motivasi untuk pertemuan selanjutnya.

---

<div align="center">

`© 2026 · Mohammad Riyan Syaifunahar · NIM 240401010292 · Informatika UNSIA`

</div>
