---
title: "Kelas CSSValue"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.css.CSSValue. Mewakili nilai sederhana atau kompleks. Objek CSSValue hanya muncul dalam konteks properti CSS."
type: docs

url: /id/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Merepresentasikan nilai sederhana atau kompleks. Objek CSSValue hanya muncul dalam konteks sebuah properti CSS.

```java
public abstract class CSSValue : DOMObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Properti cssText dari antarmuka `CSSValue` merepresentasikan nilai properti CSS yang dihitung saat ini. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Sebuah kode yang mendefinisikan tipe nilai. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Menentukan apakah Objek yang ditentukan sama dengan instance ini. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Metode ini digunakan untuk mengambil Tipe objek ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Mengembalikan String yang mewakili instance ini. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | Nilai tersebut adalah nilai khusus. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | Nilai tersebut diwariskan dan cssText berisi "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | Nilai tersebut adalah nilai primitif dan sebuah instance dari antarmuka CSSPrimitiveValue dapat diperoleh dengan menggunakan metode casting khusus binding pada instance antarmuka CSSValue ini. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | Nilai tersebut adalah daftar CSSValue dan sebuah instance dari antarmuka CSSValueList dapat diperoleh dengan menggunakan metode casting spesifik binding pada instance antarmuka CSSValue ini. |

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
