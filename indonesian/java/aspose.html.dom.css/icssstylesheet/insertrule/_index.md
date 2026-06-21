---
title: "ICSSStyleSheet.InsertRule"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode ICSSStyleSheet. Metode CSSStyleSheet.insertRule menyisipkan aturan CSS baru ke dalam lembar gaya saat ini dengan beberapa batasan"
type: docs

url: /id/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

Metode CSSStyleSheet.insertRule() menyisipkan aturan CSS baru ke dalam lembar gaya saat ini, dengan beberapa pembatasan.

Catatan: Meskipun insertRule() secara eksklusif merupakan metode dari [`CSSStyleSheet`](../), sebenarnya ia menyisipkan aturan ke dalam CSSStyleSheet.cssRules — internal [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aturan | String | String yang berisi aturan yang akan disisipkan. Isi aturan yang disisipkan tergantung pada tipenya: |
| index | Int32 | Bilangan bulat positif yang kurang dari atau sama dengan stylesheet.cssRules.length, mewakili posisi aturan yang baru disisipkan dalam CSSStyleSheet.cssRules. Nilai default adalah 0. |

### Nilai Kembali

Indeks aturan yang baru disisipkan dalam daftar aturan lembar gaya.

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Lihat Juga

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
