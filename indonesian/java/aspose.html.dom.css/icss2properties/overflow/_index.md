---
title: "ICSS2Properties.Overflow"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Properti ini menentukan apakah konten elemen tingkat blok dipotong ketika melampaui kotak elemen yang berfungsi sebagai blok kontainer untuk konten. Nilai-nilai memiliki arti sebagai berikut"
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Properti ini menentukan apakah konten elemen tingkat blok dipotong ketika melampaui kotak elemen (yang berfungsi sebagai blok kontainer untuk konten). Nilai-nilai memiliki arti sebagai berikut:

visible - Nilai ini menunjukkan bahwa konten tidak dipotong, yaitu dapat ditampilkan di luar kotak blok.hidden - Nilai ini menunjukkan bahwa konten dipotong dan tidak ada mekanisme pengguliran yang harus disediakan untuk melihat konten di luar wilayah pemotongan; pengguna tidak akan memiliki akses ke konten yang dipotong. Ukuran dan bentuk wilayah pemotongan ditentukan oleh properti ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip).scroll - Nilai ini menunjukkan bahwa konten dipotong dan jika agen pengguna menggunakan mekanisme pengguliran yang terlihat di layar (seperti bilah gulir atau penggeser), mekanisme tersebut harus ditampilkan untuk sebuah kotak baik kontennya dipotong atau tidak. Ini menghindari masalah bilah gulir yang muncul dan menghilang dalam lingkungan dinamis. Ketika nilai ini ditentukan dan media target adalah 'print' atau 'projection', konten yang melimpah harus dicetak.auto - Perilaku nilai 'auto' bergantung pada agen pengguna, tetapi harus menyebabkan mekanisme pengguliran disediakan untuk kotak yang melimpah.

```java
public String Overflow { get; set; }
```

### Nilai Kembali

properti overflow

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
