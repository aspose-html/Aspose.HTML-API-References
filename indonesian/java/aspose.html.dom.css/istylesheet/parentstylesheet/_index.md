---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti IStyleSheet. Untuk bahasa lembar gaya yang mendukung konsep inklusi lembar gaya, atribut ini mewakili lembar gaya yang menyertakan jika ada. Jika lembar gaya adalah lembar gaya tingkat atas atau bahasa lembar gaya tidak mendukung inklusi, nilai atribut ini adalah null"
type: docs

url: /id/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Untuk bahasa lembar gaya yang mendukung konsep inklusi lembar gaya, atribut ini mewakili lembar gaya yang menyertakan, jika ada. Jika lembar gaya adalah lembar gaya tingkat atas, atau bahasa lembar gaya tidak mendukung inklusi, nilai atribut ini adalah null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

Atribut parentStyleSheet harus mengembalikan [`CSS style sheet`](../../icssstylesheet/) induk.

## Catatan

Properti ini mengembalikan null jika lembar gaya saat ini adalah lembar gaya tingkat atas atau jika inklusi lembar gaya tidak didukung.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Lihat Juga

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
