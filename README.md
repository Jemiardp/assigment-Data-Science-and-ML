# assigment-Data-Science-and-ML
Uploaded assigment to GITHUB
Assigment 3

Pada proyek ini, saya telah melakukan dua tahap penting dalam rangka memahami faktor-faktor yang berkaitan dengan pemutusan hubungan kerja karyawan dan memprediksi pemutusan tersebut.

Tahap 1: Analisis Eksplorasi Data (EDA)
Dalam tahap ini, saya telah melakukan analisis eksplorasi data (EDA) terhadap variabel target, yaitu pemutusan hubungan kerja karyawan. EDA dilakukan untuk memahami hubungan antara variabel target dengan variabel-variabel lain yang mungkin mempengaruhinya. Hasil dari EDA adalah sebagai berikut:
1. Visualisasi Hubungan Termination dan Gender: Saya membuat visualisasi yang menggambarkan sebaran pemutusan hubungan berdasarkan gender karyawan. Ini membantu saya memahami apakah ada perbedaan signifikan dalam tingkat pemutusan berdasarkan jenis kelamin.
2. Analisis Termination berdasarkan Departemen: Saya membuat visualisasi yang memperlihatkan frekuensi pemutusan hubungan berdasarkan departemen. Hal ini membantu saya mengetahui apakah ada departemen tertentu yang lebih rentan terhadap pemutusan.
3. Visualisasi Alasan Pemutusan: Saya membuat grafik batang yang menggambarkan alasan pemutusan hubungan kerja yang paling umum. Ini membantu saya mengidentifikasi alasan utama yang menjadi penyebab pemutusan.
4. Distribusi Usia Karyawan yang Berhenti: Saya membuat histogram yang menunjukkan distribusi usia karyawan yang berhenti. Hal ini membantu saya memahami apakah usia memiliki pengaruh terhadap pemutusan hubungan kerja.
5. Korelasi Variabel Termination: Saya menghitung dan memvisualisasikan matriks korelasi antara variabel-variabel yang relevan dengan pemutusan hubungan kerja. Hal ini membantu saya mengidentifikasi korelasi yang signifikan antara variabel-variabel tersebut.

Insight dari tahap EDA adalah kita dapat melihat pola dan tren yang berkaitan dengan pemutusan hubungan kerja. Misalnya, kita bisa melihat apakah gender, departemen, alasan pemutusan, atau usia memiliki pengaruh signifikan pada keputusan pemutusan.

Tahap 2: Pemodelan Machine Learning
Setelah melakukan EDA, saya melanjutkan dengan tahap pemodelan Machine Learning untuk memprediksi pemutusan hubungan karyawan. Saya menggunakan berbagai algoritma Machine Learning seperti regresi logistik, decision tree, dan random forest untuk membangun model prediksi. Saya membagi dataset menjadi data pelatihan dan data pengujian, lalu mengukur kinerja model saya menggunakan metrik yang sesuai.

Hasil dari tahap pemodelan Machine Learning adalah model prediksi yang dapat digunakan untuk memprediksi kemungkinan pemutusan hubungan karyawan berdasarkan variabel-variabel yang relevan. Model ini dapat menjadi alat yang berguna dalam mengidentifikasi karyawan yang mungkin berisiko untuk diberhentikan.

Saya berharap bahwa hasil dari dua tahap ini dapat membantu perusahaan atau organisasi dalam mengelola dan mengurangi pemutusan hubungan karyawan, serta memahami faktor-faktor yang berkontribusi pada keputusan tersebut. Semua hasil pengerjaan proyek ini dapat diakses dan ditemukan di repositori GitHub saya.


Assigment 4
TASK 1
Pada tahap awal, saya melakukan tiga model evaluasi yang berbeda untuk memproyeksikan pelanggan bank yang tidak aktif. Model-model yang digunakan adalah Random Forest, K-Nearest Neighbors (KNN), dan Decision Tree. Setelah melatih dan menguji ketiga model tersebut, hasil evaluasi diperoleh seperti berikut:

1. **Random Forest:**
   - Akurasi: 86.16%
   - Model ini memberikan akurasi tertinggi di antara ketiga model yang diuji. Random Forest mampu mengidentifikasi pelanggan bank yang tidak aktif dengan sangat baik.

2. **K-Nearest Neighbors (KNN):**
   - Akurasi: 83.68%
   - Model KNN memberikan tingkat akurasi yang lebih rendah dibandingkan dengan Random Forest. Hal ini menunjukkan bahwa KNN kurang cocok untuk memproyeksikan pelanggan bank yang tidak aktif dalam dataset ini.

3. **Decision Tree:**
   - Akurasi: 85.28%
   - Model Decision Tree juga memberikan tingkat akurasi yang lebih rendah dibandingkan dengan Random Forest. Ini menunjukkan bahwa model Decision Tree juga tidak seefektif Random Forest dalam memproyeksikan pelanggan bank yang tidak aktif.

Dalam eksperimen ini, saya juga telah menggunakan metode optimasi model untuk meningkatkan akurasi. Namun, hasil eksperimen menunjukkan bahwa Random Forest tetap menjadi pilihan terbaik bahkan tanpa optimasi tambahan. Oleh karena itu, saya merekomendasikan penggunaan Random Forest sebagai model utama untuk memproyeksikan pelanggan bank yang tidak aktif dalam kasus ini.

