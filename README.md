<p align="center">
  Automatic House Gate using Arduino: Ultrasonic Sensor with Servo Motor
</p>

## Tentang Proyek Ini
Membuat Automated Gate dengan Ultrasonic Sensor menggunakan Assembly. 
<br> Dirancang oleh Kelompok B5 untuk Final Project Praktikum Sistem Siber-Fisik.

## Anggota Kelompok
1. Fahrezy H. - `2106731466`
2. Fayza Nirwasita - `2106635700`
3. Ivan Indrastata Ramadhan - `2106706981`
4. Mochammad Dyenta Dwiamtomitara - `2106731245`

## Introduction to the problem and the solution
Masih ingat ketika pertama kali mengunjungi Toll Plaza? Dan melihat mekanisme luar biasa yang digunakan untuk menghentikan kendaraan dan mengumpulkan dana? Kami sedang membuat proyek yang serupa di sini, namun dalam skala mini.

Dalam proyek ini, kami membuat replika persis dari sistem penghentian yang ada di pusat-pusat tol yang dikenal sebagai sistem penghenti. Ide untuk proyek ini terinspirasi dari sistem sebenarnya di tol, di mana kendaraan dihentikan secara otomatis ketika melintas di depan sensor atau ketika tombol diaktifkan.

Dalam kasus kami, kami menggunakan sensor jarak ultrasonik HC-SR04 untuk mendeteksi kendaraan sebagai hambatan, dan kami menggunakan servo mikro untuk mengangkat penghalang. Itulah mekanisme yang terlibat dalam proyek ini. Menggunakan konsep ini, proyek kami mengimplementasikan sistem ini untuk pagar otomatis untuk tempat parkir atau garasi pribadi. Dengan mengimplementasikan Internet of Things ke dalam kegiatan sehari-hari ini, dapat melaksanakan pembukaan pagar otomatis yang efisien dan lebih aman karena pengendara tidak perlu dan turun dari kendaraan untuk membuka pintu secara manual, sedangkan kendaraan ditinggaalkan sementara dan dalam kondisi menyala. Hal ini dapat berisko adanya pencurian kendaraan dengan mudah. Selain itu juga implementasi sistem ini meningkatkan kenyaman, seperti saat kondisi cuaca buruk pengendara tidak perlu kehujanan untuk membuka gerbang.

## Hardware design and implementaion details 
Komponen hardware yang digunakan dalam proyek di antaranya adalah Arduino UNO, sensor ultra sonik HC-SR04, servo motor untuk menggerakkan gerbang secara otomatis, yang diintegrasikan dengan kode program dalam bentuk bahasa Assembly. Sedangkan dalam implementasikan pertama membangun rangkaian hardware secara protype soft-ware based, yaitu Proteus dan website online Wokwi.com untuk melakukan simulasi. 

## Software implementaion details 
Kode program untuk mengatur arduino dalam melaksanakan sistem otomasi gerbang untuk parkir. Di mana gerbang tersebut akan terbuka dengan sensor benda yang ada didepannya. Kode yang ada di github merupakan contoh program untuk mengontrol sebuah servo motor dan mengukur jarak menggunakan sensor ultrasonik.
Hasil rangkaian dengan kode akan mendeteksi objek penghalang (mobil) yang ditangkap oleh sensor ultrasonik HC-SR04 yang mengukur jarak objek tersebut. Kemudian jika jarak objek sangat dekat (<10 cm) menandakan objek itu mendekat ke gate, sehingga servo motor akan memutar rotasi sebesar 90 derajat. Saat objek menjauh maka servo motor kembali ke posisi semula. Saat objek mendekat, maka lampu LED menjadi nyala dan pada serial monitor menampilkan angka ‘1’. Sedangkan saat objek menjauh (>10 cm) maka LED akan mati dan pada serial monitor menampilkan angka ‘0’.

## Test results and performance evaluation 

## Conclusion and Future Work  
Proyek Automatic House Gate memberikan salah satu solusi dari kebutuhan akan metode yang efisien dan nyaman untuk mengelola tempat parkir. Proyek ini memanfaatkan Internet of Things (IoT) untuk menciptakan sistem gerbang otomatis yang mendeteksi keberadaan kendaraan dan mengatur masuk dan keluarnya kendaraan. Solusi yang diusulkan menggunakan Arduino Uno, Arduino IDE, dan sirkuit elektronik, bersama dengan sensor ultrasonik HC-SR04, untuk mengukur jarak antara sensor dan kendaraan.

Proyek Automatic Turnstile for Car Parking menunjukkan aplikasi praktis teknologi IoT dalam meningkatkan manajemen tempat parkir. Dengan mengotomatiskan sistem gerbang dan mengintegrasikan kemampuan deteksi jarak, solusi ini menawarkan efisiensi, keamanan, dan pengalaman yang tidak merepotkan bagi pengemudi dan operator tempat parkir.



<!-- ## Proteus
![State Diagram](https://drive.google.com/file/d/1YnqgZwbPYb-U-LKxIgehy_YIs6JxD88m/view?usp=share_link) -->
