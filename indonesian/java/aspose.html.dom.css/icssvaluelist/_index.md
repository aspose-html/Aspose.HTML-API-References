---
title: "Antarmuka ICSSValueList"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.css.ICSSValueList. Antarmuka CSSValueList diturunkan dari antarmuka CSSValue dan menyediakan abstraksi dari koleksi terurut nilai CSS."
type: docs

url: /id/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

Antarmuka CSSValueList diturunkan dari antarmuka [`CSSValue`](../cssvalue/) dan menyediakan abstraksi dari koleksi terurut nilai CSS.

Beberapa properti mengizinkan daftar kosong dalam sintaksnya. Dalam kasus tersebut, properti tersebut menggunakan identifier none. Jadi, daftar kosong berarti properti memiliki nilai none.

Item dalam CSSValueList dapat diakses melalui indeks integral, mulai dari 0.

```java
public interface ICSSValueList
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Metode ini digunakan untuk mengambil CSSValue berdasarkan indeks ordinal. Urutan dalam koleksi ini mewakili urutan nilai dalam properti gaya CSS. Jika indeks lebih besar atau sama dengan jumlah nilai dalam daftar, metode ini mengembalikan null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) Properti read-only length pada antarmuka CSSValueList mewakili jumlah CSSValue dalam daftar. Rentang nilai indeks yang valid adalah 0 hingga length-1 termasuk. |

## Catatan

Antarmuka ini merupakan bagian dari upaya membuat CSS Object Model yang bertipe. Upaya ini telah ditinggalkan, dan sebagian besar browser tidak mengimplementasikannya.

Untuk mencapai tujuan Anda, Anda dapat menggunakan:

model [CSS Object Model](https://drafts.csswg.org/cssom/) yang tidak bertipe, didukung secara luas, atau [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects) modern, dukungannya lebih sedikit dan dianggap eksperimental.

### Lihat Juga

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
