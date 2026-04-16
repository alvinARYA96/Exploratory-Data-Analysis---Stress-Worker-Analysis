
# Exploratory Data Analysis - Stress Worker Analysis
### DigitalSkola Data Analyst Bootcamp - Homework Sesi 5

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi tingkat stres pada pekerja. Secara khusus, analisis ini menjawab pertanyaan: **"Apakah kebiasaan merokok dan tingkat pendidikan seorang pekerja berkaitan dengan pengalaman stres mereka?"**

Analisis ini mencakup  visualisasi distribusi, dan pengujian hipotesis secara statistik.

---

## 🛠️ Alur Kerja (Workflow)
1. **Data Profiling**: Memeriksa kualitas data awal.
2. **EDA & Visualisasi**: 
   - Menganalisis proporsi pekerja yang merokok vs tingkat stres.
   - Melihat korelasi tingkat pendidikan dengan pengalaman stres.
3. **Hypothesis Testing**: Menggunakan **Chi-Square Test of Independence** untuk menguji signifikansi hubungan antar variabel kategorikal.

---

## 🚀 Temuan Utama (Key Insights)
Berdasarkan hasil analisis pada notebook:
* **Uji Hipotesis**: Hasil Chi-Square menunjukkan *P-value* sebesar **0.502**, yang berarti **Gagal Menolak H₀**. Tidak cukup bukti bahwa kebiasaan merokok berkaitan langsung dengan stres pada dataset ini.
* **Saran Bisnis**: Perusahaan perlu mempertimbangkan program intervensi HR seperti *smoking cessation program* dan pengembangan SDM berbasis tingkat pendidikan untuk kesejahteraan karyawan.

---

## 📊 Teknologi & Library
* **Python** (Google Colab)
* **Pandas & NumPy** (Data Manipulation)
* **Matplotlib & Seaborn** (Data Visualization)


---

## 📁 Struktur Repositori
```text
├── data/
│   └── stress_worker_clean.csv    # Dataset utama
├── notebook/
│   └── homework_sesi_5.ipynb      # Notebook analisis lengkap
├── README.md                      # Dokumentasi proyek
└── requirements.txt               # Daftar library (dependencies)
