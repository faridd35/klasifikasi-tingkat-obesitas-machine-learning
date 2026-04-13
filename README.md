# Analisis Klasifikasi Tingkat Obesitas Menggunakan Algoritma Decision Tree dan Naive Bayes

Proyek ini bertujuan untuk mengklasifikasikan tingkat obesitas individu berdasarkan kebiasaan makan dan kondisi fisik menggunakan dua algoritma pembelajaran mesin: **Decision Tree** dan **Naive Bayes**.

## 📊 Deskripsi Data
Dataset yang digunakan bersumber dari *UCI Machine Learning Repository* dengan judul "Estimation of Obesity Levels Based on Eating Habits and Physical Condition".

- **Jumlah Data**: 2.111 entri.
- **Fitur**: 16 fitur prediktor (Kebiasaan makan, aktivitas fisik, transportasi, dll).
- **Label (NObeyesdad)**: 7 kategori (Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, Obesity Type III).

## 🛠️ Metodologi
Penelitian ini membandingkan kinerja dua algoritma:
1. **Decision Tree**: Menggunakan struktur pohon keputusan untuk pemisahan data berdasarkan atribut.
2. **Naive Bayes**: Pendekatan probabilistik menggunakan Teorema Bayes (GaussianNB).

### Skema Pengujian
- **Metode Holdout**: Pembagian data 80:20 dan 70:30.
- **K-Fold Cross Validation**: Pengujian dengan $k=5$ dan $k=10$.

## 📈 Hasil Evaluasi
Berdasarkan pengujian, **Decision Tree** menunjukkan performa yang jauh lebih unggul dan stabil dibandingkan Naive Bayes pada dataset ini.

| Algoritma | Akurasi Tertinggi (K-Fold 10) | Presisi | Recall |
| :--- | :---: | :---: | :---: |
| **Decision Tree** | **0.942** | 0.942 | 0.942 |
| **Naive Bayes** | **0.604** | 0.623 | 0.604 |

## 💻 Teknologi yang Digunakan
- **Bahasa**: Python
- **Library**: 
  - Pandas & NumPy (Manipulasi Data)
  - Scikit-Learn (Modeling & Evaluasi)
  - Matplotlib (Visualisasi)
- **Environment**: Jupyter Notebook / Google Colab

---
*Proyek ini disusun untuk Kebutuhan Tugas Mata Kuliah Machine Learning - 
Pendidikan Teknik Informatika dan Komputer, Universitas Negeri Jakarta.*
