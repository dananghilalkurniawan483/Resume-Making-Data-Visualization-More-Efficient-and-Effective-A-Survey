#### Nama : Danang Hilal Kurniawan

#### NIM : 122450085

#### Kelas : RA

## Judul : Making Data Visualization More Efficient and Effective: A Survey

### Penulis : Xuedi Qin, Yuyu Luo, Nan Tang, Guoliang Li

### Jurnal: The VLDB Journal

### DOI : 10.1007/s00778-019-00588-3

### Abstrak

Paper ini mengkaji teknik-teknik yang membuat visualisasi data lebih efisien dan efektif, yang semakin penting dalam dunia bisnis berbasis data saat ini. Visualisasi data telah menjadi alat krusial untuk mendukung pengambilan keputusan di berbagai industri. Namun, volume, kecepatan, dan variasi data yang terus meningkat menciptakan tantangan baru dalam membuat visualisasi yang tidak hanya menarik, tetapi juga efisien dan dapat diandalkan. Artikel ini menyoroti tiga aspek utama dalam membuat visualisasi data lebih efisien dan efektif:

Spesifikasi Visualisasi: Metode yang memungkinkan pengguna menentukan kebutuhan mereka dalam menghasilkan visualisasi. Pendekatan Efisien untuk Visualisasi Data: Teknik untuk memproses data dan spesifikasi visualisasi guna menghasilkan visualisasi yang cepat dan skalabel pada kecepatan interaktif. Rekomendasi Visualisasi Data: Sistem yang secara otomatis melengkapi spesifikasi visualisasi yang tidak lengkap atau merekomendasikan visualisasi yang lebih menarik berdasarkan referensi visualisasi.

### 1. Pendahuluan

Makalah ini membahas visualisasi data sebagai salah satu area yang berkembang pesat dalam manajemen data. Dengan kontribusi dari berbagai bidang, visualisasi data telah menjadi alat yang penting untuk memahami dan menganalisis informasi kompleks. Penulis meninjau berbagai pendekatan untuk membuat visualisasi data lebih efisien dan efektif, serta mengidentifikasi tantangan dan peluang penelitian yang dapat diambil oleh peneliti, terutama dalam konteks manajemen data.

### 2. Spesifikasi Visualisasi Data

Spesifikasi visualisasi data adalah proses di mana pengguna menentukan bagaimana data harus divisualisasikan untuk menyampaikan informasi dengan cara yang paling jelas dan informatif. Hal ini mencakup pembuatan representasi visual yang efektif dan memerlukan pengetahuan mendalam tentang data serta tujuan analisis.

Sistem komersial seperti Tableau dan Microsoft Power BI telah memudahkan pengguna dalam membuat visualisasi data tanpa memerlukan keterampilan teknis yang mendalam. Namun, tantangan tetap ada, terutama dalam mengelola spesifikasi visualisasi untuk dataset besar atau kompleks. Masalah yang sering dihadapi termasuk keterbatasan dalam interaksi pengguna dengan sistem dan bagaimana sistem tersebut dapat menangani volume data yang besar secara efisien tanpa mengurangi kualitas visualisasi.

### 3. Pendekatan Efisien untuk Visualisasi Data

Untuk meningkatkan efisiensi dalam visualisasi data, beberapa pendekatan dan teknik telah diidentifikasi, di antaranya:

Pemrosesan Query dan Indeksasi: Ini adalah teknik yang digunakan untuk mempercepat pengambilan data dari database besar. Dengan mengoptimalkan cara query dijalankan dan bagaimana data diindeks, proses pengambilan data dapat dipercepat, yang secara langsung mempengaruhi kecepatan rendering visualisasi. Penggunaan teknik ini sangat penting dalam aplikasi real-time di mana keputusan harus dibuat dengan cepat berdasarkan data yang dianalisis.

