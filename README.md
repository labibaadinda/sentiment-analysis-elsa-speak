# **📊 Analisis Sentimen Ulasan Aplikasi ELSA SPEAK**

## 🎯 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis sentimen pengguna **ELSA SPEAK**, sebuah aplikasi untuk melatih kemampuan berbicara dalam bahasa Inggris, berdasarkan ulasan dan feedback yang diberikan oleh pengguna di platform. Dengan menggunakan teknik analisis sentimen berbasis **pembelajaran mesin**, proyek ini mengidentifikasi perasaan **positif**, **negatif**, atau **netral** yang terkandung dalam ulasan pengguna mengenai pengalaman mereka dalam menggunakan aplikasi.

Model yang diterapkan dalam proyek ini menggunakan **Support Vector Machine (SVM)** untuk mengklasifikasikan sentimen dalam ulasan pengguna.

## 🚀 Tujuan Proyek
- Menganalisis sentimen yang terkandung dalam ulasan pengguna aplikasi ELSA SPEAK.
- Mengidentifikasi aspek **positif** dan **negatif** dari pengalaman pengguna.
- Mendapat insight dari ulasan pengguna.

## 📂 Struktur Proyek
```
sentiment-analysis-elsa-speak/       # Main project directory
    ├── PelatihanModel.ipynb         # Notebook untuk pelatihan dan evaluasi model analisis sentimen menggunakan SVM
    ├── requirements.txt             # File yang berisi daftar pustaka yang diperlukan untuk menjalankan proyek
    ├── reviews.csv                  # Dataset berisi ulasan pengguna aplikasi ELSA SPEAK yang didapat dari scraping data di ScrapingData.ipynb  
    ├── ScrapingData.ipynb           # Notebook untuk pengambilan data ulasan pengguna dari sumber eksternal (web scraping)
    └── README.md                    # Project documentation 
```

### 🔍 Penjelasan Struktur File:
- **PelatihanModel.ipynb**: Jupyter notebook untuk menerapkan teknik pembelajaran mesin dalam pelatihan model **SVM** untuk analisis sentimen, termasuk pembersihan data, tokenisasi, pelatihan model, dan evaluasi model.
- **requirements.txt**: File yang berisi daftar semua pustaka Python yang dibutuhkan untuk menjalankan proyek ini, seperti `pandas`, `scikit-learn`, `nltk`, dll.
- **reviews.csv**: File CSV yang berisi ulasan dari pengguna aplikasi ELSA SPEAK yang digunakan sebagai dataset untuk analisis sentimen.
- **ScrapingData.ipynb**: Jupyter notebook yang berisi kode untuk melakukan web scraping dan mengumpulkan data ulasan pengguna dari situs web playstore.

## 🛠️ Langkah-langkah dalam Proyek
1. **Pengumpulan Data**: Mengumpulkan ulasan dari pengguna ELSA SPEAK dari berbagai sumber, seperti aplikasi resmi dan platform lain yang relevan.
2. **Pembersihan Data**: Proses pembersihan data meliputi penghapusan karakter yang tidak relevan, stopwords, dan normalisasi teks.
3. **Tokenisasi**: Proses memecah teks ulasan menjadi kata-kata atau token yang lebih kecil agar dapat dianalisis lebih lanjut.
4. **Penerapan Model Pembelajaran Mesin (SVM)**: Model digunakan untuk melatih model klasifikasi sentimen berdasarkan data pelatihan.
5. **Evaluasi Model**: Model diuji dengan menggunakan metrik seperti **accuracy**, **precision**, **recall**, dan **F1-score** untuk memastikan performa yang optimal dalam mengklasifikasikan sentimen.
6. **Interpretasi Hasil**: Analisis sentimen dikelompokkan menjadi **positif**, **negatif**, dan **netral** untuk memberikan gambaran menyeluruh tentang feedback pengguna.
7. **Visualisasi Hasil**: Menggunakan grafik dan visualisasi untuk menunjukkan distribusi sentimen dan memberikan wawasan yang lebih mudah dipahami.

## ⚙️ Teknologi dan Tools
- **Python**: Bahasa pemrograman yang digunakan untuk mengimplementasikan analisis sentimen.
- **Pandas**: Untuk manipulasi data dan pembersihan dataset.
- **Scikit-learn**: Untuk implementasi model pembelajaran mesin (SVM).
- **NLTK / Sastrawi**: Untuk pembersihan data teks, tokenisasi, dan penghapusan stopwords.
- **Matplotlib / Seaborn**: Untuk visualisasi hasil analisis.

## 📚 Metodologi
- **Pembersihan Data**: Menghapus kata-kata yang tidak relevan (stopwords), menghapus karakter khusus, dan melakukan stemming atau lemmatization untuk mengurangi kata ke bentuk dasarnya.
- **Tokenisasi**: Mengubah teks menjadi token-token kata yang lebih kecil untuk mempermudah analisis.
- **Pembelajaran Mesin (SVM)**:
  - Menggunakan **SVM** untuk melatih model klasifikasi sentimen berdasarkan data pelatihan.
  - Evaluasi dilakukan dengan **cross-validation** dan pengukuran kinerja model menggunakan metrik evaluasi standar.

## 🏆 Hasil yang Diharapkan
- Identifikasi dan klasifikasi sentimen dalam ulasan pengguna aplikasi ELSA SPEAK.
- Penyajian analisis yang jelas mengenai tingkat kepuasan pengguna melalui analisis sentimen.


## 🖥️ Cara Menjalankan Proyek
1. **Persiapan Lingkungan**:
   - Install dependensi yang diperlukan dengan menjalankan `pip install -r requirements.txt` untuk menginstal semua pustaka Python yang diperlukan.
   
2. **Menjalankan Skrip**:
   - Jalankan skrip utama untuk pembersihan data dan pemodelan sentimen menggunakan SVM.
   ```bash
   jupyter notebook PelatihanModel.ipynb
   ```

3. **Hasil dan Visualisasi**:
   - Hasil analisis sentimen dapat ditemukan dalam file hasil atau output di visualisasi.

