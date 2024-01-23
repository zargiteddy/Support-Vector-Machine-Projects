Support Vector Machine (SVM) adalah salah satu metode machine learning yang bekerja dengan prinsip Structural Risk Minimization (SRM) yang termasuk dalam kategori supervised learning. Dalam prosesnya, metode SVM memiliki tujuan yaitu untuk menemukan hyperplane paling optimal yang yang berfungsi untuk memisahkan dua buah kelas. Tingkat akurasi pada model yang dihasilkan oleh proses klasifikasi dengan SVM sangat bergantung terhadap fungsi kernel dan parameter yang digunakan (Parapat, et al., 2018).
![image](https://github.com/zargiteddy/Support-Vector-Machine-Projects/assets/72479466/01894d01-0fd7-4274-a119-a0165e1f5d26)
Pada ilustrasi Gambar 2.4, ada dua kelas yang dipisahkan oleh garis hyperplane yaitu kelas positif yang bernilai +1 (lingkaran kuning) dan kelas negatif yang bernilai -1 (kotak merah). Garis solid yang terdapat pada tengah-tengah kedua kelas adalah hyperplane terbaik, dan objek merah dan kuning yang berada dalam lingkaran hitam disebut dengan support vector.

Pada algoritma Support Vector Machine, data ke-i pada dataset diwakilkan dengan variabel xi, sementara kelas pada dataset diwakilkan dengan variabel yi. Data xi yang termasuk dalam kelas +1 dirumuskan dengan persamaan (1), sedangkan data xi yang termasuk dalam kelas -1 dirumuskan dengan persamaan (2) (Parapat et al., 2018).
- xi.w+b≥1,yi=1								        (1)
- xi.w+b≤1,yi=-1							        (2)
Keterangan:
- xi = data ke -i
- w = nilai bobot support vector yang tegak lurus dengan hyperplane
- b = nilai bias
- yi= kelas data ke-i

Berikut tahap – tahap perhitungan klasifikasi menggunakan SVM:

