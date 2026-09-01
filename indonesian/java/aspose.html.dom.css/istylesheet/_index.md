---
title: "Antarmuka IStyleSheet"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.css.IStyleSheet. Antarmuka StyleSheet adalah antarmuka dasar abstrak untuk semua jenis lembar gaya. Ia mewakili satu lembar gaya yang terkait dengan dokumen terstruktur. Dalam HTML, antarmuka StyleSheet mewakili baik lembar gaya eksternal yang disertakan melalui elemen HTML LINK atau elemen STYLE inline. Dalam XML, antarmuka ini mewakili lembar gaya eksternal yang disertakan melalui instruksi pemrosesan lembar gaya. Lembar gaya CSS selanjutnya akan mengimplementasikan antarmuka yang lebih khusus, yaitu CSSStyleSheet."
type: docs

url: /id/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

Antarmuka StyleSheet adalah antarmuka dasar abstrak untuk semua jenis lembar gaya. Ia mewakili satu lembar gaya yang terkait dengan dokumen terstruktur. Dalam HTML, antarmuka StyleSheet mewakili baik lembar gaya eksternal yang disertakan melalui elemen HTML LINK, atau elemen STYLE inline. Dalam XML, antarmuka ini mewakili lembar gaya eksternal yang disertakan melalui instruksi pemrosesan lembar gaya. Lembar gaya CSS selanjutnya akan mengimplementasikan antarmuka yang lebih khusus, yaitu [`CSSStyleSheet`](../icssstylesheet/).

Lihat juga [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Properti

| Nama | Deskripsi |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) Properti href pada antarmuka `StyleSheet` mengembalikan lokasi lembar gaya. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) Properti media pada antarmuka `StyleSheet` menentukan media tujuan yang dimaksud untuk informasi gaya. Ini adalah objek read-only berbentuk array seperti [`MediaList`](../imedialist/) dan dapat dihapus dengan deleteMedium() serta ditambahkan dengan appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Node yang mengaitkan lembar gaya ini dengan dokumen. Untuk HTML, ini mungkin elemen LINK atau STYLE yang bersangkutan. Untuk XML, ini mungkin instruksi pemrosesan penghubung. Untuk lembar gaya yang disertakan oleh lembar gaya lain, nilai atribut ini adalah null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Untuk bahasa lembar gaya yang mendukung konsep inklusi lembar gaya, atribut ini mewakili lembar gaya yang menyertakan, jika ada. Jika lembar gaya merupakan lembar gaya tingkat atas, atau bahasa lembar gaya tidak mendukung inklusi, nilai atribut ini adalah null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) Properti title pada antarmuka `StyleSheet` mengembalikan judul penasehat dari lembar gaya saat ini. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Ini menentukan bahasa lembar gaya untuk lembar gaya ini. Bahasa lembar gaya ditentukan sebagai tipe konten (misalnya "text/css"). |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Lihat Juga

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
