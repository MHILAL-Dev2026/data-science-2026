# data-science-2026
Perkenalkan nama saya Muhammad Hilal ADM yang sedang menjalani perkuliahan aktif di Universitas Siber Asia. Tujuan saya untuk belajar data science adalah karena perannya yang krusial dalam mengolah data menjadi informasi yang bernilai bagi pengambilan keputusan. Saya melihat bahwa kemampuan analisis data menjadi kebutuhan utama di berbagai sektor industri yang semakin berbasis teknologi. 



**Nama: Muhammad Hilal ADM** <br>
**NIM: 250401020122** <br>
**Kelas: IF 405** <br>
**Program Studi: PJJ Informatika**


# Deskripsi Repositori
Repo ini berisikan kumpulan tugas hands on modul dari pertemuan 1 - 13 yang mempelajari pengenalan data science, strukture data pythonn dasar, data cleaning, analisis data, visualisasi data, data preprocessing, dan pengantar machine learning, algoritma klasifikasi, asosiasi data, pengantar deep learning, dan NLP dasar. Kumpulan tugas ini didokumentasikan untuk penilaian Ujian Tengah Semester (UTS) dan Ujian Akhir Semester (UAS)


## Daftar Pertemuan beserta Link Notebook

1. Pertemuan 1: Pengenalan Data Science & Kerangka CRISP-DM  [Notebook P1](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan1_MuhammadHilalADM_250401020122.ipynb) 
2. Pertemuan 2: Struktur Data Python Dasar, NumPy & Pandas  [Notebook P2](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan2_MuhammadHilalADM_250401020122.ipynb) 
3. Pertemuan 3: Data Cleaning: Missing Values, Outlier & Ekstraksi Data  [Notebook P3](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan3_MuhammadHilalADM_250401020122.ipynb) 
4. Pertemuan 4: Statistika Deskriptif & Analisis Data Univariat/Bivariat  [Notebook P4](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan4_MuhammadHilalADM_250401020122.ipynb) 
5. Pertemuan 5: Visualisasi Data & Dashboard Analisis Statis  [Notebook P5](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan5_MuhammadHilalADM_250401020122.ipynb) 
6. Pertemuan 6: Data Preprocessing Pipeline & Dataset Titanic [Notebook P6](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan6_MuhammadHilalADM_250401020122.ipynb) 
7. Pertemuan 7: Pengantar Machine Learning: Regresi Linear  [Notebook P7](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan7_MuhammadHilalADM_250401020122.ipynb)


8. Pertemuan 9: Algoritma Klasifikasi (Bagian 1): Logistic Regression, Decision Trees, Confusion Matrix, Accuracy, Precision, Recall, dan
F1-Score. [Notebook P9](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan9_MuhammadHilalADM_250401020122.ipynb)
9. Pertemuan 10: Algoritma Klasifikasi (Bagian 2): Metode Ensemble (Random Forest) dan penanganan Imbalanced Dataset. Termasuk
Tugas Kelompok Customer Churn Prediction. [Notebook P10](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan10_MuhammadHilalADM_250401020122.ipynb)
10. Pertemuan 11: Unsupervised Learning (Clustering): K-Means, Hierarchical Clustering, dan Metode Elbow untuk menentukan jumlah
cluster optimal. [Notebook P11](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan11_MuhammadHilalADM_250401020122.ipynb)
11. Pertemuan 12: Asosiasi Data & Sistem Rekomendasi Dasar: Algoritma Apriori (Market Basket Analysis) dan konsep
Cllaborative/Content-Based Filtering. [Notebook P12](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan12_MuhammadHilalADM_250401020122.ipynb)
12. Pertemuan 13: Pengantar Deep Learning & NLP Dasar: konsep dasar Artificial Neural Network, serta pemrosesan teks sederhana
dengan TF-IDF untuk analisis sentimen.[Notebook P13](https://github.com/MHILAL-Dev2026/data-science-2026/blob/main/Pertemuan13_MuhammadHilalADM_250401020122.ipynb)

Note: Pertemuan 9 ditambahkan informasi Confusion Matrix (dalam visualisasi heatmap) serta Accuracy, Precision, Recall, dan F1-Score.
Pertemuan 10 ditambahkan informasi Confusion Matrix (dalam visualisasi heatmap) serta Accuracy, Precision, Recall, F1-Score, dan Interpretasi singkat: metrik mana yang paling relevan untuk kasus tersebut dan mengapa, khususnya untuk dataset customer churn pada Pertemuan 10 yang cenderung imbalanced, di mana Accuracy saja bisa menyesatkan.

## Tech Stack yang Digunakan

* **Python & Google Colab**  Digunakan sebagai bahasa utama dan media pengerjaan seluruh *notebook* dari Pertemuan 1 s.d 13.
* **Pandas & NumPy**  Untuk kebutuhan *Data Cleaning* (mengatasi *missing values* & *outliers*) serta manipulasi data.
* **Matplotlib & Seaborn** Membantu dalam proses *Exploratory Data Analysis* (EDA) lewat grafik univariat dan bivariat.
* **Scikit-Learn** Diimplementasikan pada tahap akhir untuk membangun *pipeline* data dan pemodelan Regresi Linear.
* **imblearn** (Imbalanced-learn): Diperlukan untuk penanganan Imbalanced Dataset (seperti teknik SMOTE, Oversampling, atau Undersampling) pada kasus Customer Churn Prediction.
* **mlxtend** (Machine Learning extensions): Library khusus untuk menjalankan Algoritma Apriori dan mengekstrak Association Rules dalam Market Basket Analysis.
* **TensorFlow / Keras** (modul MLPClassifier di Scikit-Learn)): Digunakan sebagai pengantar Deep Learning dan pembuatan arsitektur Artificial Neural Network (ANN) dasar.