Penting untuk dicatat bahwa hasil eksperimen dapat berubah tergantung pada dataset dan kasus penggunaan tertentu. Oleh karena itu, selalu penting untuk mempertimbangkan karakteristik data dan tujuan proyek sebelum memilih model yang paling sesuai.

TASK 2
Deskripsi hasil pengerjaan GitHub yang telah dilakukan:

1. **Peparation Data**: Pada tahap awal, persiapan data dilakukan untuk memastikan data siap digunakan dalam tahap pemodelan. Ini melibatkan beberapa langkah seperti import library yang dibutuhkan dan membaca dataset `Cluster S1.csv`.

2. **Pencarian Model Cluster Terbaik**: Selanjutnya, dilakukan pencarian model klaster terbaik. Metode yang digunakan adalah K-means Clustering, dan eksperimen ini dilakukan untuk mencari jumlah cluster terbaik yang memberikan hasil optimal.

3. **Proses Clustering**: Hasil dari eksperimen menunjukkan bahwa jumlah cluster terbaik adalah 15. Ini ditemukan dengan memperoleh nilai Silhouette Score sebesar 71.12%. Silhouette Score adalah metrik evaluasi yang digunakan untuk mengukur sejauh mana setiap data point cocok dengan klusternya dan seberapa baik kluster tersebut terpisah satu sama lain.

4. **Visualisasi Cluster**: Selain menemukan jumlah cluster terbaik, ada juga langkah untuk memvisualisasikan kluster yang dihasilkan. Ini akan membantu dalam pemahaman lebih lanjut tentang bagaimana data terkelompok.

Dalam kasus ini, eksperimen berhasil dengan baik dengan mendapatkan Silhouette Score yang sangat baik, yaitu 71.12. Hasil ini menunjukkan bahwa pengelompokan data ke dalam 15 kluster adalah pilihan terbaik dan kluster tersebut memiliki pemisahan yang baik satu sama lain. Kesalahan dalam kode telah dicek sebelum pengiriman.

Dengan demikian, tahapan pengerjaan di GitHub telah berhasil mencapai hasil yang sesuai dengan persyaratan yang diberikan, dengan Silhouette Score yang memenuhi standar penilaian.

TASK 3
Hasil pengerjaan proyek GitHub "Deep Learning for MNIST Handwritten Digit Classification using PyTorch" mencerminkan pengembangan alur kerja untuk mengatasi tugas klasifikasi digit tulisan tangan MNIST dengan menggunakan jaringan saraf maju sederhana tanpa jaringan saraf konvolusi (CNN). Berikut adalah deskripsi rinci tentang hasil pengerjaan proyek ini:

1. **Pemuatan Dataset MNIST**: Dataset MNIST telah berhasil dimuat menggunakan data loader PyTorch. Ini merupakan langkah penting dalam persiapan data untuk pelatihan model.

2. **Visualisasi Dataset MNIST**: Sejumlah sampel dari dataset MNIST telah divisualisasikan. Visualisasi ini membantu dalam pemahaman awal tentang data yang digunakan untuk pelatihan model.

3. **Perancangan Model Jaringan Saraf**: Sebuah jaringan saraf maju sederhana telah dirancang untuk tugas klasifikasi digit. Ini mencakup jumlah lapisan, ukuran setiap lapisan, dan fungsi aktivasi yang digunakan.

4. **Pengaturan Hiperparameter**: Hiperparameter seperti fungsi kerugian, optimizer, tingkat pembelajaran, dll., telah dikonfigurasi dan diatur sesuai kebutuhan. Pengaturan yang tepat dari hiperparameter adalah kunci untuk hasil yang baik.

5. **Pengembangan Loop Pelatihan**: Sebuah loop pelatihan telah dikembangkan untuk melatih model pada data latihan. Ini termasuk iterasi melalui dataset, perhitungan gradien, pembaruan bobot, dan pengukuran metrik selama pelatihan.

6. **Evaluasi Model**: Model telah dievaluasi menggunakan beberapa metrik kinerja, termasuk akurasi, matriks konfusi, presisi, recall, dan skor F1. Hasil evaluasi memberikan wawasan tentang kinerja model dalam mengklasifikasikan digit MNIST.

7. **Deskripsi dan Penjelasan Hasil**: Hasil akhir dari eksperimen ini telah dideskripsikan dan dijelaskan. Ini mencakup penjelasan tentang sejauh mana model mampu mengklasifikasikan digit tulisan tangan dengan benar, serta di mana model mungkin melakukan kesalahan.

Selain itu, proyek ini memberikan dasar yang kuat untuk eksperimen lebih lanjut. Untuk meningkatkan model, eksperimen lebih lanjut dapat dilakukan dengan mengubah hiperparameter, mengganti arsitektur jaringan, atau mengadopsi teknik yang lebih canggih seperti jaringan saraf konvolusi (CNN) untuk mencapai kinerja yang lebih baik dalam tugas klasifikasi gambar seperti MNIST. Proyek ini merupakan landasan yang baik untuk penelitian lanjutan dalam pengembangan model Deep Learning untuk klasifikasi digit tulisan tangan.




