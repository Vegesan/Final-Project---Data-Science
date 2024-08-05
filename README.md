# Data-Preprocessing Stage-1
A. Handle Missing Values
* Identifikasi Missing Values: Langkah pertama adalah mengidentifikasi kolom dan baris mana yang mengandung nilai hilang.
* Mengisi (Imputation): Mengganti nilai yang hilang dengan rata-rata, median, modus, atau menggunakan metode yang lebih kompleks seperti K-Nearest Neighbors (KNN) imputation.
B. Handle Duplicated Data
* Identifikasi Duplikasi: Mencari data duplikat dalam dataset yang bisa mengganggu analisis.
* Menghapus Duplikasi: Menghapus baris duplikat dengan menggunakan metode seperti drop_duplicates di pandas untuk memastikan bahwa setiap entri dalam dataset adalah unik.
C. Handle Outliers
* Identifikasi Outliers: Menggunakan metode statistik seperti Z-score atau Interquartile Range (IQR) untuk mendeteksi nilai ekstrem.
* Mengatasi Outliers:
* Menghapus: Menghapus outliers jika mereka dianggap sebagai noise yang tidak relevan.
D. Feature Transformation
* Normalisasi: Mengubah skala fitur ke dalam rentang tertentu, seperti 0 ke 1, menggunakan metode seperti Min-Max Scaling.
* Standarisasi: Menjadikan fitur memiliki rata-rata 0 dan deviasi standar 1 dengan menggunakan Z-score standarisasi.
E. Feature Encoding
* Encoding Kategorikal: Mengonversi data kategorikal menjadi format numerik menggunakan:
* Label Encoding: Mengonversi kategori menjadi nilai integer.
F. Handle Class Imbalance
* Oversampling: Menambahkan salinan sampel minoritas hingga seimbang.
* Synthetic Data Generation: Menggunakan metode seperti SMOTE (Synthetic Minority Over-sampling Technique) untuk membuat sampel minoritas sintetis.
G. Feature Selection
* Menghapus Fitur yang Tidak Relevan: Menggunakan metode statistik atau algoritma machine learning seperti Random Forest atau LASSO untuk mengidentifikasi dan menghapus fitur yang tidak penting.
* Redundansi: Menggunakan korelasi atau analisis komponen utama (PCA) untuk mengidentifikasi dan menghapus fitur yang redundan.
H. Feature Extraction
* Pembuatan Fitur Baru: Menggabungkan atau mengubah fitur yang ada untuk membuat fitur baru yang dapat meningkatkan model, misalnya membuat fitur interaksi atau transformasi polinomial.
* Penggunaan Teknik Dimensionality Reduction: Seperti PCA atau t-SNE untuk mengurangi dimensi data sambil mempertahankan informasi penting.

Proses pra-pemrosesan data ini bertujuan untuk membersihkan dan menyiapkan data agar lebih sesuai untuk analisis atau penerapan model machine learning, sehingga dapat meningkatkan akurasi dan efektivitas model.
