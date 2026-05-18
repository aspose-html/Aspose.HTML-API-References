---
title: "Antarmuka ICSSStyleDeclaration"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.css.ICSSStyleDeclaration. Antarmuka CSSStyleDeclaration mewakili sebuah objek yang merupakan blok deklarasi CSS dan mengekspos informasi gaya serta berbagai metode dan properti terkait gaya."
type: docs

url: /id/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Antarmuka CSSStyleDeclaration mewakili objek yang merupakan blok deklarasi CSS, dan mengekspos informasi gaya serta berbagai metode dan properti yang terkait gaya.

Objek CSSStyleDeclaration dapat diakses menggunakan tiga API berbeda:

Melalui HTMLElement.style, yang menangani gaya inline dari satu elemen. Melalui API [`CSSStyleSheet`](../icssstylesheet/). Misalnya, document.styleSheets[0].cssRules[0].style mengembalikan objek `CSSStyleDeclaration` pada aturan CSS pertama dalam stylesheet pertama dokumen. Melalui Window.getComputedStyle(), yang mengekspos objek `CSSStyleDeclaration` sebagai antarmuka hanya-baca.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Digunakan untuk mengambil properti yang telah secara eksplisit diatur dalam blok deklarasi ini. Urutan properti yang diambil menggunakan metode ini tidak harus sama dengan urutan saat mereka diatur. Metode ini dapat digunakan untuk mengiterasi semua properti dalam blok deklarasi ini. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) Properti hanya-baca ini mengembalikan jumlah integer properti yang telah secara eksplisit diatur dalam blok deklarasi CSS ini. Rentang indeks yang valid adalah 0 hingga length-1 termasuk. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) Properti hanya-baca CSSStyleDeclaration.parentRule mengembalikan sebuah CSSRule yang merupakan induk dari blok gaya ini, misalnya sebuah [`CSSStyleRule`](../icssstylerule/) yang mewakili gaya untuk sebuah selector CSS. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Digunakan untuk mengambil representasi objek dari nilai properti CSS jika properti tersebut telah secara eksplisit diatur dalam blok deklarasi ini. Metode ini mengembalikan null jika properti tersebut adalah properti singkat. Nilai properti singkat hanya dapat diakses dan dimodifikasi sebagai String, menggunakan metode getPropertyValue dan setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Digunakan untuk mengambil prioritas sebuah properti CSS (misalnya qualifier \"important\") jika properti tersebut telah secara eksplisit diatur dalam blok deklarasi ini. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | Antarmuka metode CSSStyleDeclaration.getPropertyValue() mengembalikan sebuah String yang berisi nilai dari properti CSS yang ditentukan. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | Antarmuka metode CSSStyleDeclaration.removeProperty() menghapus sebuah properti dari objek deklarasi gaya CSS. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | Antarmuka metode CSSStyleDeclaration.setProperty() digunakan untuk menetapkan nilai properti dengan prioritas default dalam blok deklarasi ini. Prioritas default bukan \"important\", yaitu String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | Antarmuka metode CSSStyleDeclaration.setProperty() digunakan untuk menetapkan nilai properti dengan prioritas default dalam blok deklarasi ini. Prioritas default bukan \"important\", yaitu String.Empty. |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Lihat Juga

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
