<p align="center">
  <img src="Image/Header.jpg" width="1000" height="500">
  <br>
</p>

# 📖 **Pendahuluan**

Proyek ini bertujuan untuk menganalisis tingkat kemiskinan di Indonesia periode 2019 - 2024 menggunakan metode K-Means. Analisis ini dilakukan untuk mengelompokkan provinsi berdasarkan kesamaan tingkat kemiskinan, sehingga dapat menggambarkan pola dan perbedaan kondisi sosial ekonomi antar wilayah.

# 💡 **Latar Belakang (Yasinta)**


Kemiskinan merupakan salah satu isu pembangunan sosio-ekonomi yang paling mendesak dan kompleks di Indonesia. Meskipun telah terjadi peningkatan pertumbuhan ekonomi secara umum, tantangan dalam mengurangi disparitas pendapatan dan menjangkau kelompok rentan tetap signifikan. Data tingkat kemiskinan menjadi indikator krusial dalam mengukur keberhasilan pembangunan dan efektivitas kebijakan pemerintah. Oleh karena itu, analisis mendalam terhadap tren dan distribusi kemiskinan dari tahun ke tahun—khususnya pada periode 2019 hingga 2024—sangat diperlukan untuk memahami dinamika perubahan sosial ekonomi pasca-pandemi dan adaptasi kebijakan yang diterapkan.

Analisis tingkat kemiskinan seringkali disajikan dalam bentuk statistik agregat nasional atau perbandingan langsung antar provinsi. Namun, pendekatan ini cenderung menyembunyikan heterogenitas kondisi di lapangan. Indonesia, sebagai negara kepulauan yang luas, memiliki keragaman yang ekstrem dalam faktor-faktor yang memengaruhi kemiskinan, mulai dari akses infrastruktur, kondisi geografis, hingga struktur ekonomi lokal. Untuk merumuskan kebijakan yang tepat sasaran, penting untuk mengidentifikasi pola-pola kemiskinan yang serupa di antara berbagai provinsi. Pengelompokan ini akan mengungkapkan perbedaan kondisi sosial ekonomi yang mendasar antar wilayah, memungkinkan alokasi sumber daya yang lebih efisien dan intervensi yang disesuaikan dengan kebutuhan spesifik kelompok provinsi.

Dalam konteks analisis data yang kompleks dan multidimensi, metode Clustering K-Means menawarkan solusi yang efektif. K-Means adalah algoritma pembelajaran tanpa pengawasan (unsupervised learning) yang bertujuan untuk mengelompokkan $n$ objek pengamatan ke dalam $k$ cluster (kelompok) berdasarkan kedekatan jarak antara objek. Dalam proyek ini, K-Means akan diterapkan untuk:Mengelompokkan provinsi berdasarkan data tingkat kemiskinan periode 2019-2024.Menggambarkan pola tingkat kemiskinan yang tersembunyi (misalnya, kelompok provinsi dengan kemiskinan yang stagnan, menurun pesat, atau fluktuatif).Penerapan metode K-Means ini tidak hanya memberikan gambaran statistik, tetapi juga menghasilkan visualisasi dan interpretasi yang jelas mengenai peta kemiskinan di Indonesia.

# 🎯 **Tujuan Penelitian (Yasinta)**

Berdasarkan latar belakang di atas, penelitian ini memiliki tujuan utama untuk melakukan analisis klasterisasi angka kemiskinan di Indonesia periode 2019–2024 menggunakan Metode K-Means. Hasil klasterisasi ini diharapkan dapat memberikan kontribusi praktis berupa peta klaster kemiskinan yang jelas, yang dapat digunakan oleh Kementerian/Lembaga terkait dan pemerintah daerah sebagai dasar perumusan strategi penanggulangan kemiskinan yang lebih fokus, terukur, dan berbasis pada kondisi sosial ekonomi regional yang sebenarnya.

# 📊 **Data dan Variabel (Avin)**

<div align="center" style="background-color:#0f1419; padding:16px; border-radius:8px;">
  <img src="Image/Logo_ODJ.png" alt="Open Data Jabar" width="250"><br>
  <span style="color:white; font-weight:bold; font-size:16px;">Open Data Jabar</span>
</div>
  <br>
</p>

###  Cuplikan Data

| id | Kode Provinsi  | Provinsi              | Persentase Penduduk Miskin  | Tahun |
|----|----------------|-----------------------|-----------------------------|--------|
| 1  | 11             | ACEH                  | 15.32                       | 2019   |
| 2  | 12             | SUMATERA UTARA        | 8.83                        | 2019   |
| 3  | 13             | SUMATERA BARAT        | 6.42                        | 2019   |
| 4  | 14             | RIAU                  | 7.08                        | 2019   |
| 5  | 15             | JAMBI                 | 7.60                        | 2019   |
| …  | …              | …                     | …                           | …      |
| 224| 92             | PAPUA BARAT DAYA      | 18.13                       | 2024   |
| 225| 94             | PAPUA                 | 17.26                       | 2024   |
| 226| 95             | PAPUA SELATAN         | 17.44                       | 2024   |
| 227| 96             | PAPUA TENGAH          | 29.76                       | 2024   |
| 228| 97             | PAPUA PEGUNUNGAN      | 32.97                       | 2024   |

