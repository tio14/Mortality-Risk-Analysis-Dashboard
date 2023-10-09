# Mortality-Risk-Analysis-Dashboard

## Deskripsi 
Tingkat kematian di Indonesia diproyeksikan akan terus mengalami peningkatan semenjak tahun 2015. Salah satu cara yang dapat dilakukan untuk menurunkan angka tingkat kematian adalah dengan melakukan analisis penyebab kematian melalui data yang disediakan oleh BPJS. Beberapa hal yang dapat dijadikan asumsi terkait faktor penyebab kematian diantaranya: fasilitas kesehatan yang kurang memadai, diagnosa penyakit, dan profil dari peserta JKN-KIS. 

Asumsi faktor penyebab kematian yang pertama adalah fasilitas kesehatan yang kurang memadai di beberapa daerah. Fasilitas yang kurang memadai dapat ditandai dengan lokasi fasilitas kesehatan rujukan yang berbeda dengan fasilitas kesehatan tingkat pertama dan/atau kota domisili. Beberapa fasilitas kesehatan rujukan yang diberikan berada di provinsi yang berbeda. Perbedaan provinsi menunjukkan jarak yang cukup jauh. Walaupun kondisi pasien saat dirujuk mungkin tidak terlalu parah atau kritis, tetapi terdapat kemungkinan akan menjadi lebih parah dalam waktu tertentu saat pasien berusaha mencapai fasilitas kesehatan rujukan. 

Asumsi faktor penyebab kematian yang kedua adalah diagnosa penyakit. Diagnosa penyakit yang perlu menjadi perhatian adalah diagnosa penyakit yang berpeluang tinggi menyebabkan kematian. Hal ini dapat diperoleh dengan mencari proporsi hubungan antara masing-masing diagnosa penyakit dengan status pulang dari peserta.

Asumsi faktor penyebab kematian yang ketiga adalah profil dari peserta JKN-KIS yang berkaitan dengan kesehatan. Contoh dari data profil ini adalah nilai BMI (body mass index), usia dan jenis kelamin, serta faktor tempat tinggal. BMI dapat diperoleh dengan melakukan perhitungan pada data tinggi dan berat badan dari setiap peserta. Usia dan jenis kelamin yang memiliki risiko peluang yang lebih tinggi terhadap penyakit tertentu. Selain itu juga faktor lingkungan seperti tempat tinggal yang kurang sehat yang dapat diketahui melalui variabel kota/kabupaten. 

Dashboard yang dirancang akan menyajikan analisis lengkap mengenai faktor-faktor yang memungkinkan di atas sehingga dapat memudahkan stakeholder dalam mengambil keputusan yang tepat untuk mengurangi angka tingkat kematian di Indonesia. Perancangan dashboard menggunakan Microsoft Power BI. Penggunaan software ini dikarenakan fiturnya yang lengkap, kemudahan akses, kepraktisan penggunaan, dan juga kemampuannya dalam menunjukkan data real-time.

Halaman rujukan menampilkan persebaran lokasi faskes rujukan yang tidak berada pada lokasi yang sama dengan lokasi faskes tingkat pertama melalui tampilan peta dengan arah panah yang mengarah ke lokasi faskes rujukan.  

## Latar Belakang Masalah
Menurut prediksi dari United Nations Population Fund (UNFPA) Indonesia, pada tahun 2019, jumlah penduduk Indonesia akan mencapai 266,9 juta orang dengan perincian 134 juta laki-laki dan 132,8 juta perempuan. Selain itu, diperkirakan jumlah kematian pada tahun 2019 mencapai 1,6 juta orang dan akan terus meningkat hingga mencapai 3,2 juta orang pada tahun 2045. Dengan kematian penduduk yang terus meningkat, penting untuk memahami dampaknya terhadap pelayanan kesehatan dan risiko kematian. Analisis lokasi fasilitas kesehatan dan profil kepesertaan JKN-KIS akan memperlihatkan ketersediaan layanan dan sejauh mana akses masyarakat terhadap pelayanan kesehatan, terutama pada kasus penyakit yang memerlukan rujukan dan diagnosa yang lebih rumit. Penelitian ini diharapkan dapat memberikan wawasan mendalam tentang faktor-faktor yang mempengaruhi risiko kematian dan kualitas layanan kesehatan di Indonesia. Sehingga, dapat memberikan dasar untuk pengambilan keputusan kebijakan yang lebih baik dalam meningkatkan sistem kesehatan dan pelayanan.

## Tujuan
Untuk memperkecil risiko kematian melalui analisis lokasi fasilitas kesehatan pada kasus penyakit yang membutuhkan rujukan, diagnosa penyakit, dan profil kepesertaan JKN-KIS. 
