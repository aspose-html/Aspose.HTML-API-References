---
title: "Antarmuka IDocumentCSS"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.css.IDocumentCSS. Antarmuka ini mewakili sebuah dokumen dengan tampilan CSS."
type: docs

url: /id/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Antarmuka ini mewakili dokumen dengan tampilan CSS.

Metode getOverrideStyle menyediakan mekanisme di mana penulis DOM dapat melakukan perubahan langsung pada gaya sebuah elemen tanpa mengubah stylesheet yang secara eksplisit terhubung pada dokumen atau gaya inline elemen dalam stylesheet. Stylesheet ini berada setelah stylesheet penulis dalam algoritma kaskade dan disebut stylesheet override. Stylesheet override memiliki prioritas lebih tinggi daripada stylesheet penulis. Deklarasi \"!important\" tetap memiliki prioritas lebih tinggi daripada deklarasi normal. Stylesheet override, penulis, dan pengguna semuanya dapat berisi deklarasi \"!important\". Aturan \"!important\" pengguna memiliki prioritas lebih tinggi daripada aturan \"!important\" override dan penulis, dan aturan \"!important\" override memiliki prioritas lebih tinggi daripada aturan \"!important\" penulis.

Diharapkan bahwa sebuah instance dari antarmuka DocumentCSS dapat diperoleh dengan menggunakan metode casting khusus binding pada sebuah instance dari antarmuka Document.

Lihat juga [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Metode ini digunakan untuk mengambil deklarasi gaya override untuk elemen tertentu dan pseudo-elemen tertentu. |

### Lihat Juga

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
