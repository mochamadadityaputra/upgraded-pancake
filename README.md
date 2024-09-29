# Capstone Project 3: Prediction Saudi Arabia Used Cars Price Using Machine Learning
Additional Portofolio Capstone Project Modul 3 Purwadhika Job Connector Data Science Online Batch 15 (JCDSOL-015)
Mochamad Aditya Putra
Link Drive untuk penjelasan PPT: 
Link Drive untuk PPT:
Link untuk google collab notebook:

# Data Dictionary
|kolom | Penjelasan |
|----- | ---------- |
| Type  | Nama mobil bekas|
| Region| Wilayah tempat mobil bekas ditawarkan untuk dijual|
| Make| Nama perusahaan pembuat Mobil|
| Gear_Type  | Ukuran tipe gear mobil bekas |
| Origin| Asal mobil bekas|
| Options | Pilihan fitur pada mobil bekas|
| Year| Tahun pembuatan|
| Engine_Size | Ukuran mesin mobil bekas|
| Mileage | Jarak tempuh mobil bekas|
| Negotiable | Benar jika harga 0, berarti bisa nego|
| Price| Harga mobil bekas|

# Background
Perkembangan Penjualan Pasar Mobil Bekas di Arab Saudi

Pasar mobil bekas di Arab Saudi mengalami pertumbuhan yang signifikan dalam beberapa tahun terakhir. Beberapa faktor pendorong utama termasuk peningkatan kesadaran konsumen tentang nilai mobil bekas, pertumbuhan populasi, dan ketersediaan platform digital yang mempermudah transaksi jual-beli mobil bekas.

Peningkatan Permintaan: Seiring dengan pertumbuhan populasi dan urbanisasi, banyak konsumen yang mencari mobil bekas berkualitas sebagai alternatif dari mobil baru. Ini terutama berlaku bagi mereka yang ingin menghemat biaya tetapi tetap mendapatkan mobil dengan performa baik.

Platform Online Mempermudah Transaksi: Platform online seperti syarah.com telah memperluas pasar dengan menawarkan berbagai pilihan mobil bekas dengan transparansi harga dan kondisi kendaraan. Hal ini memudahkan pembeli untuk membandingkan harga dan memilih mobil yang sesuai dengan anggaran mereka.

Dampak Ekonomi: Selain itu, fluktuasi harga minyak dan reformasi ekonomi yang diterapkan oleh pemerintah dalam Visi 2030 turut berpengaruh pada preferensi konsumen. Banyak konsumen yang beralih ke mobil bekas sebagai pilihan lebih ekonomis dalam situasi ketidakpastian ekonomi.

Tren Mobil Listrik dan Hibrida: Ada juga peningkatan minat terhadap mobil bekas dengan teknologi ramah lingkungan, seperti mobil listrik dan hibrida, sejalan dengan inisiatif pemerintah untuk mengurangi emisi karbon di negara tersebut.

Dataset ini didapat dari Purwadikha dan mewakili daftar mobil bekas yang dikumpulkan dari platform (syarah.com), dengan atribut terperinci untuk setiap mobil seperti tipe model, wilayah, merek, tahun, ukuran mesin, jarak tempuh, dan harga. Pasar mobil bekas di Arab Saudi sangat kompetitif, dipengaruhi oleh kondisi ekonomi, preferensi konsumen, dan kebijakan pemerintah mengenai impor otomotif dan pajak.

Gambaran Pasar:

Arab Saudi merupakan pasar besar untuk mobil baru maupun bekas karena populasi yang besar dan ketergantungan pada mobil sebagai moda transportasi utama. Merek populer seperti Toyota, Kia, GMC, dan merek mewah seperti Land Rover mendominasi pasar. Faktor-faktor yang memengaruhi nilai mobil bekas termasuk reputasi merek, jarak tempuh, kondisi, dan tahun produksi mobil.

Selain itu, dorongan pemerintah Saudi terhadap Visi 2030, yang bertujuan untuk mendiversifikasi perekonomian, juga mempunyai pengaruh tidak langsung dengan menjadikan kendaraan lebih terjangkau melalui reformasi kebijakan, sehingga mendorong minat terhadap pasar mobil bekas.

# Problem Statement
Tujuan penelitian kali ini adalah untuk membantu perusahaan untuk memprediksi harga mobil bekas berdasarkan berbagai atribut seperti jenis mobil, merek, ukuran mesin, jarak tempuh, tahun pembuatan, dan wilayah. Sifat pasar mobil bekas yang berfluktuasi dan beragamnya pilihan yang tersedia membuat harga tidak dapat diprediksi. Selain itu, memahami bagaimana berbagai faktor seperti ukuran mesin dan jarak tempuh memengaruhi harga akhir akan memungkinkan strategi penetapan harga yang lebih baik.

Pertanyaan Kunci:
1. Apa faktor utama yang mempengaruhi harga mobil bekas di Arab Saudi?
2. Bagaimana cara memprediksi harga mobil bekas secara akurat berdasarkan fitur-fiturnya?
