---
title: "Antarmuka IMediaList"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.css.IMediaList interface. Antarmuka MediaList menyediakan abstraksi dari koleksi media yang terurut tanpa mendefinisikan atau membatasi bagaimana koleksi ini diimplementasikan. Daftar kosong sama dengan daftar yang berisi medium all"
type: docs

url: /id/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

Antarmuka MediaList menyediakan abstraksi koleksi terurut media, tanpa mendefinisikan atau membatasi cara koleksi ini diimplementasikan. Daftar kosong sama dengan daftar yang berisi medium "all".

Lihat juga [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) Metode item(index) harus mengembalikan serialisasi kueri media dalam koleksi kueri media yang diberikan oleh indeks, atau null, jika indeks lebih besar atau sama dengan jumlah kueri media dalam koleksi kueri media. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) Atribut length harus mengembalikan jumlah kueri media dalam koleksi kueri media. Rentang media yang valid adalah 0 hingga length-1 inklusif. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Sebuah Stringifier yang mengembalikan DOMString yang mewakili MediaList sebagai teks, dan juga memungkinkan Anda mengatur MediaList baru. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Menambahkan medium newMedium ke akhir daftar. Jika newMedium sudah digunakan, ia pertama-tama dihapus. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Menghapus medium yang ditunjuk oleh oldMedium dari daftar. |

## Catatan

Catatan: MediaList adalah daftar hidup; memperbarui daftar menggunakan properti atau metode yang tercantum di bawah ini akan langsung memperbarui perilaku dokumen.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Contoh

Berikut ini akan mencatat ke konsol representasi tekstual dari MediaList lembar gaya pertama yang diterapkan pada dokumen saat ini.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Lihat Juga

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
