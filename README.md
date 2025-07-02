1. Pencarian Jurnal Referensi
Melakukan literature review untuk memahami perkembangan terkini mengenai prediksi penyakit jantung dengan Machine Learning.

Mencari jurnal di database seperti Google Scholar, IEEE, Elsevier, atau Sinta (untuk jurnal terakreditasi di Indonesia).

Fokus pada penelitian yang menggunakan algoritma seperti Decision Tree, SVM, KNN, Random Forest, XGBoost, atau Neural Network.

Menyusun ringkasan state-of-the-art dari beberapa jurnal sebagai dasar perbandingan.

2. Pengambilan Dataset
Mencari dataset yang relevan di platform terbuka seperti Kaggle.

Pada penelitian ini digunakan dataset “UCI Heart Disease Data” yang sudah menjadi benchmark standar untuk prediksi penyakit jantung.

Dataset diunduh dalam format CSV, kemudian dianalisis atributnya (13 fitur input + 1 target).

3. Exploratory Data Analysis (EDA)
Melakukan analisis awal data:

Distribusi fitur numerik (age, chol, trestbps, thalach, oldpeak).

Distribusi fitur kategorikal (sex, cp, fbs, restecg, exang, slope, ca, thal).

Membuat visualisasi (histogram, barplot, pie chart, heatmap korelasi).

Mengidentifikasi fitur yang paling berkorelasi dengan target (misalnya cp, thalach, exang).

4. Preprocessing Data
Pembersihan data: Mengecek missing values dan outliers.

Encoding data kategorikal: karena dataset sudah dalam bentuk numerik ordinal, tidak perlu one-hot encoding.

Normalisasi data: Menggunakan StandardScaler untuk fitur numerik agar mean=0 dan std=1.

Split data: Membagi data ke train dan test set menggunakan stratified split supaya distribusi target tetap proporsional.

5. Coding di Google Colab
Mengimplementasikan coding dengan Python dan library pandas, numpy, matplotlib, seaborn, dan scikit-learn.

Langkah-langkah di notebook:

Load dataset dengan pandas.

EDA & visualisasi data.

Preprocessing: scaling & split data.

Modeling:

Decision Tree

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Evaluasi model menggunakan accuracy, precision, recall, F1-score, dan confusion matrix.

Visualisasi decision tree & feature importance.

6. Evaluasi & Perbandingan Model
Membandingkan performa ketiga algoritma berdasarkan metrik evaluasi.

Decision Tree dalam penelitian ini terbukti memiliki akurasi tertinggi (91.80%).

7. Penyusunan Laporan Penelitian
Membuat laporan dengan struktur:

Pendahuluan: latar belakang, rumusan masalah, tujuan.

Tinjauan Pustaka: ulasan jurnal referensi.

Metodologi: menjelaskan dataset, EDA, preprocessing, algoritma, dan flow penelitian.

Hasil & Pembahasan: memaparkan performa model dan interpretasi hasil.

Kesimpulan & Rekomendasi: hasil akhir, insight, serta saran pengembangan.

Menambahkan lampiran seperti grafik distribusi, heatmap, decision tree diagram, confusion matrix, hingga kode penting.