Optimasi Pravisualisasi: Sebelum data divisualisasikan, data dapat diproses, diringkas, atau difilter untuk mengurangi jumlah data yang perlu divisualisasikan. Langkah-langkah ini bertujuan untuk meningkatkan kecepatan sistem dalam menampilkan visualisasi, terutama ketika menangani dataset yang sangat besar atau kompleks. Ini mencakup teknik seperti agregasi data, sampling, dan filtering, yang memungkinkan visualisasi lebih responsif dan lebih mudah dicerna oleh pengguna.

Pemrosesan Paralel: Dalam konteks dataset besar dan kompleks, pemrosesan paralel adalah solusi untuk mempercepat rendering visualisasi. Dengan memanfaatkan kekuatan komputasi dari prosesor multi-core atau arsitektur komputasi terdistribusi, tugas pemrosesan dapat dibagi menjadi beberapa sub-tugas yang dikerjakan secara bersamaan. Hal ini memungkinkan visualisasi yang lebih cepat, terutama untuk aplikasi yang memerlukan analisis data secara real-time.

### 4. Rekomendasi Visualisasi

Rekomendasi visualisasi adalah proses di mana sistem secara otomatis menyarankan tipe visualisasi yang paling sesuai untuk data tertentu berdasarkan karakteristik data dan tujuan analisis. Sistem rekomendasi ini menjadi semakin penting karena kompleksitas data dan beragamnya tipe visualisasi yang tersedia.

Beberapa tantangan utama dalam rekomendasi visualisasi adalah:

Pemahaman Konteks Data: Sistem rekomendasi harus mampu memahami konteks data yang dianalisis untuk dapat memberikan saran yang relevan. Misalnya, data yang berisi tren mungkin lebih baik divisualisasikan dengan garis atau kurva, sementara data distribusi mungkin lebih cocok dengan histogram atau kotak-kotak plot.

Model Pembelajaran Mesin: Untuk membuat rekomendasi yang akurat, banyak sistem memanfaatkan teknik pembelajaran mesin. Namun, pengembangan model pembelajaran mesin yang efektif untuk rekomendasi visualisasi masih menjadi tantangan besar. Model harus dapat memprediksi tipe visualisasi yang optimal dengan mempertimbangkan berbagai variabel, seperti tujuan analisis, struktur data, dan preferensi pengguna.

Sistem rekomendasi yang efektif dapat membantu pengguna yang mungkin tidak memiliki pengetahuan mendalam tentang teori visualisasi data untuk tetap dapat memilih tipe visualisasi yang paling tepat dan informatif.

### 5. Teknik dan Sistem yang Relevan

Berbagai teknik dan sistem telah dikembangkan untuk mendukung visualisasi data yang lebih efisien dan efektif. Beberapa sistem ini dirancang untuk memproses, menganalisis, dan memvisualisasikan data dalam skala besar, sementara yang lain fokus pada peningkatan pengalaman pengguna dalam membuat dan berinteraksi dengan visualisasi data.

Alat-alat visualisasi modern seperti Tableau, Microsoft Power BI, dan Google Data Studio telah menjadi standar dalam industri untuk membuat visualisasi data yang interaktif dan mudah diakses. Alat-alat ini tidak hanya menyediakan berbagai pilihan visualisasi tetapi juga memungkinkan integrasi data dari berbagai sumber dan kolaborasi antara pengguna.

Algoritma dan framework untuk pemrosesan dan analisis data juga berperan penting dalam mendukung visualisasi data. Algoritma untuk pengelompokan, pengurutan, dan analisis statistik, misalnya, memungkinkan pembuatan visualisasi yang lebih kaya dan bermakna. Framework seperti D3.js dan Vega telah menjadi alat yang kuat untuk membuat visualisasi kustom yang disesuaikan dengan kebutuhan pengguna.

### 6. Arah Penelitian Lainnya

#### 5.1 Persiapan Data untuk Visualisasi

