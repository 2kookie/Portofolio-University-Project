📁 Daftar Project
1. 🖼️ Klasifikasi Gambar: Rock–Paper–Scissors

File: KlasifikasiGambar-MachineLearning.ipynb

📌 Deskripsi Singkat

Model deep learning untuk klasifikasi gambar tangan (batu, kertas, gunting) menggunakan Convolutional Neural Network (CNN) dengan akurasi sekitar 92.5%.

✨ Fitur Utama

CNN dengan 3 convolutional layers

Data augmentation untuk meningkatkan variasi data

Early stopping ketika akurasi mencapai threshold

Fitur upload gambar untuk prediksi langsung

🛠️ Teknologi

TensorFlow, Keras, NumPy, Matplotlib, Jupyter Notebook

2. 📊 Analisis Data Kredit: Exploratory & Statistical Analysis

File: M09_TGS (1).ipynb

📌 Deskripsi Singkat

Analisis hubungan variabel demografi, finansial, dan status persetujuan kredit menggunakan dataset 60 nasabah. Menggunakan visualisasi statistik, data profiling, dan uji hipotesis.

✨ Fitur Utama

Analisis korelasi lengkap (heatmap)

Eksplorasi 11 variabel (7 numerik, 4 kategorikal)

Visualisasi interaktif dengan anotasi nilai korelasi

Integrasi Google Colab + Google Drive

Uji statistik (T-Test & Chi-Square) menggunakan SciPy

🛠️ Teknologi

Pandas – manipulasi data

NumPy – komputasi numerik

Seaborn & Matplotlib – visualisasi data

SciPy – uji statistik

Google Colab – environment notebook

📊 Dataset Overview (60 sampel, 11 fitur)

Variabel numerik: Age, Income, Debt, CreditCardLimit, Score, Savings
Variabel kategorikal: JobType, Marital, Education, Approved (target)

📈 Temuan Penting

Age ↔ Income = 0.716 (korelasi kuat)

Income ↔ Score = 0.651

Age ↔ Savings = 0.658

CreditCardLimit ↔ Score ≈ -0.004 (tidak berkorelasi)

🎨 Visualisasi

Heatmap korelasi lengkap

Annotated correlation values

Data profiling melalui df.info() & df.head()

3. 🏗️ Arsitektur Data & Dokumentasi Sistem — MRT Jakarta

File: About MRTJ Project.md

📌 Deskripsi Singkat

Project pemetaan arsitektur data dan dokumentasi teknis sebagai bagian dari studi kasus integrasi Data Lake MRT Jakarta. Fokus project meliputi analisis struktur database, pemetaan relasi antar tabel, serta perancangan alur data untuk mendukung integrasi lintas aplikasi.

