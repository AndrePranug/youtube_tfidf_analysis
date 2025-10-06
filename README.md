# YouTube Comments TF-IDF Analysis

Notebook ini berisi proses **Text Mining** pada komentar YouTube berbahasa Indonesia menggunakan **TF-IDF (Term Frequency - Inverse Document Frequency)**.

## 🚀 Alur Proses
1. **Instalasi & Import Library**
   - `Sastrawi` untuk stemming bahasa Indonesia.
   - `nltk` untuk stopwords.
   - `scikit-learn` untuk TF-IDF.
   - `pandas`, `numpy`, `re` untuk data handling.

2. **Load Dataset**
   - Dataset berupa `youtube-comments.csv` yang berisi komentar YouTube.
   - Menampilkan info, head, tail, dan missing values.

3. **Preprocessing**
   - Lowercasing.
   - Menghapus URL dan mention (`@username`).
   - Menghapus stopword bahasa Indonesia.
   - Stemming dengan **Sastrawi**.

4. **Feature Extraction**
   - Menggunakan `TfidfVectorizer` untuk menghasilkan representasi numerik komentar.
   - Ekstraksi kata unik (feature names).
   - Hasil akhir berupa matriks TF-IDF dalam bentuk `DataFrame`.

## 📂 Struktur Project
