---
title: "ICSS2Properties.Clear"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Properti ini menunjukkan sisi mana dari kotak elemen yang tidak boleh berdekatan dengan kotak mengambang sebelumnya. Mungkin elemen itu sendiri memiliki keturunan mengambang; properti clear tidak berpengaruh pada mereka."
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Properti ini menunjukkan sisi mana dari kotak elemen yang tidak boleh berdekatan dengan kotak mengambang sebelumnya. (Mungkin elemen itu sendiri memiliki keturunan mengambang; properti 'clear' tidak berpengaruh pada mereka.)

Properti ini hanya dapat ditentukan untuk elemen tingkat blok (termasuk mengambang). Untuk kotak kompak dan run-in, properti ini berlaku pada kotak blok akhir tempat kotak kompak atau run-in berada.

Nilai-nilai memiliki arti berikut ketika diterapkan pada kotak blok yang tidak mengambang:

left - Margin atas kotak yang dihasilkan ditambah cukup sehingga tepi batas atas berada di bawah tepi luar bawah dari semua kotak mengambang ke kiri yang dihasilkan oleh elemen sebelumnya dalam dokumen sumber. right - Margin atas kotak yang dihasilkan ditambah cukup sehingga tepi batas atas berada di bawah tepi luar bawah dari semua kotak mengambang ke kanan yang dihasilkan oleh elemen sebelumnya dalam dokumen sumber. both - Kotak yang dihasilkan dipindahkan di bawah semua kotak mengambang dari elemen sebelumnya dalam dokumen sumber. none - Tidak ada batasan pada posisi kotak terhadap float.

```java
public String Clear { get; set; }
```

### Nilai Kembali

properti clear

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
