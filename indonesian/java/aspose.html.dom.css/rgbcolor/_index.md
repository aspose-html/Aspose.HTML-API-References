---
title: "Kelas RGBColor"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.css.RGBColor class. Antarmuka RGBColor digunakan untuk merepresentasikan nilai warna RGB apa pun. Antarmuka ini mencerminkan nilai-nilai dalam properti gaya yang mendasari. Oleh karena itu, modifikasi yang dilakukan pada objek CSSPrimitiveValue mengubah properti gaya."
type: docs

url: /id/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

Antarmuka RGBColor digunakan untuk merepresentasikan nilai warna RGB apa pun. Antarmuka ini mencerminkan nilai-nilai dalam properti gaya yang mendasarinya. Oleh karena itu, modifikasi yang dilakukan pada objek CSSPrimitiveValue mengubah properti gaya.

Warna RGB yang ditentukan tidak dipotong (bahkan jika angkanya berada di luar rentang 0-255 atau 0%-100%). Warna RGB yang dihitung dipotong tergantung pada perangkat.

Bahkan jika lembar gaya hanya dapat berisi integer untuk nilai warna, penyimpanan internal integer ini adalah float, dan dapat digunakan sebagai float dalam gaya yang ditentukan atau yang dihitung.

Nilai persentase warna selalu dapat dikonversi menjadi angka dan sebaliknya.

```java
public class RGBColor : DOMObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Mendapatkan nilai komponen alfa dari struktur Color ini. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Mendapatkan nilai komponen biru dari struktur Color ini. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Mendapatkan nilai komponen hijau dari struktur Color ini. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Mendapatkan nilai komponen merah dari struktur Color ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Mengonversi ke objek warna asli. |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