Data dalam kehidupan nyata sering kali kotor atau tidak bersih, yang dapat menyebabkan visualisasi yang menyesatkan. Untuk mengatasi hal ini, data perlu dibersihkan sebelum divisualisasikan. Proses pembersihan data meliputi normalisasi nilai, deduplikasi, imputasi nilai yang hilang, dan deteksi outlier.

Contohnya, Scorpion adalah sistem yang memungkinkan pengguna untuk mengidentifikasi dan menghapus outlier dari hasil query agregasi tanpa mempengaruhi data lainnya. Studi juga menunjukkan bahwa pendekatan yang berbeda dalam menangani data yang hilang (seperti zero-filling, marginal mean, dan interpolasi linear) dapat mempengaruhi kualitas dan akurasi interpretasi data.

Peluang Penelitian:

Deteksi Visualisasi yang Bias: Mengembangkan metode untuk mendeteksi visualisasi yang bias akibat data yang kotor merupakan area penelitian yang penting. Pendekatan ini dapat diintegrasikan dengan teknik statistik untuk mendeteksi anomali atau bias dalam visualisasi. Pembersihan Data yang Terkait Tugas: Penelitian lebih lanjut diperlukan untuk mengembangkan teknik pembersihan data yang disesuaikan dengan tugas spesifik. Misalnya, pembersihan data untuk analisis tren mungkin berbeda dengan pembersihan data untuk analisis distribusi.

#### 5.2 Tolok Ukur Visualisasi Data

Meskipun tolok ukur seperti ImageNet telah menjadi standar untuk klasifikasi gambar, tidak ada tolok ukur yang serupa untuk visualisasi data. Pengembangan tolok ukur untuk visualisasi data akan membantu dalam mengukur kinerja dan efektivitas teknik visualisasi.

VizNet adalah salah satu upaya untuk menciptakan basis data besar yang dapat digunakan sebagai dasar perbandingan dalam pengembangan teknik desain visualisasi. Dengan lebih dari 31 juta dataset, VizNet menyediakan baseline yang diperlukan untuk penelitian lebih lanjut dalam bidang ini.

Peluang Penelitian:

Kategorisasi Visualisasi: Salah satu tantangan utama adalah mendefinisikan kategori untuk visualisasi data. Berbeda dengan gambar yang dapat diklasifikasikan berdasarkan objek yang jelas, visualisasi data perlu dikategorikan berdasarkan konsep abstrak seperti "tren" atau "distribusi". Data Pelatihan: Meskipun kategorisasi dapat dilakukan, proses pelabelan visualisasi adalah tugas yang sangat kompleks. Tantangan lebih lanjut adalah bagaimana menggunakan data berlabel ini untuk melatih model pembelajaran mesin yang dapat memprediksi visualisasi yang optimal.

#### 5.3 Visualisasi Data untuk Aplikasi Terkait Basis Data

Visualisasi data memiliki peran penting dalam aplikasi terkait basis data seperti Excel, Google Sheets, dan berbagai alat lain yang digunakan sehari-hari oleh para profesional. Dengan kemajuan teknik visualisasi, terdapat peluang besar untuk meningkatkan aplikasi-aplikasi ini agar lebih efektif dalam mendukung analisis data.

Peluang Penelitian:

Visualisasi Data untuk Penemuan Data: Salah satu tantangan besar dalam analisis data adalah menemukan dataset yang relevan dari kumpulan data besar (data lake). Visualisasi dapat membantu dalam memberikan pemahaman cepat tentang dataset yang ditemukan. Visualisasi Data untuk Debugging Data: Debugging data adalah proses mengidentifikasi kesalahan dalam data, yang mungkin tidak terdeteksi sebagai bug dalam program. Menggabungkan teknik visualisasi dalam proses ini dapat membantu mengidentifikasi dan memperbaiki kesalahan data dengan lebih efektif.

### Kesimpulan Paper

