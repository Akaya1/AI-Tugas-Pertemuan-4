### Nur Muhammad Fadilah - 20220801114
---
### Deskripsi
Proyek ini bertujuan untuk membangun sebuah model machine learning menggunakan algoritma Decision Tree untuk mengklasifikasikan jenis bunga Iris berdasarkan fitur-fitur spesifik yang terdapat pada dataset Iris. Dataset ini berisi tiga kelas bunga yang berbeda: Iris-setosa, Iris-versicolor, dan Iris-virginica, serta fitur seperti panjang dan lebar sepal, dan panjang serta lebar petal.

Proses ini meliputi pembersihan data, membangun model Decision Tree, menguji model menggunakan data uji, dan mengevaluasi performa model menggunakan metrik seperti akurasi, confusion matrix, dan classification report.
### Detail Dataset Iris
- Jumlah Data: 150 sampel
- Fitur (Features):
- Sepal length (Panjang Sepal) - dalam cm
- Sepal width (Lebar Sepal) - dalam cm
- Petal length (Panjang Petal) - dalam cm
- Petal width (Lebar Petal) - dalam cm
- Target (Label/Kelas):
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica
### Alur Singkat Proyek
- Memuat Dataset:
Dataset Iris diimpor menggunakan ```sklearn.datasets.load_iris()``` yang sudah memiliki data siap pakai untuk analisis.
- Pembagian Data:
Dataset dibagi menjadi data latih (training set) dan data uji (testing set) dengan proporsi 70% untuk latih dan 30% untuk uji menggunakan ```train_test_split```.
- Membangun Model:
Model Decision Tree Classifier dibangun menggunakan data latih untuk mempelajari hubungan antara fitur-fitur bunga dan kelas target.
- Prediksi dan Evaluasi:
Setelah model dilatih, ia digunakan untuk memprediksi kelas bunga pada data uji.
Evaluasi model dilakukan menggunakan akurasi, confusion matrix, dan classification report untuk menilai performa.
- Visualisasi:
Confusion matrix divisualisasikan dalam bentuk heatmap untuk memahami prediksi model secara visual.

### Hasil Analisis
- Akurasi Model: Model Decision Tree berhasil memprediksi data uji dengan akurasi 100%, yang berarti semua prediksi pada data uji benar.
- Classification Report: Precision, Recall, dan F1-Score untuk semua kelas adalah 1.00, yang menunjukkan bahwa model sangat baik dalam membedakan ketiga kelas bunga tersebut.
Analisis Potensi Overfitting:
- Meskipun akurasi yang tinggi sangat bagus, ada kemungkinan overfitting karena model terlalu cocok pada data latih. Ini bisa diperbaiki dengan menggunakan lebih banyak data atau teknik seperti cross-validation untuk mengevaluasi generalisasi model pada data yang lebih beragam.
