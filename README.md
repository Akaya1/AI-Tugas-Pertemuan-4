- Nur Muhammad Fadilah - 20220801114
---
## Algoritma Decision Tree 
adalah salah satu algoritma supervised learning yang digunakan untuk tugas klasifikasi dan regresi. Algoritma ini bekerja dengan membangun model dalam bentuk pohon (tree) yang memetakan atribut atau fitur dari data ke label atau target tertentu.
Data yang sedang diolah adalah dataset Iris. Dataset ini berisi informasi tentang tiga jenis bunga Iris (Setosa, Versicolor, Virginica), serta beberapa fitur dari bunga tersebut yang digunakan untuk membedakan setiap jenisnya.
**1. Detail Dataset Iris:**
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
**2. Contoh Data :**
| Panjang Sepal (cm) | Lebar Sepal (cm) | Panjang Petal (cm) | Lebar Petal (cm) | Target      |
|---------------------|-------------------|---------------------|-------------------|-------------|
| 5.1                 | 3.5               | 1.4                 | 0.2               | Setosa      |
| 4.9                 | 3.0               | 1.4                 | 0.2               | Setosa      |
| 7.0                 | 3.2               | 4.7                 | 1.4               | Versicolor  |
| 6.4                 | 3.2               | 4.5                 | 1.5               | Versicolor  |
| 5.9                 | 3.0               | 5.1                 | 1.8               | Virginica   |
**3. Tujuan Pengolahan :**
Tujuan utama adalah klasifikasi—yaitu, menggunakan fitur-fitur bunga (panjang/lebar sepal dan petal) untuk memprediksi apakah bunga tersebut adalah Setosa, Versicolor, atau Virginica. Model seperti Decision Tree dilatih untuk belajar dari data latih dan kemudian diujikan pada data uji untuk memprediksi jenis bunga berdasarkan fitur-fiturnya.
**Keuntungan dan Kelemahan Decision Tree**
- **Keuntungan:**
  - Mudah Dipahami: Pohon keputusan mudah dipahami dan dijelaskan secara grafis.
  - Tidak Membutuhkan Preprocessing yang Rumit: Tidak memerlukan skala data atau normalisasi.
  - Dapat Menangani Data Kategoris dan Numerik.
- **Kelemahan:**
  - Rentan Terhadap Overfitting: Jika pohon terlalu dalam, itu bisa overfit.
  - Tidak Stabil: Perubahan kecil pada data dapat menghasilkan pohon yang sangat berbeda.
  - Bias terhadap fitur dominan: Fitur dengan lebih banyak kategori dapat mendominasi keputusan.
**Kesimpulan**
Penggunaan algoritma Decision Tree dalam analisis data Iris memberikan hasil yang sangat baik dengan akurasi yang sempurna, meskipun perlu diperhatikan potensi masalah overfitting. Model ini dapat berfungsi sebagai langkah awal yang baik dalam memahami konsep dasar pembelajaran mesin dan klasifikasi.
