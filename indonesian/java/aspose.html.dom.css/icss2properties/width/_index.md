---
title: "ICSS2Properties.Width"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Properti ini menentukan lebar konten kotak yang dihasilkan oleh elemen level-blok dan elemen yang diganti."
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Properti ini menentukan [lebar konten](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) dari kotak yang dihasilkan oleh elemen level-blok dan elemen [diganti](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element).

Properti ini tidak berlaku untuk elemen [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) yang tidak diganti. Lebar kotak elemen inline yang tidak diganti adalah lebar konten yang dirender di dalamnya (sebelum ada offset relatif anak). Ingat bahwa kotak inline mengalir ke [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). Lebar kotak baris diberikan oleh [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) mereka, tetapi dapat dipersingkat oleh keberadaan [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

Lebar kotak elemen yang diganti adalah [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) dan dapat diskalakan oleh agen pengguna jika nilai properti ini berbeda dari 'auto'.

Nilai memiliki arti berikut:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Menentukan lebar tetap.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Menentukan lebar dalam persentase. Persentase dihitung relatif terhadap lebar [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - Lebar tergantung pada nilai properti lain. Lihat bagian di bawah.Catatan: Nilai negatif untuk ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) tidak sah.

```java
public String Width { get; set; }
```

### Nilai Kembali

properti lebar

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
