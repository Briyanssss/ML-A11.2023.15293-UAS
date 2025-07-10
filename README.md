# Proyek Machine Learning: Prediksi Viralitas Video TikTok

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun model klasifikasi yang dapat memprediksi potensi viralitas sebuah video di TikTok. Model ini menggunakan arsitektur hibrida yang menggabungkan fitur interaksi pengguna (jumlah tayangan, suka, dll.) dengan fitur teks yang diekstrak dari transkripsi video menggunakan TF-IDF dan Naive Bayes. Model akhir menggunakan Random Forest yang dioptimalkan dengan GridSearchCV dan SMOTE.

---

## Struktur Folder

Tentu, pertanyaan yang sangat bagus.

File README.md adalah halaman depan atau "papan pengumuman" untuk repositori GitHub Anda. Ini adalah file pertama yang akan dilihat oleh siapa pun (termasuk dosen Anda) saat mereka mengunjungi link repositori Anda.

Tujuannya adalah untuk memberikan gambaran umum yang jelas dan ringkas tentang proyek Anda.

Secara spesifik, file README.md biasanya berisi:

Judul Proyek: Nama proyek Anda yang jelas dan deskriptif.

Deskripsi Singkat: Penjelasan satu atau dua paragraf tentang apa yang dilakukan proyek ini, masalah yang dipecahkan, dan metodologi yang digunakan.

Cara Menjalankan Proyek (How to Run): Ini bagian yang sangat penting. Anda perlu memberikan instruksi tentang:

Bagaimana cara menyiapkan lingkungan (misalnya, library apa saja yang perlu diinstal).

Bagaimana cara menjalankan notebook.

Struktur Folder: Penjelasan singkat tentang bagaimana Anda menata file (misalnya, "Dataset berada di dalam folder /data").

Hasil (Opsional tapi bagus): Anda bisa menambahkan ringkasan singkat tentang hasil yang Anda dapatkan, seperti akurasi model.

File ini menggunakan format Markdown (.md), yang merupakan cara sederhana untuk memformat teks (misalnya, menggunakan # untuk judul, \* untuk daftar, dll.).

Contoh Template README.md untuk Proyek Anda
Anda bisa membuat file baru bernama README.md di dalam folder proyek Anda dan menyalin teks di bawah ini sebagai template awal.

Markdown

# Proyek Machine Learning: Prediksi Viralitas Video TikTok

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun model klasifikasi yang dapat memprediksi potensi viralitas sebuah video di TikTok. Model ini menggunakan arsitektur hibrida yang menggabungkan fitur interaksi pengguna (jumlah tayangan, suka, dll.) dengan fitur teks yang diekstrak dari transkripsi video menggunakan TF-IDF dan Naive Bayes. Model akhir menggunakan Random Forest yang dioptimalkan dengan GridSearchCV dan SMOTE.

---

## Struktur Folder

.
├── data/
│ └── tiktok_dataset.csv
├── ML-NIM-UAS.ipynb
└── README.md

---

## Cara Menjalankan

1.  **Clone Repositori**

    ```bash
   git clone https://github.com/Briyanssss/ML-A11.2023.15293-UAS.git
   cd ML-A11.2023.15293-UAS
    ```

2.  **Instal Library yang Dibutuhkan**
    Pastikan Anda memiliki Python terinstal. Kemudian, jalankan perintah berikut di terminal:

    ```bash
    pip install pandas numpy matplotlib seaborn wordcloud nltk scikit-learn imbalanced-learn jupyter
    ```

3.  **Jalankan Jupyter Notebook**
    Buka dan jalankan sel-sel kode di dalam file `ML-A11.2023.15293-UAS.ipynb`.

---

## Author

- **Nama**:Briyan Nicho Saputra
- **NIM**: A11.2023.15293
