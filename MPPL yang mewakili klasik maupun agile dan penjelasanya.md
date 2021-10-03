## Contoh MPPL yang mewakili klasik


## WATERFALL
	      Waterfall adalah suatu metodologi pengembangan perangkat lunak yang mengusulkan pendekatan kepada perangkat lunak sistematik dan sekuensial yang mulai pada tingkat kemajuan sistem pada seluruh analisis, design, kode, pengujian dan pemeliharaan. Nama model ini sebenarnya adalah “Linear Sequential Model”. Model ini sering disebut dengan “classic life cycle” atau model waterfall. Model ini adalah model yang muncul pertama kali yaitu sekitar tahun 1970 sehingga sering dianggap kuno, tetapi merupakan model yang paling banyak dipakai didalam Software Engineering (SE).
Proses pada metodologi Waterfall:

* Requirement Analysis
     Seluruh kebutuhan software harus bisa didapatkan dalam fase ini, termasuk didalamnya kegunaan software yang diharapkan pengguna dan batasan software. Informasi ini biasanya dapat diperoleh melalui wawancara, survey atau diskusi. Informasi tersebut dianalisis untuk mendapatkan dokumentasi kebutuhan pengguna untuk digunakan pada tahap selanjutnya.

* System Design
Tahap ini bertujuan untuk memberikan gambaran apa yang seharusnya dikerjakan dan bagaimana tampilannya. Tahap ini membantu dalam menspesifikasikan kebutuhan hardware dan sistem serta mendefinisikan arsitektur sistem secara keseluruhan.

* Implementation
Dalam tahap ini dilakukan pemrograman. Pembuatan software dipecah menjadi modul-modul kecil yang nantinya akan digabungkan dalam tahap berikutnya. Selain itu dalam tahap ini juga dilakukan pemeriksaaan terhadap modul yang dibuat, apakah sudah memenuhi fungsi yang diinginkan atau belum.

* Integration & Testing
Di tahap ini dilakukan penggabungan modul-modul yang sudah dibuat dan dilakukan pengujian ini dilakukan untuk mengetahui apakah software yang dibuat telah sesuai dengan desainnya dan masih terdapat kesalahan atau tidak.

* Operation & Maintenance
Ini merupakan tahap terakhir dalam model waterfall. Software yang sudah jadi dijalankan serta dilakukan pemeliharaan. Pemeliharaan termasuk dalam memperbaiki  kesalahan yang tidak ditemukan pada langkah sebelumnya. Perbaikan implementasi unit sistem dan peningkatan jasa sistem sebagai kebutuhan baru.


## Prototyping	
   Prototyping adalah proses iterative dalam pengembangan sistem dimana requirement diubah ke dalam sistem yang bekerja (working system) yang secara terus menerus diperbaiki melalui kerjasama antara user dan analis. Prototype juga bisa dibangun melalui beberapa tool  pengembangan untuk menyederhanakan proses.

   * Pengumpulan kebutuhan
    Developer dan klien akan bertemu terlebih dahulu dan kemudian menentukan tujuan umum, kebutuhan yang diketahui dan gambaran bagian-bagian yang akan dibutuhkan berikutnya.

   * Perancangan
    Perancangan dilakukan dengan cepat dan rancangan tersebut mewakili semua aspek software yang diketahui, dan rancangan ini menjadi dasar pembuatan prototype.

   * Evaluasi Prototype
   Klien akan mengevaluasi prototype yang dibuat dan digunakan untuk memperjelas kebutuhan software.

   * Mengkodekan system
  Dalam tahap ini prototyping yang sudah disepakati diterjemahkan ke dalam bahasa pemrograman yang sesuai
  
  * Menguji system
  Setelah sistem sudah menjadi suatu perangkat lunak yang siap pakai, harus dites dahulu sebelum digunakan. Pengujian ini dilakukan dengan White Box, Black Box, Basis Path, pengujian arsitektur dan lain-lain.

  * Evaluasi Sistem
  Pelanggan mengevaluasi apakah sistem yang sudah jadi sudah sesuai dengan yang diharapkan . Jika sudah, maka langkah ketujuh dilakukan, jika belum maka mengulangi langkah 4 dan 5.

  * Menggunakan system
  Perangkat lunak yang telah diuji dan diterima pelanggan siap untuk digunakan

