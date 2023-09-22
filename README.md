# Jarkom-Modul-1-F03-2023
  Abyan Zhafran Trisnanto / 5025211218
  
  Akhmad Mustofa Solikin / 5025211230

## Penjelasan jawaban
1. (Penjelasan)
2. (Penjelasan)
3. (Penjelasan)
4. (Penjelasan)
5. (Penjelasan)
6. (Penjelasan)
7. (Penjelasan)
8. Memerlukan kueri filter yang menyaring paket dengan tujuan port 80.Karena berkaitan dengan port, kami menggunakan TCP dan UDP, kemudian karena disebutkan port 80 maka kueri filter yang sesuai adalah [tcp.dstport == 80 || udp.dstport == 80]
9. Memerlukan queri filter untuk mengabil paket yang berasal dari alamat 10.51.40.1 dan tidak menuju alamat 10.39.55.34. Karena berkaitan dengan alamata, maka kami menggunakan (ip), kemudian menggunakan and(&&) untuk menyatukan kondisi yang dibutuhkan. Sehingga kueri yang sesuai adalah [ip.src == 10.51.40.1 && ip.dst != 10.39.55.34]
10. (Penjelasan)
