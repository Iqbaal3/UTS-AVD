# UTS-AVD
Nama: Iqbal Nurriz Ramadhan

NIM: 2509116067

Kelas: Sistem Informasi (B)

## Deskripsi
Dataset Bike Buyers memuat data 1.000 pelanggan yang berkaitan dengan keputusan pembelian sepeda. Analisis ini bertujuan untuk memahami karakteristik pelanggan, mengidentifikasi faktor yang memengaruhi keputusan pembelian sepeda, serta menyediakan dasar pengambilan keputusan bagi strategi pemasaran.
Dataset terdiri dari 1.000 baris dan 13 kolom yang mencakup informasi demografi, kondisi ekonomi, dan status pembelian sepeda.

## Latar Belakang
Sepeda kini semakin relevan sebagai alternatif transportasi yang efisien, ekonomis, dan ramah lingkungan. Namun tidak semua orang memilih sepeda sebagai moda transportasi, keputusan ini dipengaruhi oleh berbagai faktor seperti pendapatan, usia, jarak tempuh, dan latar belakang pekerjaan.
Analisis ini dilakukan untuk menggali pola dari data pelanggan nyata guna menjawab pertanyaan: faktor apa yang paling menentukan seseorang membeli sepeda?

#Dataset
Sumber: Kaggle, Bike Buyers Dataset
Jumlah data: 1.000 baris, 13 kolom

Kolom utama:

-Marital Status

-Gender 

-Income

-Children 

-Education

-Occupation

-Home Owner

-Cars

-Commute Distance

-Region

-Age

-Purchased Bike

## Tahapan Proses

1. Business Understanding
Menetapkan tujuan analisis: mengidentifikasi faktor yang memengaruhi keputusan pembelian sepeda untuk mendukung strategi pemasaran.

3. Data Understanding
Memuat dataset dan melakukan pemahaman awal terhadap struktur, tipe data, serta statistik deskriptif tiap kolom.

5. Verifikasi Kualitas Data
   
Pengecekan tipe data : semua sesuai

Pengecekan inkonsistensi nilai : tidak ditemukan

Missing values : ditemukan pada 7 kolom (< 1,1%)

Duplikasi : tidak ditemukan

Outlier : ditemukan pada kolom Income (1%), Cars (5,9%), Age (0,4%)

## Hasil & Insight

Income : Responden dengan pendapatan lebih tinggi cenderung membeli sepeda

Usia : Kelompok usia produktif 30–50 tahun adalah segmen pembeli terbesar

Jarak Komuter : Semakin dekat jarak ke kantor, semakin tinggi kemungkinan membeli sepeda

Pekerjaan : Kelompok Professional paling banyak membeli sepeda

Region : North America mendominasi pembelian sepeda

Gender : Pria sedikit lebih banyak membeli, namun perbedaan tidak signifikan

## Exploratory Data Analysis (EDA)
EDA dilakukan untuk menemukan pola dan hubungan antar variabel menggunakan empat pendekatan utama.
Pertama, analisis komparasi dilakukan untuk membandingkan jarak komuter, gender, dan pekerjaan terhadap keputusan pembelian sepeda menggunakan bar chart dan boxplot. Kedua, analisis komposisi dilakukan untuk melihat proporsi pembelian sepeda berdasarkan region menggunakan pie chart. Ketiga, analisis distribusi dilakukan untuk melihat penyebaran data pada variabel Income dan Age menggunakan histogram. Keempat, analisis hubungan dilakukan untuk mengukur korelasi antar variabel numerik yaitu Income, Children, Cars, dan Age menggunakan heatmap.

## Kesimpulan
Berdasarkan seluruh proses eksplorasi data yang telah dilakukan tanpa data preparation/data cleaning lanjutan, didapatkan bahwa keputusan seseorang dalam membeli sepeda dipengaruhi oleh kombinasi faktor demografis, ekonomi, dan perilaku. Responden dengan income lebih tinggi dan bekerja sebagai profesional cenderung lebih banyak membeli sepeda. Usia juga terbukti berperan penting, kelompok usia produktif antara 30 hingga 50 tahun merupakan segmen paling aktif, sementara responden yang lebih tua cenderung tidak membeli.
Dari sisi jarak komuter, semakin dekat jarak rumah ke tempat kerja, semakin tinggi kecenderungan membeli sepeda, mengindikasikan bahwa sepeda dipandang sebagai alat transportasi harian jarak pendek. Secara geografis, North America mendominasi pembelian dibandingkan region lain. Faktor gender memiliki pengaruh relatif kecil.
Profil pembeli tipikal: usia 30–50 tahun, pendapatan menengah ke atas, pekerjaan profesional, jarak komuter dekat, berdomisili di North America. Temuan ini dapat menjadi dasar strategi pemasaran yang lebih tepat sasaran, fokus pada kelompok usia produktif berpenghasilan menengah ke atas dengan produk sepeda berorientasi commuting jarak pendek.