| Periode               | Tahun      | Keterangan                                           |
|:----------------------|:----------:|------------------------------------------------------|
| Pra & Pandemi COVID-19   | 2019 – 2021  | Mencerminkan dampak awal hingga puncak pandemi       |
| Pasca COVID-19        | 2022 – 2024  | Mencerminkan proses pemulihan ekonomi                |

# ⚙️ **Metodologi (Joi)**

Proyek ini menggunakan dua pendekatan utama:
1. Statistik Deskriptif : menggambarkan sebaran dan tren tingkat kemiskinan provinsi di Indonesia pada periode 2019–2024.
2. Klastering K-Means : mengelompokkan provinsi dengan pola kemiskinan yang mirip untuk melihat kesamaan kondisi ekonomi antar wilayah.

# 🎨 **Visualisasi**
### 1. Peta Klasterisasi Tingkat Kemiskinan Provinsi di Indonesia (Avin)
<div align="center" style="background-color:#0f1419; padding:16px; border-radius:8px;">
  <img src="Image/2021.png" width="1000" height="500"><br>
  <span style="color:white; font-weight:bold; font-size:16px;">Gambar 1. Peta Klasterisasi Pra & Pandemi Covid-19</span>
</div>
  <br>
</p>

### Tabel Hasil Klasterisasi Provinsi Pra & Pandemi Covid-19

| Cluster | Kriteria | Nama Provinsi |
|:-------:|:-------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | **Tinggi** | Nusa Tenggara Timur, Papua Barat, Papua |
| **2** | **Menengah** | Sumatera Utara, Sumatera Barat, Riau, Jambi, Bangka Belitung, Kepulauan Riau, Jakarta Raya, Jawa Barat, Banten, Bali, Kalimantan Barat, Kalimantan Tengah, Kalimantan Selatan, Kalimantan Timur, Kalimantan Utara, Sulawesi Utara, Sulawesi Selatan |
| **3** | **Rendah** | Aceh, Bengkulu, Nusa Tenggara Barat, Gorontalo, Maluku, Sumatera Selatan, Lampung, Jawa Tengah, Yogyakarta, Jawa Timur, Sulawesi Tengah, Sulawesi Tenggara, Sulawesi Barat |

<div align="center" style="background-color:#0f1419; padding:16px; border-radius:8px;">
  <img src="Image/2024.png" width="1000" height="500"><br>
  <span style="color:white; font-weight:bold; font-size:16px;">Gambar 2. Peta Klasterisasi Pasca Covid-19</span>
</div>
  <br>
</p>

### Tabel Hasil Klasterisasi Provinsi Pasca Covid-19

| Cluster | Kriteria | Nama Provinsi |
|:-------:|:-------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | **Tinggi** | Nusa Tenggara Timur, Papua Barat, Papua |
| **2** | **Menengah** | Sumatera Utara, Sumatera Barat, Riau, Jambi, Bangka Belitung, Kepulauan Riau, Jakarta Raya, Jawa Barat, Banten, Bali, Kalimantan Barat, Kalimantan Tengah, Kalimantan Selatan, Kalimantan Timur, Kalimantan Utara, Sulawesi Utara, Sulawesi Selatan |
| **3** | **Rendah** | Aceh, Bengkulu, Nusa Tenggara Barat, Gorontalo, Maluku, Sumatera Selatan, Lampung, Jawa Tengah, Yogyakarta, Jawa Timur, Sulawesi Tengah, Sulawesi Tenggara, Sulawesi Barat |

   
### 2. Trend Data rata rata pertahun (line chart) (Joy)
<div align="center" style="background-color:#0f1419; padding:16px; border-radius:8px;">
  <img src="Image/rata-ratapersentasependudukmiskinpertahun.png" width="1000" height="500"><br>
  <span style="color:white; font-weight:bold; font-size:16px;">Gambar 3. Tren Rata-Rata Presentase Penduduk Miskin Nasional</span>
</div>
  <br>
</p>

