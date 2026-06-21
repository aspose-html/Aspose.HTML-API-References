---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Nilai untuk properti ini memiliki makna berikut"
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Nilai untuk properti ini memiliki makna berikut:

normal - Elemen tidak membuka tingkat penyematan tambahan terkait algoritma bidirectional. Untuk elemen tingkat inline, penataan ulang implisit bekerja melintasi batas elemen. embed - Jika elemen tingkat inline, nilai ini membuka tingkat penyematan tambahan terkait algoritma bidirectional. Arah tingkat penyematan ini diberikan oleh properti ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). Di dalam elemen, penataan ulang dilakukan secara implisit. Ini sesuai dengan menambahkan LRE (U+202A; untuk 'direction: ltr') atau RLE (U+202B; untuk 'direction: rtl') di awal elemen dan PDF (U+202C) di akhir elemen. bidi-override - Jika elemen tingkat inline atau elemen tingkat blok yang hanya berisi elemen tingkat inline, ini membuat override. Ini berarti bahwa di dalam elemen, penataan ulang dilakukan secara ketat sesuai urutan berdasarkan properti ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); bagian implisit dari algoritma bidirectional diabaikan. Ini sesuai dengan menambahkan LRO (U+202D; untuk 'direction: ltr') atau RLO (U+202E; untuk 'direction: rtl') di awal elemen dan PDF (U+202C) di akhir elemen.

```java
public String UnicodeBidi { get; set; }
```

### Nilai Kembali

properti unicode-bidi

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
