---
title: "ICSS2Properties.TextShadow"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Properti ini menerima daftar efek bayangan yang dipisahkan koma untuk diterapkan pada teks elemen. Efek bayangan diterapkan dalam urutan yang ditentukan dan dapat menumpuk satu sama lain tetapi tidak pernah menutupi teks itu sendiri. Efek bayangan tidak mengubah ukuran kotak tetapi dapat melampaui batasnya. Tingkat tumpukan efek bayangan sama dengan elemen itu sendiri."
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Properti ini menerima daftar efek bayangan yang dipisahkan koma untuk diterapkan pada teks elemen. Efek bayangan diterapkan dalam urutan yang ditentukan dan dapat menumpuk satu sama lain, tetapi tidak pernah menutupi teks itu sendiri. Efek bayangan tidak mengubah ukuran kotak, tetapi dapat melampaui batasnya. [Tingkat tumpukan](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) efek bayangan sama dengan elemen itu sendiri.

Setiap efek bayangan harus menentukan offset bayangan dan dapat secara opsional menentukan radius blur serta warna bayangan.

Offset bayangan ditentukan dengan dua nilai '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' yang menunjukkan jarak dari teks. Nilai panjang pertama menentukan jarak horizontal ke kanan teks. Nilai panjang horizontal negatif menempatkan bayangan di sebelah kiri teks. Nilai panjang kedua menentukan jarak vertikal di bawah teks. Nilai panjang vertikal negatif menempatkan bayangan di atas teks.

Radius blur dapat secara opsional ditentukan setelah offset bayangan. Radius blur adalah nilai panjang yang menunjukkan batas efek blur. Algoritma tepat untuk menghitung efek blur tidak ditentukan.

Nilai warna dapat secara opsional ditentukan sebelum atau sesudah nilai panjang efek bayangan. Nilai warna akan digunakan sebagai dasar efek bayangan. Jika tidak ada warna yang ditentukan, nilai properti ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) akan digunakan sebagai gantinya.

```java
public String TextShadow { get; set; }
```

### Nilai Kembali

properti text-shadow

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
