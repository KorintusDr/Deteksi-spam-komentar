# Deteksi Komentar Spam dengan Naive Bayes

Proyek ini bertujuan untuk mengembangkan model deteksi otomatis komentar spam menggunakan algoritma Naive Bayes. Komentar spam adalah masalah umum di platform-platform online seperti YouTube, Twitter, dan forum-forum umum, yang dapat mengganggu pengalaman pengguna. Model yang dikembangkan akan memungkinkan platform untuk secara otomatis menyaring komentar-komentar yang tidak relevan atau mengganggu ini.


### Dataset

Proyek ini menggunakan dataset `Youtube01-Psy.csv`, yang berisi komentar-komentar dari video YouTube. Dataset ini terdiri dari dua kolom utama:
- `CONTENT`: Isi dari komentar.
- `CLASS`: Label yang menunjukkan apakah komentar tersebut "Bukan Spam" (0) atau "Spam" (1).


### Langkah-langkah Proyek:

1. **Explorasi Data**: 
Memuat dataset, membersihkan data, dan menganalisis distribusi kelas serta panjang teks komentar.
   
2. **Preprocessing**: 
Mengubah teks komentar menjadi representasi numerik menggunakan Count Vectorization.

3. **Pemodelan**: 
Melatih model Naive Bayes (BernoulliNB) untuk klasifikasi komentar. Melakukan optimisasi parameter menggunakan Grid Search untuk meningkatkan performa model.

4. **Evaluasi**: 
Mengevaluasi model menggunakan metrik seperti akurasi, confusion matrix, dan classification report untuk mengukur seberapa baik model dapat mengidentifikasi komentar spam.


### Persyaratan:

Untuk menjalankan proyek ini, pastikan komputer Anda memiliki:
- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn


### Penggunaan:

Untuk menggunakan proyek ini:
1. Pastikan semua persyaratan terpenuhi.
2. Jalankan script pada file Python yang disediakan (`main.ipynb`).
