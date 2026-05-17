# Gerbang Logika Menggunakan Tinkercad

## Link Tinkercad

## Anggota Kelompok
1.  Nama: Naufal Siswanto  
    NIM: H1H025033  
2.  Nama:  Felix Erza Shandika
     NIM: H1H025034
4.  Nama:  
    NIM:  

## Deskripsi
Project ini merupakan simulasi gerbang logika digital menggunakan platform Tinkercad. Simulasi dilakukan untuk memahami cara kerja gerbang logika dasar menggunakan IC TTL seri 74HC dengan output berupa LED.

## Tujuan
- Memahami konsep dasar gerbang logika digital
- Mengetahui fungsi masing-masing gerbang logika
- Mengimplementasikan gerbang logika pada Tinkercad
- Menguji tabel kebenaran dari setiap gerbang logika

## Software yang Digunakan
- Tinkercad

## Komponen yang Digunakan
- Power Supply DC
- LED
- Resistor 220Ω
- Switch
- IC Gerbang Logika Seri 74HC

## Gerbang Logika yang Digunakan

### 1. AND Gate
Pada rangkaian gerbang AND yang disimulasikan menggunakan Tinkercad, digunakan IC seri 74HC08 yang berbasis teknologi High-speed CMOS (HC) dengan catu daya dari Power Supply sebesar 5V DC. IC seri 74HC dipilih karena memiliki efisiensi daya yang tinggi dan rentang tegangan operasi yang stabil untuk sistem logika digital. Input logika disuplai secara manual melalui DIP Switch nomor 1 dan 2 yang masing-masing dihubungkan ke Pin 1 (Input 1A) dan Pin 2 (Input 1B) pada IC. Pin 14 dihubungkan ke jalur positif VCC (5V) dan Pin 7 dihubungkan ke ground (GND) untuk memberikan daya aktif pada IC. Output dari gerbang AND berada pada Pin 3 (Output 1Y) yang kemudian dihubungkan ke kaki anoda LED melalui sebuah resistor pembatas arus untuk mencegah kerusakan akibat arus berlebih. Secara prinsip kerja, LED atau output hanya akan bernilai 1 (menyala) jika kedua input dari DIP Switch berada pada kondisi 1 (ON), sedangkan jika salah satu atau seluruh input bernilai 0, maka output akan tetap 0 atau LED mati.

### 2. OR Gate
Rangkaian gerbang OR diimplementasikan menggunakan IC 74HC32 pada platform Tinkercad dengan pasokan daya sebesar 5V dari Power Supply DC. Penggunaan IC seri 74HC memastikan kecepatan operasional yang tinggi dengan konsumsi daya yang minimal saat simulasi berjalan. Rangkaian ini memanfaatkan DIP Switch 1 dan 2 sebagai pemberi sinyal input logika yang dialirkan menuju Pin 1 (Input 1A) dan Pin 2 (Input 1B) dari IC 74HC32. Untuk mengaktifkan IC, Pin 14 dipasangkan ke jalur VCC dan Pin 7 disambungkan ke ground. Sinyal keluaran logika diproses melalui Pin 3 (Output 1Y) yang disambungkan secara seri dengan resistor pembatas arus sebelum menuju ke komponen LED. Berdasarkan karakteristik gerbang logika OR, rangkaian ini akan menghasilkan output 1 atau LED menyala selama salah satu atau kedua inputnya berada dalam kondisi ON atau bernilai 1, dan output hanya akan bernilai 0 atau LED mati jika kedua input bernilai 0 atau OFF secara bersamaan. 

### 3. NOT Gate
Pada rangkaian gerbang NOT, digunakan IC inverter seri 74HC04 yang disimulasikan melalui software Tinkercad. Komponen utama yang mendukung rangkaian ini meliputi Power Supply DC 5V sebagai sumber tegangan, satu buah DIP Switch sebagai input tunggal, sebuah resistor, dan satu LED sebagai indikator keluaran. Hubungan pin pada IC dilakukan dengan menyambungkan Pin 14 ke jalur positif VCC dan Pin 7 ke jalur negatif ground agar komponen internal IC aktif. Input dari DIP Switch nomor 1 dihubungkan langsung ke Pin 1 (Input 1A), sementara Pin 2 (Output 1Y) bertindak sebagai keluaran yang disambungkan ke resistor pembatas arus menuju anoda LED. Prinsip kerja dari rangkaian ini adalah sebagai pembalik (inverter), di mana kondisi output pada LED selalu merupakan kebalikan dari kondisi input yang diberikan oleh switch; jika switch bernilai 0 (OFF) maka LED akan menyala (1), dan sebaliknya jika switch bernilai 1 (ON) maka LED akan mati (0). 

