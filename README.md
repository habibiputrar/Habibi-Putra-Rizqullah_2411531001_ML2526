# Praktikum Machine Learning 2025/2026

Kumpulan notebook praktikum dan tugas **Machine Learning**, mulai dari regresi dan klasifikasi hingga reduksi dimensi serta ensemble learning. Repository memuat **16 notebook** yang dikelompokkan dalam **Praktikum 1–10** dan **Mini Project**, beserta dataset CSV untuk beberapa latihan.

| Identitas | Keterangan |
| --- | --- |
| Nama | Habibi Putra Rizqullah |
| NIM | 2411531001 |
| Mata Kuliah | Machine Learning |
| Periode | 2025/2026 |
| Repository | [Habibi-Putra-Rizqullah_2411531001_ML2526](https://github.com/habibiputrar/Habibi-Putra-Rizqullah_2411531001_ML2526) |

## Daftar Praktikum

| Bagian | Materi dan Eksperimen | Notebook |
| --- | --- | --- |
| 1 | Regresi linear sederhana dan berganda, prediksi harga, serta evaluasi error. | [Simple Linear Regression](Praktikum1/SimpleLinearRegression.ipynb) · [Multiple Linear Regression](Praktikum1/MultiLinearRegression.ipynb) |
| 2 | Gaussian dan Bernoulli Naive Bayes, pengolahan fitur, serta evaluasi klasifikasi. | [Gaussian Naive Bayes](Praktikum2/GaussianNaiveBayes.ipynb) · [Bernoulli Naive Bayes](Praktikum2/BernoulliNaiveBayes.ipynb) · [Tugas Naive Bayes](Praktikum2/TugasNaiveBayes.ipynb) |
| 3 | Logistic Regression, confusion matrix, classification report, serta kurva ROC dan AUC. | [Logistic Regression](Praktikum3/LogisticRegression.ipynb) · [Tugas Logistic Regression](Praktikum3/TugasLogisticRegression.ipynb) |
| 4 | Perbandingan Linear Regression, Ridge, dan Lasso untuk mempelajari regularisasi. | [Regularization](Praktikum4/Regularization.ipynb) |
| 5 | Pembagian data, K-Fold dan Stratified K-Fold, serta perbandingan model melalui cross-validation. | [Validation Techniques](Praktikum5/ValidationTechniques.ipynb) · [Tugas Cross Validation](Praktikum5/TugasCrossValidation.ipynb) |
| 6 | K-Nearest Neighbors dan Support Vector Machine, visualisasi decision boundary, serta eksperimen parameter. | [KNN dan SVM](Praktikum6/KNN_%26_SVM_%28Decision_Boundary_Visualization%29.ipynb) |
| 7 | Decision Tree, pengaruh kedalaman pohon, overfitting, serta perbandingan dengan model lain. | [Decision Tree](Praktikum7/Decision_Tree_%28Overfitting_%26_Tree_Depth%29.ipynb) |
| 8 | Principal Component Analysis, covariance matrix, eigenvalue, explained variance, dan pemilihan jumlah komponen. | [Principal Component Analysis](Praktikum8/Principal_Component_Analysis_%28PCA%29.ipynb) |
| 9 | Integrasi PCA dengan Logistic Regression, KNN, SVM, dan Decision Tree; perbandingan hasil serta tuning parameter. | [Integrasi PCA dengan Model](Praktikum9/%20Integrasi_PCA_dengan_model.ipynb) |
| 10 | Random Forest, feature importance, seleksi fitur, serta perbandingan beberapa model sebelum dan sesudah PCA. | [Bagging dan Random Forest](Praktikum10/Bagging_%26_Random_Forest.ipynb) |
| Mini Project | AdaBoost, Gradient Boosting, soft voting, GridSearchCV, serta kombinasi PCA dan ensemble. | [Boosting dan Voting](Mini%20Project/Boosting_voting.ipynb) |

## Struktur Repository

```text
.
├── Praktikum1/       # Regresi linear
├── Praktikum2/       # Naive Bayes
├── Praktikum3/       # Logistic Regression
├── Praktikum4/       # Regularisasi
├── Praktikum5/       # Teknik validasi
├── Praktikum6/       # KNN dan SVM
├── Praktikum7/       # Decision Tree
├── Praktikum8/       # PCA
├── Praktikum9/       # Integrasi PCA dan model
├── Praktikum10/      # Random Forest dan perbandingan model
├── Mini Project/     # Boosting dan voting
└── README.md
```

Beberapa tugas individu berada dalam notebook praktikum yang sama. Baca judul bagian pada setiap notebook untuk menemukan eksperimen dan pembahasannya.

## Dataset

| Dataset | Lokasi / Cara Memuat | Penggunaan |
| --- | --- | --- |
| Data luas dan harga | Dibuat langsung di notebook regresi sederhana | Simple Linear Regression |
| California Housing | `fetch_california_housing()` dari scikit-learn | Multiple Linear Regression |
| Breast Cancer dengan fitur ringkas | [Praktikum2/Breast_cancer_data.csv](Praktikum2/Breast_cancer_data.csv) | Gaussian Naive Bayes dan tugasnya |
| Data cuaca kategorikal | Dibuat langsung pada notebook Bernoulli Naive Bayes | Klasifikasi dengan fitur biner |
| Diabetes | [Praktikum3/diabetes.csv](Praktikum3/diabetes.csv) | Logistic Regression |
| Breast Cancer bawaan scikit-learn | `load_breast_cancer()` | Tugas Logistic Regression |
| Advertising | [Praktikum4/Advertising.csv](Praktikum4/Advertising.csv) dan [Praktikum5/Advertising.csv](Praktikum5/Advertising.csv) | Regularisasi dan validasi regresi |
| Titanic | [train.csv](Praktikum5/train.csv), [test.csv](Praktikum5/test.csv), dan [gender_submission.csv](Praktikum5/gender_submission.csv) | Tugas Cross Validation |
| Breast Cancer dengan fitur lengkap | [Praktikum6/breast-cancer.csv](Praktikum6/breast-cancer.csv) | KNN, SVM, Decision Tree, PCA, Random Forest, dan Mini Project |

Sejumlah notebook membaca CSV melalui URL raw GitHub. California Housing juga dapat membutuhkan unduhan pada pemakaian pertama. Pastikan akses internet tersedia untuk sel yang mengambil data dari sumber tersebut.

## Teknologi

| Kebutuhan | Pustaka / Lingkungan |
| --- | --- |
| Pemrograman dan notebook | Python, Jupyter Notebook, Google Colab |
| Pengolahan data | pandas, NumPy |
| Visualisasi | Matplotlib, seaborn |
| Model, preprocessing, validasi, dan evaluasi | scikit-learn |
| Penyimpanan object pada latihan tertentu | pickle dari standard library Python |

## Menjalankan melalui Google Colab

1. Buka [Google Colab](https://colab.research.google.com/).
2. Pada pilihan membuka notebook, gunakan tab **GitHub** dan masukkan URL repository ini.
3. Pilih notebook yang ingin dipelajari, lalu gunakan runtime Python 3.
4. Periksa import pustaka dan lokasi dataset.
5. Jalankan sel secara berurutan, kemudian tinjau grafik, metrik, serta analisis hasil.

Untuk notebook yang membutuhkan pustaka tambahan, pasang pada sel terpisah:

```python
%pip install numpy pandas matplotlib seaborn scikit-learn
```

Membuka notebook melalui GitHub tidak otomatis menyalin seluruh file CSV ke runtime Colab. Pada `TugasCrossValidation.ipynb`, kode membaca `train.csv`, `test.csv`, dan `gender_submission.csv` dari `/content/drive/MyDrive/ML/Dataset/`. Hubungkan Google Drive dan tempatkan ketiga file pada folder tersebut, atau sesuaikan `BASE_PATH` dengan lokasi dataset yang digunakan.

## Menjalankan melalui Jupyter

Siapkan Python 3 dan Git, kemudian unduh repository:

```bash
git clone https://github.com/habibiputrar/Habibi-Putra-Rizqullah_2411531001_ML2526.git
cd Habibi-Putra-Rizqullah_2411531001_ML2526
```

Pasang dependensi dan jalankan Jupyter Notebook:

```bash
python -m pip install numpy pandas matplotlib seaborn scikit-learn notebook
jupyter notebook
```

Buka notebook yang dipilih dengan kernel Python 3. Untuk latihan yang memakai Google Drive, sesuaikan bagian `drive.mount()` dan path dataset dengan folder lokal. Pada tugas cross-validation, `BASE_PATH` dapat diarahkan ke folder `Praktikum5/` pada salinan repository.

Panduan pemasangan dan menjalankan Jupyter tersedia pada [dokumentasi Jupyter](https://jupyter.org/install).

## Hasil Eksperimen

Notebook menyertakan output tersimpan berupa prediksi, grafik, confusion matrix, metrik evaluasi, dan tabel perbandingan sesuai latihan masing-masing.

- **Regresi:** penilaian error prediksi, termasuk Mean Squared Error (MSE).
- **Klasifikasi:** accuracy, precision, recall, F1-score, confusion matrix, dan ROC-AUC sesuai notebook.
- **Validasi:** perbandingan hasil pembagian data dan cross-validation.
- **PCA:** explained variance, jumlah komponen, serta pengaruh reduksi dimensi terhadap model.
- **Ensemble:** perbandingan model dasar, boosting, voting, dan hasil tuning.

Interpretasikan hasil berdasarkan dataset dan konfigurasi pada notebook terkait. Nilai metrik serta waktu eksekusi dapat berbeda ketika parameter, pembagian data, atau versi pustaka berubah.
