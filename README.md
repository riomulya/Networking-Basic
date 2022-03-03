# <h1>Networking-Basic</h1>

# Tugas Networking Basic

### Tugas 1

### Silahkan jawab pertanyaan-pertanyaan berikut :

1.  OSI memiliki kepanjangan dari ?
2.  Bilangan 11011001 merupakan contoh bentuk dari bilangan ?
3.  Bentuk desimal dari 11011001 adalah ?
4.  Menjelaskan spesifikasi mekanis, kabel dan fungsional guna menangani data jaringan merupakan proses pada layer ?
5.  Bilangan 3f dan 8a merupakan contoh bentuk dari bilangan ?

### Jawab :

1. Kepanjangan dari OSI adalah Open Systems Interconnection
2. Bentuk dari bilangan biner
3. 1 + 0 + 0 + 8 + 16 + 0 + 64 + 128 = 217
4. Dari Physical Layer
5. Contoh dari bilangan Hexadecimal
<hr>

### Tugas 2

### Silahkan jawab pertanyaan-pertanyaan berikut :

1.  Oktet pertama yang diawali dengan 128 hingga 191 adalah merupakan pembagian kelas ?
2.  Subnet Mask dari CIDR /28 adalah ?
3.  IP Address 127.0.0.1 merupakan bentuk dari ?
4.  CIDR dari Subnet Mask 255.255.0.0 adalah ?
5.  Bagaimana penulisan Subnet Mask dari 192.168.20.20/22 ?

### Jawab :

1.  merupakan kelas b
2.  255.255.255.240
3.  merupakan sebuah loopback address untuk mengakses localhost di dalam komputer
4.  CIDR /16
5.  Decimal : 255.255.252.0 dan Biner : 11111111 11111111 11111100 00000000
<hr>

### Tugas 3

### Silahkan jawab pertanyaan-pertanyaan berikut :

1. Unicast adalah ?
2. Multicast adalah ?
3. White-orange, Orange, White-green, Blue, White-blue, Green, White-brown, Brown merupakan tipe penyusunan pin kabel RJ-45 berjenis ?
4. Nama/jenis kabel berikut adalah : <br><br><hr>
<img src="img/kabel-rj-11.png"/>
<hr>
5. Nama/jenis kabel berikut adalah :<br><br><hr>
<img src="img/kabel-rp-tnc.png"/>
<hr>

### Jawab :

1. Unicast adalah metode pengiriman dari 1 jaringan ke satu jaringan
   atau di sebut dengan (one to one)
2. Multicast adalah metode pengiriman dari 1 atau banyak ke banyak jaringan
   atau (one to many) dan bisa juga (many to many)
3. Berjenis T-568B
4. Itu adalah kabel RJ 11 atau kabel buat telepon
5. Kabel RP-TNC
<hr>

### Tugas 4

Silahkan lakukan monitoring trafik jaringan anda, dan silahkan disesuaikan apabila menggunakan koneksi Wi-Fi atau Ethernet, dan lakukan beberapa langkah berikut :

1. Buka setidaknya > 2 website saat monitoring trafik menggunakan wireshark dilakukan.
2. Amati pada bagian IP Source ke IP Destination dan Protokol apa yang digunakan.
3. Silahkan kirim ke tim pengajar file hasil monitoring trafik wireshark anda.

### Jawab :

<br>
<img src="img/1wireshark.png"/>
<br>
<img src="img/2wireshark.png"/>

<hr>

### Tugas 5

Silahkan jawab pertanyaan-pertanyaan berikut :

1.  Video dan Audio Streaming merupakan penggunaan protokol ?
2.  Benar atau salah bahwa protokol UDP memiliki kecepatan lebih rendah daripada protokol TCP ?
3.  Benar atau salah bahwa DHCP memiliki fungsi untuk merubah IP Address kedalam bentuk Domain (cth: google.com) ?
4.  DNS (Domain Name Server) adalah ?
5.  Gambar berikut merupakan contoh dari penggunaan protokol ? : <br>

<img src="img/tcp.jpeg">

### Jawab :

