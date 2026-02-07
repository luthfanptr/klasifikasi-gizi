# Perbandingan Kinerja Algoritma XGBoost, Random Forest, dan K-Nearest Neighbors dalam Klasifikasi Pola Nutrisi Berdasarkan Data Gizi Makanan

## Deskripsi Proyek
Proyek ini bertujuan untuk **membandingkan kinerja tiga algoritma machine learning**, yaitu **XGBoost**, **Random Forest**, dan **K-Nearest Neighbor (KNN)** dalam melakukan **klasifikasi pola nutrisi** berdasarkan **data gizi makanan**.

Studi ini berfokus pada bagaimana perbedaan karakteristik algoritma (tree-based ensemble dan distance-based) memengaruhi performa klasifikasi, baik dari sisi akurasi maupun metrik evaluasi lainnya.

Proyek ini disusun sebagai bagian dari **proyek UAS mata kuliah Artificial Intelligence** yang bertujuan untuk memahami:
- Mengolah dan mempersiapkan dataset nutrisi makanan untuk analisis machine learning
- Mengembangkan model klasifikasi untuk mengidentifikasi pola nutrisi makanan
- Membandingkan performa beberapa algoritma machine learning
- Mengoptimalkan model untuk mendapatkan akurasi terbaik

---

## Dataset
Dataset yang digunakan merupakan **data sekunder** yang diperoleh dari **Kaggle**. Dataset ini merupakan hasil **web scraping** dari situs **nilaigizi.com**, yang berisi informasi nilai gizi dari berbagai produk makanan dan minuman yang beredar di Indonesia.

Dataset ini mencakup berbagai atribut kandungan nutrisi yang digunakan sebagai fitur dalam proses klasifikasi pola nutrisi.

Tahapan umum yang dilakukan pada dataset meliputi:
- Pembersihan data (*handling missing value*)
- Pemilihan fitur nutrisi yang relevan
- Normalisasi / setting threshold gizi dalam batas wajar

## Cara Menjalankan Proyek
1. Membuat virtual environment
```bash
python3 -m venv venv
source venv\bin\activate  # linux/wsl
```

2. Instalasi dependensi
```bash
pip install -r requirements.txt
```

3. Ubah kernel notebook di VS Code menjadi `venv`, supaya seluruh dependensi sesuai dengan `requirements.txt`.

4. Run cell code satu per satu atau dengan Run All
