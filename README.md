# Jarkom_Modul4_Lapres_E5  

---
### 5111840000088 Angelita Titiandes Br. Silalahi  
### 5111840000150 Alberto Sanjaya  

---

## Pengerjaan Soal  
Berikut ini gambar dari jaringan yang terdapat pada soal  
![0](jawaban/SoalShiftModul4.png)  

1. Membuat subnetting dan routing pada Cisco Packet Tracer  
Berikut perhitungan subnetting dari jaringan yang terbentuk dengan menggunakan metode **Classless VLSM**  

Pertama, membagi jaringan pada soal menjadi 13 subnet seperti pada gambar berikut  
![1.a](jawaban/ciscovlsm.JPG)  

Berikutnya untuk pembagian berdasarkan jumlah yang diperlukan dan didapatkan tabel berikut  
Nama | Perlu | Submask  
-----|-------|--------  
A1 | 1001 | /22  
A2 | 101 | /25  
A3 | 2021 | /21  
A4 | 2 | /30  
A5 | 701 | /22  
A6 | 2 | /30  
A7 | 13 | /28  
A8 | 502 | /23  
A9 | 2 | /30  
A10 | 521 | /22  
A11 | 2 | /30  
A12 | 252 | /24  
A13 | 721 | /22  
Total | 5841 | /19  

Untuk pembagian IPnya menggunakan tree terbagi menjadi  
![1.b](jawaban/treevlsm1.jpg)  
![1.c](jawaban/treevlsm2.jpg)  

Dan untuk 'server' yaitu dengan menggunakan IP DMZ Kelompok masing-masing yang akan dibentuk dari DMZ ```10.151.71.48/29``` dimana terbagi berdasarkan tree berikut  
![1.d](jawaban/treeserver.jpg)  

sehingga menghasilkan pembagian IP sebagai berikut  
![1.e](jawaban/excel.JPG)  

untuk file **.pkt** terdapat pada 
[CPT File](https://github.com/Alberto0150/Jarkom_Modul4_Lapres_E5/blob/main/jawaban/praktikum%201%20cisco%20vlsm%20fix%20backup%20harusnya%20sudah.pkt)  

Dimana ketika diuji sudah dapat mengirim pesan satu sama lain sesuai dengan uji dari asisten penguji  