---
title: "ICSS2Properties.Display"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Nilai-nilai properti ini memiliki arti berikut"
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Nilai-nilai properti ini memiliki arti berikut:

block - Nilai ini menyebabkan elemen menghasilkan kotak blok utama. inline - Nilai ini menyebabkan elemen menghasilkan satu atau lebih kotak inline. list-item - Nilai ini menyebabkan elemen (mis., LI dalam HTML) menghasilkan kotak blok utama dan kotak inline list-item. Untuk informasi tentang daftar dan contoh pemformatan daftar, silakan lihat bagian tentang [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker - Nilai ini mendeklarasikan [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) sebelum atau sesudah sebuah kotak menjadi penanda. Nilai ini hanya boleh digunakan dengan pseudo-elemen [:before dan :after](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) yang terpasang pada elemen block-level. Dalam kasus lain, nilai ini diinterpretasikan sebagai 'inline'. Silakan lihat bagian tentang [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) untuk informasi lebih lanjut. none - Nilai ini menyebabkan elemen tidak menghasilkan kotak apa pun dalam [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (yaitu, elemen tidak berpengaruh pada tata letak). Elemen turunan juga tidak menghasilkan kotak apa pun; perilaku ini tidak dapat diubah dengan menetapkan properti ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) pada turunan. Perlu dicatat bahwa display 'none' tidak membuat kotak tak terlihat; ia tidak membuat kotak sama sekali. CSS menyertakan mekanisme yang memungkinkan elemen menghasilkan kotak dalam struktur pemformatan yang memengaruhi pemformatan tetapi tidak terlihat sendiri. Silakan lihat bagian tentang [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) untuk detail. run-in and compact - Nilai-nilai ini membuat kotak block atau inline, tergantung pada konteks. Properti berlaku pada kotak run-in dan compact berdasarkan status akhir mereka (inline-level atau block-level). Misalnya, properti ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) hanya berlaku jika kotak menjadi kotak block. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell, dan table-caption - Nilai-nilai ini menyebabkan elemen berperilaku seperti elemen tabel (dengan batasan yang dijelaskan dalam bab tentang [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Nilai Kembali

properti display

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