### 4. NAND Gate
Rangkaian gerbang NAND dirancang pada Tinkercad dengan menggunakan IC seri 74HC00 yang disuplai oleh tegangan 5V dari Power Supply DC. IC CMOS berkecepatan tinggi ini memerlukan koneksi daya standar, yaitu Pin 14 ke jalur positif VCC dan Pin 7 ke jalur negatif ground. Dua input logika diambil dari DIP Switch 1 dan 2, lalu dihubungkan ke Pin 1 (Input 1A) dan Pin 2 (Input 1B) pada IC. Output gerbang diakses melalui Pin 3 (Output 1Y) yang kemudian dipasangkan resistor pembatas arus untuk mengontrol aliran listrik menuju LED. Gerbang NAND memberikan performa keluaran yang merupakan kebalikan dari gerbang AND. Oleh karena itu, output akan bernilai rendah (0) atau LED mati hanya jika kedua input switch berada pada kondisi tinggi (1 atau ON) secara bersamaan, sedangkan variasi kombinasi input lainnya akan menghasilkan logika 1 yang membuat LED tetap menyala. 

### 5. NOR Gate
Pada rangkaian gerbang NOR yang disimulasikan di Tinkercad, digunakan IC seri 74HC02 dengan dukungan daya 5V dari Power Supply DC. Berbeda dengan IC gerbang logika 2-input standar lainnya, IC 74HC02 memiliki konfigurasi tata letak pin yang terbalik (inverted pinout). Berdasarkan rangkaian, Pin 1 bertindak sebagai Output 1Y yang dihubungkan langsung ke resistor pembatas arus dan LED, sedangkan Pin 2 (Input 1A) dan Pin 3 (Input 1B) bertindak sebagai penerima input logika dari DIP Switch 1 dan 2. Pengondisian daya IC tetap menggunakan standar pabrikan dengan menghubungkan Pin 14 ke VCC dan Pin 7 ke ground. Secara fungsional, gerbang NOR merupakan kebalikan dari gerbang OR, sehingga output hanya akan bernilai 1 atau LED menyala jika seluruh input dari DIP Switch berada pada kondisi 0 atau OFF. Jika salah satu atau kedua switch diubah ke kondisi ON, maka output otomatis bernilai 0 dan LED akan mati. 

### 6. XOR Gate
Rangkaian gerbang XOR (Exclusive-OR) dibangun menggunakan IC seri 74HC86 pada media simulasi Tinkercad dengan tegangan operasional 5V dari Power Supply DC. IC ini diaktifkan dengan menghubungkan Pin 14 ke jalur positif VCC dan Pin 7 ke jalur negatif ground. Input dari DIP Switch 1 dan 2 disalurkan masing-masing ke Pin 1 (Input 1A) dan Pin 2 (Input 1B) pada IC 74HC86. Sinyal keluaran logika diambil dari Pin 3 (Output 1Y) yang dipasang seri dengan resistor pembatas arus menuju komponen LED. Sesuai dengan karakteristik logikanya, gerbang EX-OR ini hanya akan menghasilkan output 1 atau LED menyala jika kedua input switch memiliki kondisi logika yang berbeda atau tidak sama. Sebaliknya, jika kedua input berada pada kondisi yang sama (keduanya bernilai 0 atau keduanya bernilai 1), maka output akan menghasilkan nilai 0 atau LED mati.

