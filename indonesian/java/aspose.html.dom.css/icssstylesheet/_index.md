---
title: "Antarmuka ICSSStyleSheet"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.css.ICSSStyleSheet. Antarmuka CSSStyleSheet mewakili satu lembar gaya CSS dan memungkinkan Anda memeriksa serta memodifikasi daftar aturan yang terdapat dalam lembar gaya. Ia mewarisi properti dan metode dari induknya IStyleSheet."
type: docs

url: /id/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Antarmuka CSSStyleSheet mewakili satu lembar gaya CSS, dan memungkinkan Anda memeriksa serta memodifikasi daftar aturan yang terdapat dalam lembar gaya. Ia mewarisi properti dan metode dari induknya, [`IStyleSheet`](../istylesheet/).

Sebuah lembar gaya terdiri dari kumpulan objek [`ICSSRule`](../icssrule/) yang mewakili setiap aturan dalam lembar gaya. Aturan-aturan tersebut berada dalam sebuah [`ICSSRuleList`](../icssrulelist/), yang dapat diperoleh dari properti cssRules lembar gaya.

Sebagai contoh, satu aturan dapat berupa objek [`ICSSStyleRule`](../icssstylerule/) yang berisi gaya seperti

```java
h1, h2 {   font-size: 16pt; }
```

Aturan lain dapat berupa at-rule seperti @import atau @media, dan seterusnya.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) Properti read-only CSSStyleSheet cssRules mengembalikan sebuah [`CSSRuleList`](../icssrulelist/) yang hidup yang menyediakan daftar real-time, terkini dari setiap aturan CSS yang membentuk lembar gaya. Setiap item dalam daftar adalah sebuah [`CSSRule`](../icssrule/) yang mendefinisikan satu aturan. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) Properti read-only CSSStyleSheet ownerRule mengembalikan [`CSSImportRule`](../icssimportrule/) yang sesuai dengan at-rule @import yang mengimpor lembar gaya ke dalam dokumen. Jika lembar gaya tidak diimpor ke dalam dokumen menggunakan @import, nilai yang dikembalikan adalah null. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Metode `CSSStyleSheet` deleteRule() menghapus sebuah aturan dari objek lembar gaya. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | Metode CSSStyleSheet.insertRule() menyisipkan aturan CSS baru ke dalam lembar gaya saat ini, dengan beberapa batasan. |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Lihat Juga

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
