# UAS Machine Learning - Implementasi Decision Tree

Tugas ini merupakan bagian dari Ujian Akhir Semester (UAS) yang berfokus pada implementasi algoritma Tree-based Method menggunakan Python.

## 📋 Deskripsi Proyek
Proyek ini melakukan klasifikasi prediksi keselamatan penumpang kapal Titanic menggunakan algoritma **Decision Tree**. Proyek mencakup pemahaman konsep teori, pengolahan data (preprocessing), pembangunan model, hingga evaluasi hasil.

## 📁 Struktur Repositori
* `notebook.ipynb` : File Jupyter Notebook berisi kode Python lengkap (EDA, Preprocessing, Modeling).
* `Laporan_UAS.pdf` : Laporan tertulis lengkap dalam format PDF.
* `README.md` : Panduan singkat mengenai proyek ini.

## 🚀 Metodologi
1. **Load Data**: Menggunakan dataset Titanic dari library Seaborn.
2. **Preprocessing**: 
   - Handling missing values pada kolom 'age'.
   - Label encoding pada fitur 'sex'.
   - Seleksi fitur relevan ('pclass', 'sex', 'age', 'sibsp', 'parch').
3. **Modeling**: Menggunakan `DecisionTreeClassifier` dengan parameter `max_depth=3`.
4. **Evaluation**: Menggunakan Accuracy, Precision, Recall, dan F1-Score.

## 📊 Hasil Analisis
Model berhasil mencapai akurasi sekitar **81%**. Fitur paling berpengaruh dalam prediksi keselamatan adalah **Jenis Kelamin (Sex)** dan **Kelas Penumpang (Pclass)**. Visualisasi pohon keputusan menunjukkan bahwa prioritas keselamatan diberikan kepada wanita dan anak-anak dari kelas penumpang yang lebih tinggi.

## 🛠️ Teknologi yang Digunakan
* Python
* Pandas & Numpy
* Scikit-Learn
* Matplotlib & Seaborn

---
**Dibuat oleh:** Reiksa Azra Octavian  
**NIM:** 231011401754
