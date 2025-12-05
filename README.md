# Portofolio-University-Project
Kumpulan Project analisis data dan tugas tugas kuliah

📁 DAFTAR PROJECT
1. 🖼️ Klasifikasi Gambar: Rock Paper Scissors
File: KlasifikasiGambar-MachineLearning.ipynb

Deskripsi Singkat:
Project deep learning untuk klasifikasi gambar tangan dalam permainan batu-kertas-gunting. Menggunakan Convolutional Neural Network (CNN) dengan akurasi mencapai 92.5%.

Fitur:

CNN dengan 3 layer konvolusi

Data augmentation

Upload gambar interaktif

Early stopping saat akurasi >85%

Teknologi: TensorFlow, Keras, Jupyter Notebook


2. 📊 Analisis Data Kredit: Prediksi Persetujuan Kredit
File: M09_TGS (1).ipynb

📌 Deskripsi Singkat
Project analisis data untuk prediksi persetujuan kredit menggunakan dataset 60 nasabah. Menganalisis hubungan antara variabel demografi, finansial, dan status persetujuan kredit dengan visualisasi interaktif dan matriks korelasi.

✨ Fitur Utama
✅ Analisis Korelasi Lengkap: Heatmap matriks korelasi antar variabel numerik

✅ Data Profiling: Eksplorasi 11 variabel (7 numerik, 4 kategorikal)

✅ Visualisasi Interaktif: Plot korelasi dengan annotasi nilai

✅ Google Colab Integration: Koneksi langsung dengan Google Drive

✅ Statistical Analysis: Menggunakan SciPy untuk analisis statistik

🛠️ Teknologi yang Digunakan
Pandas - Manipulasi dan analisis data

NumPy - Komputasi numerik

Seaborn & Matplotlib - Visualisasi data

SciPy - Analisis statistik

Google Colab - Cloud notebook environment

📊 Dataset (60 sampel, 11 fitur)
Variabel Numerik:
No - Nomor urut

Age - Usia (22-60 tahun)

Income - Pendapatan (3.0-15.0)

Debt - Hutang (1.0-6.0)

CreditCardLimit - Batas kartu kredit (1.8-8.9)

Score - Skor kredit (600-730)

Savings - Tabungan (0.1-8.0)

Variabel Kategorikal:
JobType - Tipe pekerjaan (Contract, Permanent, Self-Employed)

Marital - Status pernikahan (Single, Married)

Education - Pendidikan (SMA, Univeristas, SMP)

Approved - Persetujuan kredit (Yes, No) ← Target Variable

📈 Temuan Analisis
Korelasi Signifikan:
🔗 Age vs Income: 0.716 (Korelasi kuat positif)

🔗 Age vs Score: 0.629 (Korelasi positif)

🔗 Income vs Score: 0.651 (Korelasi positif)

🔗 Age vs Savings: 0.658 (Korelasi positif)

Korelasi Lemah:
⚠️ CreditCardLimit vs Score: -0.004 (Hampir tidak berkorelasi)

⚠️ No vs Savings: -0.001 (Tidak berkorelasi)

🎨 Visualisasi yang Dihasilkan
Heatmap Korelasi: Matriks korelasi dengan skala warna coolwarm

Annotated Values: Nilai korelasi pada setiap sel heatmap

Data Summary: Info lengkap dataset dengan df.info() dan df.head()

🚀 Insight Bisnis
Usia berpengaruh terhadap pendapatan dan skor kredit

Tabungan meningkat seiring bertambahnya usia

Batas kartu kredit tidak berkorelasi dengan skor kredit

Potensi model prediktif untuk persetujuan kredit
