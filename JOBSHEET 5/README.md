# JOBSHEET 5
# PEMROGRAMAN DASAR NODE-RED
# ABSTRAK	:
<p align="justify">Dalam pembahasan tentang pemrograman dasar dengan Node-RED, terungkap platform visual programming yang mempermudah pengembangan alur kerja Internet of Things (IoT). Fokusnya adalah pada pemahaman dasar pemrograman melalui Node-RED untuk menciptakan alur kerja yang efisien. Dalam eksplorasi ini, dipaparkan konsep-konsep pemrograman visual, implementasi logika dasar, serta penggunaan berbagai node atau blok pembangun dalam Node-RED. Dengan pendekatan yang praktis, pembaca dapat memahami langkah-langkah dasar untuk menciptakan alur kerja yang responsif dan efektif menggunakan Node-RED untuk mendukung proyek-proyek IoT.

**TUJUAN PADA JOBSHEET INI,** antara lain	:
1.	Memahami dasar pemrograman pada Node-Red.
2.	Membuat application server sederhana menggunakan Node-Red.
# ALAT DAN BAHAN	:
**Alat dan bahan** yang digunakan dalam jobsheet ini, antara lain:
1.	ESP32 
2.	Server Node-Red
3.	Breadboard
4.	Kable jumper
5.	Sensor DHT
6.	LED
7.	Resistor 330
8.	Resistor 1K

## A.	Basic Flow
### a.	Langkah Kerja
1.	Pastikan perangkat komputer terpasang Node-red
2.	Buatlah Basic Flow seperti pada gambar berikut
![gambar basic flow programming](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/b0957908-60c1-4673-932a-9e5735cf72b3)

4.	Double klik pada node input, kemudian konfigurasi seperti pada gambar di bawah
![gambar konfigurasi inject](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/72b02e15-de78-49ec-8e0d-e827962ccf37)

6.	Lakukan hal yang  sama seperti pada langkah 3 unutk node output / debug node seperti gambar berikut
![gambar konfigurasi debug](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/fc6945af-ef71-429e-930d-1eb54e3edc20)

8.	Klik tombol “Deploy” yang terletak pada pojok kanan atas UI untuk menjalankan program
### b.	Hasil dan Pembahasan
<img width="437" alt="A  Basic Flow" src="https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/cbd73bac-46e2-4150-bb01-3a63ba75fc2d">

## B.	Menggunakan Function Node
### a.	Langkah Kerja
1.	Buatlah flow fungsi output Tunggal seperti gambar berikut ini
![flow fungsi output tunggal](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/9611851b-2500-41ca-ac21-41e38328e36d)

3.	Konfigurasi node input1. Isikan payload dengan “Hello World”, dan topik berupa “test1”
<img width="416" alt="B 1 Flow fungsi output tunggal (input1)" src="https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/54ee83d2-6977-40d0-88a5-16c4ac17423a">

<img width="379" alt="B 1 Flow fungsi output tunggal (fungsi2)" src="https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/bdbf7d4c-3b25-4123-9331-b9b88452460b">

<img width="485" alt="B 1 Flow fungsi output tunggal (fungsi1)" src="https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/9ac072a7-0048-46b8-90f5-40fdde2971ec">


5.	Deploy program 
6.	Buatlah flow fungsi output berganda yang berfungsi memisahkan pesan seperti gambar dibawah ini
![gambar flow fungsi output berganda](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/48c7a20c-9637-4155-aeb5-091515158615)

8.	Konfigurasi node input2. Isikan payload dengan “Expeliarmus”, dan topik berupa “test2”
9.	Konfigurasi node fungsi seperti gambar dibawah ini
10.	Deploy program 

### b.	Hasil dan Pembahasan
<img width="549" alt="B 1 Flow fungsi output tunggal" src="https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/b463565d-d6ea-4805-a9c4-9b051be263f0">

## C.	Menggunakan Switch Node
### a.	Langkah Kerja
1.	Buatlah flow seperti pada gambar dibawah ini
![gambar flow switch node](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/1e341406-2bf7-4486-bbbf-82a2e0599334)

3.	Konfigurasi Input/Inject Node. Isikan Payload pada Inject Node 1 dengan angka 28. Kemudian pada Inject Node 2, isikan Payload dengan angka 27
4.	Konfigurasi Switch Node seperti gambar dibawah ini
![gambar koonfigurasi switch node](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/d997b84f-44c1-413e-a918-3f81b945928b)

6.	Deploy flow

### b.	Hasil dan Pembahasan

## D.	Menggunakan JSON Parsing
### a.	Langkah Kerja
1.	Buatlah flow seperti gambar dibawah ini
![gambar flow json parser](https://github.com/maratumaritha/Laporan-Embedded/assets/151802682/757c0797-d0c2-49ed-ad23-40797cb28a34)

3.	Konfigurasikan Inject Node, JSON Parser Node, dan Function Node seperti gambar dibawah ini

5.	Deploy flow

### b.	Hasil dan Pembahasan
