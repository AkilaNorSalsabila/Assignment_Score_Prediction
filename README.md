# Assignment_Score_Prediction
ML Student Scores Prediction

📌 Overview

Proyek ini menggunakan teknik Machine Learning untuk memprediksi skor siswa berdasarkan jumlah jam belajar mereka. Model yang digunakan termasuk Linear Regression dan Decision Tree untuk membandingkan performa prediksi.

📂 Project Structure

├── data/                 # Dataset yang digunakan
├── notebooks/            # Jupyter Notebook untuk eksplorasi dan training
├── models/               # Model yang sudah dilatih
├── src/                  # Kode utama untuk preprocessing dan training
├── results/              # Hasil prediksi dan visualisasi
└── README.md             # Dokumentasi proyek ini

📊 Dataset

Dataset yang digunakan dalam proyek ini adalah **student_scores.xlsx**.  
Dataset ini berisi data jumlah jam belajar siswa dan skor yang mereka peroleh.  


🚀 Model & Metode

1. Linear Regression
   - Model sederhana untuk memprediksi skor berdasarkan jumlah jam belajar.
   - Cenderung memberikan prediksi yang lebih mulus tetapi bisa gagal menangkap pola kompleks.

2. Decision Tree
   - Model yang lebih fleksibel dalam menangkap pola non-linear.
   - Berpotensi mengalami overfitting jika tidak dikontrol dengan baik.

🔧 Instalasi

Clone repositori ini:

git clone https://github.com/rizkyjisantt-dev/ml-student-scores.git

Masuk ke direktori proyek:

cd ml-student-scores

Install dependensi:

pip install -r requirements.txt

Jalankan notebook di Google Colab atau Jupyter Notebook.

📈 Visualisasi Hasil

Beberapa grafik yang dihasilkan dalam proyek ini:

Scatter Plot untuk melihat hubungan antara jam belajar dan skor.

Garis Prediksi Linear Regression dibandingkan dengan data aktual.

Prediksi Decision Tree untuk menangkap pola lebih detail.

🏆 Kesimpulan

Linear Regression cocok untuk data dengan pola linear sederhana.

Decision Tree lebih fleksibel tetapi berpotensi overfitting.
