# Jarkom-Modul-1-F03-2023
### Anggota Kelompok Jarkom D27:
- Abyan Zhafran Trisnanto - 5025211218
- Akhmad Mustofa Solikin - 5025211230

## Soal 1
### Soal

User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.
Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut? 
Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut? 
Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

### Penyelesaian
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)

## Soal 2
### Soal
Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!
### Penyelesaian
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)

## Soal 3
### Soal
Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:
Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702?
Protokol layer transport apa yang digunakan?
### Penyelesaian
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)


## Soal 4
### Soal
Berapa nilai checksum yang didapat dari header pada paket nomor 130?
### Penyelesaian
![alt text](?raw=true)
![alt text](?raw=true)



## Soal 5
### Soal
Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.
Berapa banyak packet yang berhasil di capture dari file pcap tersebut?
Port berapakah pada server yang digunakan untuk service SMTP?
Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP?

### Penyelesaian


## Soal 6
### Soal
Seorang anak bernama Udin Berteman dengan SlameT yang merupakan seorang penggemar film detektif. sebagai teman yang baik, Ia selalu mengajak slamet untuk bermain valoranT bersama. suatu malam, terjadi sebuah hal yang tak terdUga. ketika udin mereka membuka game tersebut, laptop udin menunjukkan sebuah field text dan Sebuah kode Invalid bertuliskan "server SOURCE ADDRESS 7812 is invalid". ketika ditelusuri di google, hasil pencarian hanya menampilkan a1 e5 u21. jiwa detektif slamet pun bergejolak. bantulah udin dan slamet untuk menemukan solusi kode error tersebut.
### Penyelesaian


## Soal 7
### Soal
Berapa jumlah packet yang menuju IP 184.87.193.88?
### Penyelesaian
![alt text](?raw=true)
![alt text](?raw=true)

## Soal 8
### Soal
Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)
### Penyelesaian
Memerlukan kueri filter yang menyaring paket dengan tujuan port 80.Karena berkaitan dengan port, kami menggunakan TCP dan UDP, kemudian karena disebutkan port 80 maka kueri filter yang sesuai adalah [tcp.dstport == 80 || udp.dstport == 80]
![alt text](?raw=true)

## Soal 9
### Soal
Berikan kueri filter sehingga wireshark hanya mengambil paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34!
### Penyelesaian
Memerlukan queri filter untuk mengabil paket yang berasal dari alamat 10.51.40.1 dan tidak menuju alamat 10.39.55.34. Karena berkaitan dengan alamata, maka kami menggunakan (ip), kemudian menggunakan and(&&) untuk menyatukan kondisi yang dibutuhkan. Sehingga kueri yang sesuai adalah [ip.src == 10.51.40.1 && ip.dst != 10.39.55.34]
![alt text](?raw=true)

## Soal 10
### Soal
Sebutkan kredensial yang benar ketika user mencoba login menggunakan Telnet
### Penyelesaian
![alt text](?raw=true)
![alt text](?raw=true)
![alt text](?raw=true)