Kesimpulan Setelah mengeksplorasi berbagai aspek dari paper "Making Data Visualization More Efficient and Effective: A Survey," saya memahami bahwa visualisasi data bukan hanya sekadar alat untuk menampilkan informasi, tetapi juga kunci untuk mengoptimalkan pengambilan keputusan berbasis data di berbagai industri. Dengan semakin kompleksnya data yang kita hadapi saat ini, efisiensi dan efektivitas dalam visualisasi data menjadi semakin penting.

1.  Spesifikasi Visualisasi Dalam hal spesifikasi visualisasi, paper ini menunjukkan betapa pentingnya pemahaman yang mendalam tentang bagaimana mendefinisikan kebutuhan visualisasi. Saya menemukan bahwa bahasa visualisasi seperti Vega dan Vega-Lite memainkan peran penting dalam mempermudah pembuatan visualisasi yang kompleks. Vega menyediakan spesifikasi tingkat rendah yang memungkinkan pengaturan detail teknis secara mendalam, sementara Vega-Lite menawarkan spesifikasi tingkat tinggi yang lebih intuitif, memungkinkan pengguna untuk fokus pada jenis visualisasi tanpa terjebak dalam rincian teknis. Pendekatan ini memberikan fleksibilitas dalam pembuatan visualisasi, baik bagi pengguna yang memerlukan kontrol mendetail maupun bagi mereka yang menginginkan cara yang lebih cepat dan sederhana.

2.  Pendekatan Efisien untuk Visualisasi Data Efisiensi dalam visualisasi data adalah salah satu fokus utama paper ini. Saya mempelajari bahwa untuk mengatasi tantangan data besar, kita perlu mengadopsi pendekatan yang dapat meningkatkan kecepatan dan skalabilitas visualisasi. Penggunaan query SQL dan alat seperti D3.js membantu dalam merender data dengan performa tinggi. Selain itu, teknik Approximate Query Processing (AQP) memungkinkan pemrosesan visualisasi yang lebih cepat dengan hasil yang cukup akurat melalui sampling, sehingga mengurangi waktu tunggu untuk visualisasi yang besar dan kompleks. Visualisasi data progresif juga memberikan solusi dengan menggunakan agregasi hierarkis dan sampling bertahap, yang memungkinkan pengguna untuk berinteraksi dengan data parsial sambil menunggu hasil yang lebih lengkap. Sistem seperti Ermac dan Kyrix, yang mengintegrasikan pemrosesan data dengan rendering visualisasi secara efisien, merupakan contoh penerapan teknologi yang mendukung efisiensi ini.

3.  Rekomendasi Visualisasi Data Sistem rekomendasi visualisasi data yang dibahas dalam paper ini memberikan solusi untuk tantangan dalam menentukan visualisasi yang tepat. Dengan adanya rekomendasi berbasis spesifikasi, sistem seperti DeepEye dan Voyager dapat melengkapi spesifikasi visualisasi yang tidak lengkap atau memberikan saran berdasarkan referensi visualisasi yang ada. Selain itu, pendekatan berbasis perilaku, yang memanfaatkan data perilaku pengguna sebelumnya, dapat membantu dalam merekomendasikan visualisasi yang lebih relevan. Saya juga menemukan bahwa rekomendasi yang dipersonalisasi, yang disesuaikan berdasarkan interaksi pengguna sebelumnya, meningkatkan relevansi seiring waktu. Pendekatan berbasis pembelajaran mesin seperti Draco, yang menggunakan RankSVM, menawarkan solusi canggih untuk merekomendasikan visualisasi berdasarkan preferensi pengguna yang dipelajari dari data crowdsourcing.

Secara keseluruhan, paper ini memberikan wawasan mendalam tentang bagaimana kita dapat mengatasi tantangan dalam visualisasi data besar dan kompleks dengan menerapkan berbagai teknik dan sistem yang efektif. Dengan memahami dan menerapkan teknik-teknik ini, kita dapat memastikan bahwa visualisasi data tidak hanya informatif tetapi juga efisien dan relevan, mendukung pengambilan keputusan yang lebih baik di era big data yang terus berkembang.
