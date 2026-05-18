---
title: "ICSS2Properties.VerticalAlign"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Properti ini memengaruhi posisi vertikal di dalam kotak baris dari kotak-kotak yang dihasilkan oleh elemen tingkat-sebaris. Nilai-nilai berikut hanya memiliki arti sehubungan dengan elemen tingkat-sebaris induk atau dengan elemen tingkat-blok induk jika elemen tersebut menghasilkan kotak sebaris anonim; mereka tidak berpengaruh jika tidak ada induk semacam itu"
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Properti ini memengaruhi posisi vertikal di dalam kotak baris dari kotak-kotak yang dihasilkan oleh elemen tingkat-sebaris. Nilai-nilai berikut hanya memiliki arti sehubungan dengan elemen tingkat-sebaris induk, atau dengan elemen tingkat-blok induk, jika elemen tersebut menghasilkan [anonymous inline boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); mereka tidak berpengaruh jika tidak ada induk semacam itu.

Catatan. Nilai properti ini memiliki arti yang sedikit berbeda dalam konteks tabel. Silakan lihat bagian tentang [table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) untuk detail. baseline - Menyelaraskan garis dasar kotak dengan garis dasar kotak induk. Jika kotak tidak memiliki garis dasar, menyelaraskan bagian bawah kotak dengan garis dasar induk. middle - Menyelaraskan titik tengah vertikal kotak dengan garis dasar kotak induk ditambah setengah tinggi x dari induk. sub - Menurunkan garis dasar kotak ke posisi yang tepat untuk subskrip kotak induk. (Nilai ini tidak memengaruhi ukuran font teks elemen.) super - Menaikkan garis dasar kotak ke posisi yang tepat untuk superskrip kotak induk. (Nilai ini tidak memengaruhi ukuran font teks elemen.) text-top - Menyelaraskan bagian atas kotak dengan bagian atas font elemen induk. text-bottom - Menyelaraskan bagian bawah kotak dengan bagian bawah font elemen induk. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Mengangkat (nilai positif) atau menurunkan (nilai negatif) kotak sebesar jarak ini (persentase dari nilai ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)). Nilai '0%' berarti sama dengan 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Mengangkat (nilai positif) atau menurunkan (nilai negatif) kotak sebesar jarak ini. Nilai '0cm' berarti sama dengan 'baseline'. top - Menyelaraskan bagian atas kotak dengan bagian atas kotak baris. bottom - Menyelaraskan bagian bawah kotak dengan bagian bawah kotak baris.

```java
public String VerticalAlign { get; set; }
```

### Nilai Kembali

properti vertical-align

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
