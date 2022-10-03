# Merge-Sort

## [16,21,11,8,12,22] Dizisinin sort turune gore asamalarını yazınız.

Merge sort isleminde dizide ki elemanlar ikiye bolunur ve her biri kendi icerisinde siralanir.
Bir eleman kalincaya kadar.

- [16,21,11,8,12,22]
- [16,21,11] [8,12,22]
- [16,21] [11] [8] [12,22]
- [16] [21] [11] [8] [12] [22]

Siraliyarak birlestiriyoruz.

* [11,16,21] [8,12,22]
* [8,11,12,16,21,22]

Islemlerin sonucunda sirali bir dizi elde etmis olduk.

 ## Big-O gosterimi 

 Her seferinde yariya indirerek islem yapiyoruz ve butun dizi icerisinde bu islemleri gerceklestirdigimiz icin **O(nlogn)** seklinde gösterilerbilir.







 