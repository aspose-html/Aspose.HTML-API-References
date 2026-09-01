---
title: "IViewCSS.GetComputedStyle"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IViewCSS. Metode IViewCSS.getComputedStyle mengembalikan sebuah objek yang berisi nilai semua properti CSS dari sebuah elemen setelah menerapkan stylesheet yang aktif dan menyelesaikan perhitungan dasar yang mungkin terkandung dalam nilai-nilai tersebut."
type: docs

url: /id/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

Metode IViewCSS.getComputedStyle() mengembalikan sebuah objek yang berisi nilai semua properti CSS dari sebuah elemen, setelah menerapkan stylesheet yang aktif dan menyelesaikan setiap perhitungan dasar yang mungkin terkandung dalam nilai tersebut.

Nilai properti CSS individu dapat diakses melalui API yang disediakan oleh objek, atau dengan mengindeks menggunakan nama properti CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | Element | Elemen [`Element`](../../../com.aspose.html.dom/element/) yang akan diambil gaya terhitungnya. Parameter ini tidak boleh null. |

### Nilai Kembali

Gaya yang dikembalikan adalah objek live [`CSSStyleDeclaration`](../../icssstyledeclaration/) yang secara otomatis diperbarui ketika gaya elemen berubah.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| TypeError | Jika objek yang diberikan bukan sebuah Element atau pseudoElt bukan selector pseudo-elemen yang valid. |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Lihat Juga

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

Metode IViewCSS.getComputedStyle() mengembalikan sebuah objek yang berisi nilai semua properti CSS dari sebuah elemen, setelah menerapkan stylesheet yang aktif dan menyelesaikan setiap perhitungan dasar yang mungkin terkandung dalam nilai tersebut.

Nilai properti CSS individu dapat diakses melalui API yang disediakan oleh objek, atau dengan mengindeks menggunakan nama properti CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | Element | Elemen [`Element`](../../../com.aspose.html.dom/element/) yang akan diambil gaya terhitungnya. Parameter ini tidak boleh null. |
| pseudoElement | String | String yang menentukan pseudo-elemen yang akan dicocokkan. Ditinggalkan (atau null) untuk elemen nyata. |

### Nilai Kembali

Gaya yang dikembalikan adalah objek live [`CSSStyleDeclaration`](../../icssstyledeclaration/) yang secara otomatis diperbarui ketika gaya elemen berubah.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| TypeError | Jika objek yang diberikan bukan sebuah Element atau pseudoElt bukan selector pseudo-elemen yang valid. |

## Catatan

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referensi

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Lihat Juga

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