1.  Video dan Audio Streaming menggunakan protocol UDP agar cepat saat Streaming
2.  iya benar karena UDP tidak perlu adanya balasan dari server dan sangat cepat
3.  Salah karena fungsi DHCP hanya untuk memberi dekstop sebuah ip address,
    yang merubah ip address menjadi domain adalah fungsi dari DNS
4.  sebuah protocol yang dimana dapat merubah url menjadi ip address
5.  gambar tersebut merupakan protocol UTP karena mendapat balasan dari server setelah sampai.

<hr>

### Tugas 6

<br>
<img src="img/cthtgs6.png"><br>
<p>Silahkah konfigurasikan ke VLAN dan sesuaikan jaringan yang anda buat seperti topologi diatas, dengan ketentuan :<br>
a. Network yang digunakan : 192.168.50.xx /24 <br>
b. Warna orange merupakan jaringan VLAN : Gedung-A<br>
c. Warna kuning merupakan jaringan VLAN : Gedung-B<br>
d. Warna biru merupakan jaringan VLAN : Gedung-C<br>
e. Warna hijau merupakan jaringan VLAN : Gedung-D<br>
f. Masing-masing komputer hanya bisa melakukan koneksi di dalam gedung masing-masing<p>

### Jawab :

<img src="img/tugas6-cisco.png">
<hr>

### Tugas 7

<img src="img/tugas7contoh.png">
1. Silahkah konfigurasikan ketiga kota tersebut kedalam Dinamic Routing dengan mendownload file ini, dengan ketentuan :<br>
Network KOTA - A menggunakan : 192.168.20.xx /24<br>
Network KOTA - B menggunakan : 192.168.40.xx /24<br>
Network KOTA - C menggunakan : 192.168.60.xx /24<br>

### Jawab :

1. <img src="img/tugas7-dynamicRouting.png"> 
      <p><a href="file/tugas7.pkt">Ini Hasilnya</a></p>
   <hr>

### Tugas 9

### Silahkan jawab pertanyaan-pertanyaan berikut :

1. Cara untuk membagi bandwith kepada user-user tertentu dengan cara memperioritaskan koneksi
   daripada user lain adalah dengan cara metode ?
2. Jitter adalah ?
3. Pada QOS, suatu parameter yang menggambarkan suatu kondisi hilangnya paket pada saat sampai tujuan adalah pengertian dari ?
4. Ipv6 dengan alamat 0000:0000:0000:0000:0000:0000:0000:0001 apabila dipendekkan akan menjadi ?
5. Benar atau salah bahwa ipv6 memiliki panjang sebesar 126-bit ?

### Jawab :

1. Cara Membagi bandwith dengan metode : Priority
2. jitter adalah variasi jaringan yang sampai, atau Jitter adalah ukuran variabilitas dalam ping seiring waktu
3. Pengertian dari Packet loss
4. Menjadi -> ::1
5. salah yang benar adalah berukuran 128-bit

<hr>
### Tugas 10

### Silahkan jawab pertanyaan-pertanyaan berikut :

1. Salah satu fungsi mengapa menggunakan VPN adalah karena adanya Confidentially, merupakan penjelasan dari ?
2. Benar atau salah bahwa HTTPS dan SFTP merupakan contoh protokol yang mengirimkan data secara clear text ?
3. Benar atau salah bahwa Symetric Algorithm menggunakan kunci yang sama untuk enkripsi dan dekripsi ?

### Jawab :

1. Kerahasisaan Data (Confidentiality)
   Penggunaan VPN dapat menjaga kerahasiaan data dan informasi milik pengguna agar tidak digunakan orang lain
   sembarangan. Saat ini menggunakan jaringan yang bersifat publik bisa dibilang cukup berbahaya, apalagi untuk
   bisnis-bisnis besar misalnya pada perusahaan jasa konsultan atau asuransi yang rentan dengan informasi-informasi
   penting. Sehingga dengan menggunakan VPN maka bisa mengamankan keluar masuknya data melalui metode enkripsi.
2. Salah
3. Iya Benar
