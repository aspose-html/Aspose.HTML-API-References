---
title: "Antarmuka ICSSRule"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.css.ICSSRule interface. Antarmuka CSSRule adalah antarmuka dasar abstrak untuk setiap jenis pernyataan CSS. Ini mencakup baik set aturan maupun at-rule. Implementasi diharapkan mempertahankan semua aturan yang ditentukan dalam lembar gaya CSS bahkan jika aturan tersebut tidak dikenali oleh parser. Aturan yang tidak dikenali direpresentasikan menggunakan antarmuka ini."
type: docs

url: /id/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

Antarmuka CSSRule adalah antarmuka dasar abstrak untuk setiap jenis pernyataan CSS. Ini mencakup baik rule set maupun at-rule. Implementasi diharapkan mempertahankan semua aturan yang ditentukan dalam lembar gaya CSS, bahkan jika aturan tersebut tidak dikenali oleh parser. Aturan yang tidak dikenali direpresentasikan menggunakan antarmuka ini.

```java
public interface ICSSRule
```

## Properti

| Nama | Deskripsi |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Jika aturan ini berada di dalam aturan lain (misalnya aturan gaya di dalam blok @media), ini adalah aturan yang menampungnya. Jika aturan ini tidak bersarang di dalam aturan lain, ini mengembalikan null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) Properti parentStyleSheet dari antarmuka `CSSRule` mengembalikan objek [`StyleSheet`](../istylesheet/) di mana aturan saat ini didefinisikan. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Tipe aturan, sebagaimana didefinisikan [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Diharapkan metode casting khusus binding dapat digunakan untuk menurunkan tipe dari sebuah instance antarmuka CSSRule ke antarmuka turunan spesifik yang diimplikasikan oleh tipe tersebut. |

### Lihat Juga

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