## Extreme Programming Dan Agile

Extreme Programming (XP) merupakan salah satu metode pengembangan software yang termasuk dalam Agile Software Development. XP menggunakan pendekatan object-oriented.

Dalam XP, terdapat 5 nilai yang menjadi pondasi yaitu communication, simplicity, feedback, courage, dan respect. Komunikasi yang efektif antara pengembang perangkat lunak dan pihak-pihak yang terlibat sangatlah penting. Dalam XP, desain dijadikan kebutuhan intermediate. Desain dibuat sesederhana mungkin agar mudah mengimplementasikan code. Disini dapat terjadi perubahan struktur desain atau perubahan source code tanpa mengubah fungsi utamanya (refactoring). Feedback akan diberikan saat peningkatan dan pengimplementasian perangkat lunak.

## Cara Kerja Extreme Programming :
* Perencanaan XP: pengumpulan user stories dari klien yang klien tetapkan prioritasnya. Setiap story ditetapkan harga dan lama pembangunan, jika terlalu besar, story dapat dipecah menjadi beberapa story yang lebih kecil. Periksa dan pertimbangkan resiko
* Desain XP berprinsip: sederhana memanfaatkan kartu CRC (Class-Responsibility-Collaborator) untuk identifikasi dan mengatur class-class di konsep OO. Jika temui kesulitan, prototype dibangun (ini namanya spike solution). Lakukan refactoring, yaitu mengembangkan desain dari program setelah ditulis.
* Pengkodean XP: siapkan unit test sebelum pengkodean dipakai sebagai fokus pemrogram untuk membuat program. Pair programming dilakukan untuk real time program solving dan real time quality assurance
* Pengujian XP: menggunakan unit test yang dipersiapkan sebelum pengkodean

## Scrum Model

Scrum Pada dasarnya merupakan salah satu komponen dari metodologi pengembangan sistem Agile . Akhir-akhir ini scrum mulai marak di implemntasikan di perusahaan IT di Indonesia, dikarenakan maraknya perusahaan IT mengimplementasikan agile development. Scrum menguraikan proses untuk mengidentifikasi dan katalogisasi pekerjaan yang perlu dilakukan, memprioritaskan yang bekerja dengan berkomunikasi dengan pelanggan atau wakil pelanggan, dan pelaksanaan yang bekerja menggunakan rilis iterative dan memiliki tujuan utama untuk mendapatkan perkiraan berapa lama development akan dilakukan.
Scrum merupakan suatu kerangka kerja. Jadi, bukannya menyediakan deskripsi rinci tentang bagaimana segala sesuatu yang harus dilakukan pada proyek seperti diserahkan kepada tim pengembangan perangkat lunak pada umumnya. Hal ini dilakukan supaya tim akan tahu bagaimana cara terbaik untuk memecahkan masalah
Element-Element dalam Scrum

Ada 3 elemen organisasi utama pada scrum yaitu product owner, Scrum master, dan the Scrum team.
* Product Owner mewakili bisnis, pelanggan atau pengguna dan memandu tim ke arah pegembangan produk yang tepat.
*  Scrum Master dapat dianggap sebagai pemersatu bagi product owner dan scrum team (developer, QA, technical wirter dll), membantu anggota tim menggunakan kerangka Scrum untuk menyelesaikan suatu project berdasarkan timeline yang ditentukan di awal.
*  Scrum Team merupakan grup pengembang kecil biasanya terdiri dari 5-9 orang. Untuk projek yang sangat besar, pekerjaan biasanya dibagi dan didelegasikan ke grup-grup kecil
Scrum tepat digunakan saat kondisi:
*  Keperluan berubah dengan cepat
* Tim programmer sedikit, yaitu 5-9 orang
