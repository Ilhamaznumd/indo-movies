---

# 🇮🇩 Indonesian Movies Exploratory Data Analysis

📂 **Project Description**  
This project aims to conduct *Exploratory Data Analysis (EDA)* on a dataset of over 1200 Indonesian films. This analysis helps understand film production trends, popular genres, user ratings, and many other interesting aspects.

---

## 📊 Dataset Information
The dataset used is taken from https://www.kaggle.com/datasets/dionisiusdh/imdb-indonesian-movies/data. This dataset has 11 main columns:
- `title`
- `year`
- `description`
- `genre`
- `rating`
- `users_rating`
- `votes`
- `languages`
- `directors`
- `actors`
- `runtime`

---

## 🔧 Preprocessing
Sebelum EDA dilakukan, beberapa langkah pembersihan data telah dilakukan:
- Menghapus duplikat data.
- Mengabaikan baris dengan missing value pada visualisasi tertentu.
- Membentuk kategori grup tahun.
- Memetakan rating usia.
- Membersihkan kolom aktor dari NaN untuk analisis aktor terbanyak.

---

## 📈 Exploratory Data Analysis
Analisis yang dilakukan meliputi:

- **Distribusi Film Berdasarkan Tahun**  
  ➔ Melihat tren produksi film per dekade.

- **Distribusi Genre Film**  
  ➔ Menganalisis genre film apa yang paling banyak diproduksi.

- **Distribusi Rating Pengguna**  
  ➔ Menganalisis persebaran skor yang diberikan pengguna.

- **Distribusi Rating Usia**  
  ➔ Mengetahui segmentasi umur target film.

- **Sutradara Paling Produktif**  
  ➔ Siapa saja yang paling banyak memproduksi film.

- **Aktor/Aktris Paling Produktif**  
  ➔ Siapa saja yang paling banyak membintangi film.

- **Rata-rata Rating per Genre**  
  ➔ Melihat genre mana yang mendapatkan rating rata-rata tertinggi.

- **Distribusi Rating dari Penonton Berdasarkan Tahun**  
  ➔ Melihat tren rating film dari penonton per tahun.

- **Distribusi Film Berdasarkan Kategori Runtime**  
  ➔ Menganalisis kategori seberapa panjang durasi film yang paling banyak diproduksi.

- **Wordcloud Deskripsi**  
  ➔ Visualisasi genre yang paling sering muncul.

---

## 📝 Important Notes
- Baris dengan nilai kosong pada kolom penting (seperti `description`, `genre`, `rating`, `directors`, `runtime`) **diabaikan** saat visualisasi untuk menjaga akurasi analisis.
- Interpretasi chart mempertimbangkan potensi bias akibat missing data.

---

## 🎯 Conclusions
- Produksi film Indonesia meningkat drastis setelah tahun 2000.
- Drama, Komedi, dan Romance menjadi genre paling dominan.
- Sebagian besar film mendapatkan rating pengguna 5–8.

---
