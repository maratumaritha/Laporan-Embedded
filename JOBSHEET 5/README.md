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
3.	Double klik pada node input, kemudian konfigurasi seperti pada gambar di bawah
4.	Lakukan hal yang  sama seperti pada langkah 3 unutk node output / debug node seperti gambar berikut
5.	Klik tombol “Deploy” yang terletak pada pojok kanan atas UI untuk menjalankan program
### b.	Hasil dan Pembahasan

## B.	Menggunakan Function Node
### a.	Langkah Kerja
1.	Buatlah flow fungsi output Tunggal seperti gambar berikut ini
2.	Konfigurasi node input1. Isikan payload dengan “Hello World”, dan topik berupa “test1”
3.	Deploy program 
4.	Buatlah flow fungsi output berganda yang berfungsi memisahkan pesan seperti gambar dibawah ini
5.	Konfigurasi node input2. Isikan payload dengan “Expeliarmus”, dan topik berupa “test2”
6.	Konfigurasi node fungsi seperti gambar dibawah ini
7.	Deploy program 

### b.	Hasil dan Pembahasan

## C.	Menggunakan Switch Node
### a.	Langkah Kerja
1.	Buatlah flow seperti pada gambar dibawah ini
2.	Konfigurasi Input/Inject Node. Isikan Payload pada Inject Node 1 dengan angka 28. Kemudian pada Inject Node 2, isikan Payload dengan angka 27
3.	Konfigurasi Switch Node seperti gambar dibawah ini
4.	Deploy flow

### b.	Hasil dan Pembahasan

## D.	Menggunakan JSON Parsing
### a.	Langkah Kerja
1.	Buatlah flow seperti gambar dibawah ini
2.	Konfigurasikan Inject Node, JSON Parser Node, dan Function Node seperti gambar dibawah ini
3.	Deploy flow

### b.	Hasil dan Pembahasan
