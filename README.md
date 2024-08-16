[ Project Klasifikasi Gambar Dicoding ]
Proyek ini adalah tugas individu yang saya kerjakan sebagai syarat kelulusan untuk salah satu kursus di Dicoding. Tujuan dari proyek ini adalah untuk membangun dan mengevaluasi model deep learning untuk klasifikasi gambar yang terdiri dari tiga kategori: batu, gunting, dan kertas.

[ Dataset dan Pembagian Data ]
Dataset yang digunakan dalam proyek ini disediakan oleh pihak Dicoding dan terdiri dari total 2188 gambar. Gambar-gambar tersebut dibagi menjadi dua set: 1312 gambar untuk train set dan 876 gambar untuk test set. Pembagian ini dirancang untuk memastikan model dapat dilatih dengan baik dan dievaluasi dengan akurat.

[ Desain dan Pengembangan Model ]
Saya membangun model deep learning dengan arsitektur sebagai berikut:
- 4 Lapisan Convolutional: Setiap lapisan convolutional dilengkapi dengan lapisan max pooling untuk mengurangi dimensi data dan menangkap fitur penting dari gambar.
- 1 Lapisan Flatten: Digunakan untuk meratakan output dari lapisan convolutional menjadi satu dimensi, sehingga dapat dihubungkan dengan lapisan dense.
- 2 Lapisan Dense: Lapisan ini berfungsi untuk melakukan klasifikasi berdasarkan fitur yang diekstraksi oleh lapisan-lapisan sebelumnya.
Model ini dikompilasi menggunakan optimizer Adam dengan learning rate sebesar 0.001. Saya melatih model menggunakan 15 epoch dengan 41 step per epoch.

[ Evaluasi Model ]
Hasil evaluasi menunjukkan bahwa model mencapai akurasi 96.95% pada data train dengan loss 9.98%. Meskipun akurasi yang diperoleh sudah memuaskan, nilai loss yang masih berada di angka 9.98% menunjukkan bahwa masih ada ruang untuk perbaikan. Oleh karena itu, fine-tuning hyperparameter dapat dilakukan untuk lebih meningkatkan kualitas model.

[ Pembelajaran dan Kesimpulan ]
Melalui proyek ini, saya memperoleh banyak pengetahuan tentang bagaimana merancang sebuah model deep learning, termasuk pemilihan arsitektur yang tepat dan teknik evaluasi model. Project ini juga memperkuat pemahaman saya tentang penerapan teknik-teknik deep learning dalam klasifikasi gambar.