##  Panduan Menjalankan Notebook

Seluruh materi pembelajaran dalam repositori ini dirancang agar dapat dijalankan secara langsung melalui lingkungan *cloud* menggunakan Google Colab. Metode ini direkomendasikan karena Anda tidak perlu melakukan proses instalasi pustaka (*library*) apa pun di komputer pribadi.

Langkah-Langkah Menjalankan di Link Google Colab:

1. **Akses Google Colab:** Buka platform Google Colab melalui peramban (*browser*) Anda.
2. **Impor dari GitHub:** Pada menu yang muncul, pilih tab **GitHub**.
3. **Masukkan URL Repositori:** Masukkan tautan (*link*) repositori ini ke dalam kolom pencarian yang tersedia.
4. **Pilih File Notebook:** Setelah repositori terdeteksi, pilih file dengan format `.ipynb` yang sesuai dengan materi pertemuan yang ingin Anda pelajari atau eksekusi.



## Kesimpulan Umum Perjalanan Belajar (Pertemuan 1 - 7)

Pembelajaran dari pertemuan 1 sampai 7 telah memberikan dasar yang terstruktur mengenai alur kerja Data Science berdasarkan panduan CRISP-DM. Prosesnya dimulai dari penguasaan tools seperti Python, NumPy, dan Pandas untuk analisis statistik deskriptif. Melalui visualisasi univariat dan bivariat, pola sebaran data serta hubungan antar-variabel dapat terlihat dengan jelas. Pada tahap data cleaning dan preprocessing menggunakan dataset Titanic, fokus utamanya adalah menjaga kualitas data. Proses membersihkan data duplikat, mengisi nilai yang hilang (missing values), dan menyaring pencilan (outliers) dengan metode IQR membuktikan prinsip Garbage In, Garbage Out bahwa hasil akhir yang akurat sangat bergantung pada kebersihan data awal.

Rangkaian materi ini diakhiri dengan penerapan Machine Learning dasar menggunakan Regresi Linear untuk prediksi angka. Selain menggabungkan data yang sudah dibersihkan, tahap ini juga menekankan pentingnya memisahkan data (split dataset) secara disiplin untuk mencegah kebocoran data (data leakage). Tujuh pertemuan ini berhasil membangun fondasi teknis dan logika berpikir yang kuat untuk pengembangan model ke depannya.

## Kesimpulan Umum Perjalanan Belajar (Pertemuan 9 - 13)

Pembelajaran dari pertemuan 9 sampai 13 telah memperluas kapabilitas analitik menuju pemodelan Machine Learning yang lebih kompleks dan beragam. Prosesnya dimulai dengan pendalaman algoritma Klasifikasi (Supervised Learning), bergerak dari model dasar seperti Logistic Regression dan Decision Trees menuju metode Ensemble yang lebih tangguh yakni Random Forest. Pemahaman terhadap metrik evaluasi seperti Confusion Matrix, Precision, Recall, dan F1-Score menekankan pentingnya mengukur kinerja model secara kritis melampaui sekadar tingkat akurasi. Penerapan teknik penanganan imbalanced dataset pada kasus Customer Churn Prediction membuktikan bahwa solusi algoritmik harus disesuaikan dengan kondisi ketidakseimbangan data di dunia nyata agar model tidak bias dan menghasilkan keputusan bisnis yang valid.

Rangkaian materi ini kemudian berekspansi ke ranah Unsupervised Learning untuk menggali struktur dan pola tersembunyi pada data tanpa label. Melalui algoritma Clustering (K-Means, Hierarchical) yang dioptimasi dengan metode Elbow, serta asosiasi data menggunakan Apriori (Market Basket Analysis) untuk merancang Sistem Rekomendasi, pembelajaran beralih dari sekadar memprediksi kelas menjadi memahami perilaku dan keterkaitan data. Perjalanan ini dipuncaki dengan pengenalan terhadap arsitektur Artificial Neural Network (ANN) serta teknik Natural Language Processing (NLP) menggunakan TF-IDF untuk analisis sentimen teks. Lima pertemuan ini berhasil menjembatani kompetensi dari Machine Learning tradisional menuju fondasi awal pemrosesan kecerdasan buatan (Deep Learning) dan analisis data tidak terstruktur.
