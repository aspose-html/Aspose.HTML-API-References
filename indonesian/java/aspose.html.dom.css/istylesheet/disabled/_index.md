---
title: "IStyleSheet.Disabled"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti IStyleSheet. Properti disabled dari antarmuka StyleSheet menentukan apakah lembar gaya dicegah untuk diterapkan pada dokumen"
type: docs

url: /id/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

Properti disabled dari antarmuka [`StyleSheet`](../) menentukan apakah lembar gaya dicegah untuk diterapkan pada dokumen.

Lembar gaya dapat dinonaktifkan dengan mengatur properti ini ke true secara manual atau jika itu adalah lembar gaya alternatif yang tidak aktif. Perhatikan bahwa disabled == false tidak menjamin lembar gaya diterapkan (misalnya dapat dihapus dari dokumen).

Memodifikasi atribut ini dapat menyebabkan resolusi gaya baru untuk dokumen. Sebuah lembar gaya hanya berlaku jika definisi media yang sesuai ada dan atribut disabled bernilai false. Jadi, jika media tidak berlaku untuk agen pengguna saat ini, atribut disabled diabaikan.

```java
public bool Disabled { get; set; }
```

### Nilai Kembali

Atribut disabled, saat dibaca, harus mengembalikan true jika flag disabled diatur, atau false sebaliknya. Saat diatur, atribut disabled harus mengatur flag disabled jika nilai baru true, atau menghapus flag disabled sebaliknya.

### Property Value

Atribut disabled, saat dibaca, harus mengembalikan true jika flag disabled diatur, atau false sebaliknya. Saat diatur, atribut disabled harus mengatur flag disabled jika nilai baru true, atau menghapus flag disabled sebaliknya.

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Lihat Juga

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
