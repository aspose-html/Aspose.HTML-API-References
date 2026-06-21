---
title: "Antarmuka ICSSRuleList"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.css.ICSSRuleList. CSSRuleList merepresentasikan koleksi terurut dari objek CSSRule yang hanya-baca."
type: docs

url: /id/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList merepresentasikan koleksi terurut dari objek [`CSSRule`](../icssrule/) yang hanya-baca.

Meskipun objek CSSRuleList hanya-baca, dan tidak dapat dimodifikasi secara langsung, objek ini dianggap hidup, karena kontennya dapat berubah seiring waktu.

Untuk mengedit aturan dasar yang dikembalikan oleh objek [`CSSRule`](../icssrule/), gunakan CSSStyleSheet.insertRule() dan CSSStyleSheet.deleteRule(), yang merupakan metode dari [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Digunakan untuk mengambil sebuah aturan CSS dengan metode item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Urutan dalam koleksi ini mewakili urutan aturan dalam lembar gaya CSS. Jika indeks lebih besar atau sama dengan jumlah aturan dalam daftar, ini mengembalikan null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) Properti length dari antarmuka `CSSRuleList` mengembalikan jumlah objek [`CSSRule`](../icssrule/) dalam daftar. |

### Lihat Juga

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
