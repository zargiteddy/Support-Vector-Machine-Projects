Support Vector Machine (SVM) adalah salah satu metode machine learning yang bekerja dengan prinsip Structural Risk Minimization (SRM) yang termasuk dalam kategori supervised learning. Dalam prosesnya, metode SVM memiliki tujuan yaitu untuk menemukan hyperplane paling optimal yang yang berfungsi untuk memisahkan dua buah kelas. Tingkat akurasi pada model yang dihasilkan oleh proses klasifikasi dengan SVM sangat bergantung terhadap fungsi kernel dan parameter yang digunakan (Parapat, et al., 2018).
![image](https://github.com/zargiteddy/Support-Vector-Machine-Projects/assets/72479466/01894d01-0fd7-4274-a119-a0165e1f5d26)

(Parapat, et al., 2018)

Pada ilustrasi di atas, ada dua kelas yang dipisahkan oleh garis hyperplane yaitu kelas positif yang bernilai +1 (lingkaran kuning) dan kelas negatif yang bernilai -1 (kotak merah). Garis solid yang terdapat pada tengah-tengah kedua kelas adalah hyperplane terbaik, dan objek merah dan kuning yang berada dalam lingkaran hitam disebut dengan support vector.

Prinsip kerja algoritma Support Vector Machine pada dasarnya adalah suatu algoritma yang digunakan untuk klasifikasi data linear, sehingga dalam proses klasifikasi seringkali ditemukan kondisi dimana SVM tidak bekerja dengan baik dalam melakukan klasifikasi pada data non-linear. Masalah tersebut bisa diatasi dengan menggunakan kernel trick. Kernel trick digunakan untuk memetakan data non-linear berdimensi rendah ke dalam ruang dimensi yang lebih tinggi sehingga membuat data terpisah secara linear lalu dapat terbentuk hyperplane yang optimal. Proses klasifikasi dengan SVM dapat dilakukan dengan memilih salah satu di antara 4 kernel yang tersedia yaitu linear, polymonial, RBF, dan sigmoid (Husada & Paramita, 2021). Ilustrasi kernel trick dapat dilihat pada gambar di bawah ini:
![image](https://github.com/zargiteddy/Support-Vector-Machine-Projects/assets/72479466/93b92bf6-51d8-4b73-bf44-37cd835bded1)
Pemetaan Input Space Berdimensi Dua dengan Pemetaan ke Dimensi Tinggi (Rahutomo et al., 2018)

Daftar Pustaka:
1. Parapat, I. M., Muhammad Tanzil F., dan Sutrisno. (2018). Penerapan Metode Support Vector Machine (SVM) Pada Klasifikasi Penyimpangan Tumbuh Kembang Anak. Jurnal Pengembangan Teknologi Informasi dan Ilmu Komputer, 2(10), 3163-3169.
2. Husada, H. C. dan Adi S. P. Analisis Sentimen Pada Maskapai Penerbangan di Platform Twitter Menggunakan Algoritma Support Vector Machine (SVM). TEKNIKA: Jurnal Teknologi dan Informasi, 10(1), 18-26. DOI: 10.34148/teknika.v10i1.311.
3. Rahutomo, F., Pramana Y. S., dan Miftahul A. F. ( 2018).  Implementasi Twitter Sentiment Analysis Untuk Review Film Menggunakan Algoritma Support Vector Machine. Jurnal Informatika Polinema, 4(2), 93-100. DOI: 10.33795/jip.v4i2.152.

