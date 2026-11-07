# UTS Deep Learning — Kelas B

**Nama:** Ivander Risq Azmi  
**NIM:** 202432057  
**Kelas:** B  
**Mata kuliah:** Deep Learning  
**Topik:** Implementasi LSTM untuk Analisis Sentimen Twitter US Airline

## Deskripsi proyek

Proyek ini menerapkan algoritma **Long Short-Term Memory (LSTM)** untuk mengklasifikasikan tweet terkait pelayanan maskapai penerbangan ke dalam tiga kelas sentimen: **Negative**, **Neutral**, dan **Positive**.

## Dataset

Dataset yang digunakan adalah **Twitter US Airline Sentiment** dari Kaggle:

https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

File `Tweets.csv` yang disertakan dalam repositori memiliki 14.485 baris dan 15 kolom. Kolom teks yang digunakan adalah `text`, sedangkan target klasifikasi adalah `airline_sentiment`.

Notebook juga mendukung `database.sqlite` sebagai sumber data lokal. Jika file SQLite tersedia di direktori kerja, notebook membacanya terlebih dahulu; jika tidak, notebook menggunakan `Tweets.csv` yang tersedia di repositori ini.

## Isi repositori

- `UTS_DEEPL_B_202432057_IvanderRisqAzmi.ipynb` — notebook praktikum yang mencakup eksplorasi dataset, preprocessing, pembentukan vocabulary, arsitektur LSTM, training, evaluasi, dan visualisasi.
- `Tweets.csv` — dataset Twitter US Airline Sentiment.
- `README.md` — informasi proyek dan petunjuk penggunaan.

## Cara menjalankan

1. Buka file notebook menggunakan Google Colab atau Jupyter Notebook.
2. Unduh file `Tweets.csv` dari repositori ini dan letakkan pada direktori kerja notebook. Pada Google Colab, unggah file tersebut ke panel Files.
3. Jalankan seluruh cell secara berurutan (**Run all**).
4. Periksa output preprocessing, proses training, classification report, dan grafik evaluasi.

Notebook menggunakan Python, Pandas, NumPy, Matplotlib, scikit-learn, dan PyTorch. Pastikan dependensi tersedia pada runtime yang digunakan.

## Hasil eksperimen

Pada pengujian dengan 2.897 tweet, hasil evaluasi model yang tercatat dalam praktikum adalah:

- **Accuracy:** 71,45%
- **Macro F1-score:** 68,42%
- **Weighted F1-score:** 72,91%

Hasil tersebut merupakan hasil eksekusi praktikum yang digunakan dalam laporan UTS.

## Tujuan repositori

Repositori ini disediakan untuk pengumpulan dan pemeriksaan program Ujian Tengah Semester mata kuliah Deep Learning Kelas B.
