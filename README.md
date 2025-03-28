# Klasifikasi Gambar CIFAR-10  

### Proyek ini bertujuan untuk mengklasifikasikan gambar menggunakan dataset CIFAR-10. Dataset: https://www.cs.toronto.edu/~kriz/cifar.html

### Dataset Dataset CIFAR-10 terdiri dari 60.000 gambar berwarna yang terbagi dalam 10 kelas. Berikut adalah kelas-kelas dalam dataset: 
 ['pesawat', 'mobil', 'burung', 'kucing', 'rusa', 'anjing', 'katak', 'kuda', 'kapal', 'truk']

## Bagan Proyek:
- tfjs_model
- tflite
- saved_model
- CIFAR_10_Klasifikasi_Gambar_Submission_Akhir.ipynb
- cifar_10_klasifikasi_gambar_submission_akhir.py
- README.md
- requirements.txt
 
## Proyek ini mencakup langkah-langkah berikut: 
1. **Persiapan Data**: Memuat dan memproses dataset CIFAR-10.
2. **Augmentasi Data**: Menerapkan augmentasi untuk meningkatkan variasi data pelatihan.
3. **Modeling**: Membangun model CNN menggunakan Keras.
4. **Pelatihan Model**: Melatih model dengan data pelatihan dan validasi.
5. **Evaluasi Model**: Mengevaluasi akurasi model pada data pelatihan dan pengujian.
6. **Visualisasi**: Menampilkan grafik akurasi dan loss selama pelatihan.
7. **Konversi Model**: Menyimpan model dalam format SavedModel, TF-Lite, dan TFJS.

## Cara Menjalankan 
1. Pastikan menjalankan semua dependensi library (ada di requirements.txt). <br>

Pastikan untuk menginstall package yang dibutuhkan menggunakan:
```
pip install tensorflow tensorflowjs matplotlib numpy scikit-learn
```