### 3. Provinsi 10 tertinggi dan 10 terendah (Covid) (Bar Chart) (Wita)
### 4. Provinsi 10 tertinggi dan 10 terendah (Pasca Covid) (Bar Chart) (Sisca)
### 5. Distribusi Data Berdasarkan Cluster Gabungan (Density Plot) (sisca)
### 6. Distribusi Data Berdasarkan Cluster Covid (Density Plot) (Joy)
### 7. Distribusi Data Berdasarkan Cluster Pasca Covid (Density Plot) (Wita)
<div align="center" style="background-color:#0f1419; padding:16px; border-radius:8px;">
  <img src="Image/density pasca covid.png" width="1000" height="500"><br>
  <span style="color:white; font-weight:bold; font-size:16px;">Gambar gatau cobain dlu. Density Plot Pasca Covid</span>
</div>
  <br>
</p>

# 💎 **Manfaat Penelitian (Yasinta)**


Tentu, berdasarkan latar belakang dan judul "ANALISIS KLASTERISASI ANGKA KEMISKINAN DI INDONESIA PERIODE 2019–2024 MENGGUNAKAN METODE K-MEANS", berikut adalah manfaat utama dari proyek atau penelitian ini, dikelompokkan berdasarkan penerima manfaat:

🌟 Manfaat Analisis Klasterisasi Angka Kemiskinan
Proyek ini diharapkan memberikan manfaat yang signifikan bagi berbagai pihak, terutama dalam konteks pengambilan keputusan dan perumusan kebijakan.

1. Manfaat Bagi Pemerintah dan Pembuat Kebijakan (Pusat & Daerah)
Penyusunan Kebijakan yang Tepat Sasaran (Targeted Policy): Hasil klasterisasi (pengelompokan) provinsi akan mengidentifikasi wilayah mana yang memiliki pola kemiskinan serupa. Ini memungkinkan pemerintah merancang intervensi program (seperti bantuan sosial, pelatihan kerja, atau pembangunan infrastruktur) yang spesifik dan disesuaikan dengan kebutuhan setiap klaster, sehingga meningkatkan efektivitas anggaran.

Alokasi Sumber Daya yang Efisien: Dengan memahami klaster mana yang paling parah atau paling rentan, pemerintah dapat memprioritaskan alokasi dana (misalnya, Dana Transfer Daerah atau Dana Desa) ke wilayah yang benar-benar membutuhkan, menghindari pemborosan sumber daya pada wilayah yang pola kemiskinannya sudah membaik.

Pemantauan dan Evaluasi Kinerja: Klaster yang terbentuk dapat digunakan sebagai tolok ukur (benchmarking). Pemerintah dapat membandingkan kinerja penanggulangan kemiskinan antar provinsi dalam klaster yang sama, untuk mengidentifikasi praktik terbaik (best practices) yang dapat direplikasi.

Perencanaan Pembangunan Regional: Data klasterisasi memberikan panduan bagi Badan Perencanaan Pembangunan Nasional/Daerah (Bappenas/Bappeda) dalam menyusun Rencana Pembangunan Jangka Menengah Daerah (RPJMD) yang lebih kontekstual dan berbasis bukti.

2. Manfaat Bagi Dunia Akademis dan Peneliti
Pengembangan Ilmu Pengetahuan: Penelitian ini berkontribusi pada penerapan praktis algoritma Machine Learning (K-Means) di bidang sosial ekonomi dan statistik, khususnya di Indonesia.

Dasar Penelitian Lanjutan: Hasil klasterisasi dapat menjadi dasar untuk penelitian lebih lanjut. Peneliti dapat menggunakan klaster yang terbentuk sebagai variabel eksogen untuk menyelidiki faktor-faktor penentu (misalnya, Indeks Pembangunan Manusia, inflasi, atau tingkat pengangguran) yang mendorong provinsi masuk ke dalam klaster kemiskinan tertentu.

Metodologi Baru: Penelitian ini dapat menjadi referensi metodologis bagi peneliti lain yang ingin melakukan analisis komparatif atau klasterisasi pada data pembangunan regional lainnya.

3. Manfaat Bagi Lembaga Non-Pemerintah (LSM dan Donor)
Fokus Program: Lembaga Swadaya Masyarakat (LSM) dan lembaga donor dapat menggunakan peta klaster ini untuk memfokuskan program bantuan dan pengembangan mereka pada klaster provinsi yang paling membutuhkan dukungan non-pemerintah.

Advokasi yang Lebih Kuat: Data klasterisasi yang dihasilkan memberikan bukti empiris yang kuat untuk mendukung upaya advokasi dalam menuntut kebijakan yang lebih adil dan merata.



# 👥 **Tim Penyusun**

* [Joice Junansi Tandirerung](https://github.com/JoiceJunansi) (M0501251007) 
* [Avin Rahmadian](https://github.com/avinrahmadian) (M0501251023)
* [Charisma Yasintasya Kafilla](https://github.com/yasintasya) (M0501251039)
* [Francisca Juventini Mandas](https://github.com/franciscajuventini09) (M0501251045)
* [Baiq Wita Rachmatia](https://github.com/baiqwitaa) (M0501251061)