### 7. XNOR Gate
Rangkaian gerbang XNOR (Exclusive-NOR) pada simulasi Tinkercad ini dirancang secara modular dengan mengombinasikan dua buah IC, yaitu IC XOR 74HC86 dan IC NOT 74HC04. Kombinasi ini dilakukan karena ketiadaan IC XNOR tunggal bawaan pada komponen dasar platform simulasi. Kedua IC tersebut dtenagai oleh Power Supply DC sebesar 5V dengan masing-masing Pin 14 terhubung ke VCC dan Pin 7 terhubung ke ground. Input dari DIP Switch 1 dan 2 dimasukkan terlebih dahulu ke Pin 1 (Input 1A) dan Pin 2 (Input 1B) pada IC 74HC86. Output awal yang keluar dari Pin 3 IC 74HC86 kemudian dijembatani menggunakan kabel menuju Pin 1 (Input 1A) pada IC NOT 74HC04 untuk dibalikkan kondisi logikanya. Hasil pembalikan akhir dikeluarkan melalui Pin 2 (Output 1Y) IC 74HC04, yang mengalir melewati resistor pembatas arus menuju LED. Karena gerbang EX-NOR merupakan kebalikan dari gerbang EX-OR, output akan bernilai 1 atau LED menyala jika kedua inputnya memiliki kondisi logika yang sama (identik), dan sebaliknya akan menghasilkan logika 0 atau LED mati jika kondisi kedua inputnya berbeda. 

## Langkah Percobaan
1. Membuka Tinkercad melalui browser
2. Membuat project baru pada menu Circuit
3. Menyiapkan komponen yang dibutuhkan
4. Menyusun rangkaian sesuai konfigurasi
5. Mengatur nilai resistor menjadi 220Ω
6. Menjalankan simulasi
7. Mengamati output LED berdasarkan input switch

## Hasil Percobaan
Hasil simulasi menunjukkan bahwa setiap gerbang logika bekerja sesuai dengan tabel kebenaran masing-masing.

## Kesimpulan
Berdasarkan serangkaian proses perancangan, perakitan virtual, dan pengujian empiris yang telah dilaksanakan terhadap berbagai gerbang logika dasar pada platform Tinkercad, dapat disimpulkan bahwa seluruh gerbang logika dasar seperti AND, OR, NOT, NAND, NOR, XOR, dan XNOR berhasil dipahami serta diverifikasi karakteristik logikanya melalui pengamatan indikator LED secara real-time. Setiap perubahan kombinasi input terbukti menghasilkan keluaran sesuai tabel kebenaran dan prinsip Aljabar Boolean. Pengujian terhadap keluarga IC CMOS digital seri 74HC, meliputi 74HC08, 74HC32, 74HC04, 74HC00, 74HC02, dan 74HC86, juga menunjukkan bahwa seluruh komponen mampu bekerja dengan stabil dan menghasilkan level logika HIGH maupun LOW secara akurat sesuai fungsi masing-masing gerbang. Akhirnya manusia menemukan cara membuat lampu kecil menyala dan mati dengan sangat serius, lalu menyebutnya kemajuan teknologi. Dan anehnya, memang benar begitu.  
Selain itu, keterbatasan ketersediaan komponen gerbang XNOR tunggal pada simulator berhasil diatasi melalui rekayasa sirkuit gabungan menggunakan IC XOR 74HC86 dan IC NOT 74HC04. Kombinasi kedua IC tersebut terbukti mampu menghasilkan fungsi logika XNOR dengan baik sehingga dapat digunakan sebagai pendeteksi kesetaraan dua bit biner secara valid. Hal ini menunjukkan bahwa konsep perancangan logika digital tidak hanya bergantung pada komponen tunggal, tetapi juga pada kemampuan analisis dan penyusunan kombinasi rangkaian yang tepat.  
Secara keseluruhan, penggunaan platform laboratorium virtual saat ini menggunakan Tinkercad terbukti sangat efektif sebagai media pembelajaran dan simulasi sistem digital. Platform ini mampu memodelkan interkoneksi kelistrikan DC, konfigurasi pin IC, serta penerapan resistor pull-down dengan aman, praktis, dan presisi tanpa risiko kerusakan komponen fisik. Melalui simulasi ini, proses pembelajaran rangkaian digital menjadi lebih mudah dipahami sekaligus memberikan pengalaman perancangan yang mendekati implementasi nyata.  


