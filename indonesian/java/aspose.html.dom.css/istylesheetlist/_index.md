---
title: "Antarmuka IStyleSheetList"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.css.IStyleSheetList interface. Antarmuka StyleSheetList mewakili daftar objek CSSStyleSheet. Sebuah instance dari objek ini dapat dikembalikan oleh Document.styleSheets."
type: docs

url: /id/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

Antarmuka StyleSheetList mewakili daftar objek [`CSSStyleSheet`](../icssstylesheet/). Sebuah instance dari objek ini dapat dikembalikan oleh [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Indeks properti yang didukung oleh objek adalah angka dalam rentang nol hingga satu kurang dari jumlah lembar gaya CSS yang direpresentasikan oleh koleksi. Jika tidak ada lembar gaya CSS seperti itu, maka tidak ada indeks properti yang didukung.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) Metode item(index) harus mengembalikan [`CSS style sheet`](../icssstylesheet/) ke‑index dalam koleksi. Jika tidak ada objek ke‑index dalam koleksi, maka metode harus mengembalikan null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) Atribut length harus mengembalikan jumlah lembar gaya CSS yang direpresentasikan oleh koleksi. Rentang indeks stylesheet anak yang valid adalah 0 hingga length‑1 termasuk. |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Lihat Juga

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
