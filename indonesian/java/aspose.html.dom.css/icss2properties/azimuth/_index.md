---
title: "ICSS2Properties.Azimuth"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Audio spasial adalah properti stilistik penting untuk presentasi audial. Ini menyediakan cara alami untuk membedakan beberapa suara, seperti dalam kehidupan nyata orang jarang semua berdiri di tempat yang sama dalam sebuah ruangan."
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

Audio spasial adalah properti stilistik penting untuk presentasi audial. Ini menyediakan cara alami untuk membedakan beberapa suara, seperti dalam kehidupan nyata (orang jarang semua berdiri di tempat yang sama dalam sebuah ruangan).

```java
public String Azimuth { get; set; }
```

### Nilai Kembali

Properti azimuth

### Property Value

Nilai memiliki arti berikut:

angle - Posisi dijelaskan dalam hal sudut dengan rentang '-360deg' hingga '360deg'. Nilai '0deg' berarti tepat di depan di tengah panggung suara. '90deg' ke kanan, '180deg' ke belakang, dan '270deg' (atau secara setara dan lebih mudah, '-90deg') ke kiri.

left-side - Sama dengan '270deg'. Dengan 'behind', '270deg'.

far-left - Sama dengan '300deg'. Dengan 'behind', '240deg'.

left - Sama dengan '320deg'. Dengan 'behind', '220deg'.

center-left - Sama dengan '340deg'. Dengan 'behind', '200deg'.

center - Sama dengan '0deg'. Dengan 'behind', '180deg'.

center-right - Sama dengan '20deg'. Dengan 'behind', '160deg'.

right - Sama dengan '40deg'. Dengan 'behind', '140deg'.

far-right - Sama dengan '60deg'. Dengan 'behind', '120deg'.

right-side - Sama dengan '90deg'. Dengan 'behind', '90deg'.

leftwards - Memindahkan suara ke kiri, relatif terhadap sudut saat ini. Lebih tepatnya, mengurangi 20 derajat. Aritmetika dilakukan modulo 360 derajat. Perhatikan bahwa 'leftwards' lebih tepat digambarkan sebagai "diputar berlawanan arah jarum jam," karena selalu mengurangi 20 derajat, bahkan jika azimuth yang diwarisi sudah berada di belakang pendengar (dalam hal ini suara sebenarnya tampak bergerak ke kanan).

rightwards - Memindahkan suara ke kanan, relatif terhadap sudut saat ini. Lebih tepatnya, menambah 20 derajat. Lihat 'leftwards' untuk aritmetika.

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
