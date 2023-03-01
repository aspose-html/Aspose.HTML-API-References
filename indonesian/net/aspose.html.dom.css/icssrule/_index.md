---
title: Interface ICSSRule
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Css.ICSSRule antarmuka. Antarmuka CSSRule adalah antarmuka dasar abstrak untuk semua jenis pernyataan CSS. Ini termasuk kumpulan aturan dan atrules. Implementasi diharapkan untuk mempertahankan semua aturan yang ditentukan dalam lembar gaya CSS bahkan jika aturan tersebut tidak dikenali oleh parser. Aturan yang tidak dikenal direpresentasikan menggunakanICSSUnknownRule antarmuka.
type: docs
weight: 470
url: /id/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

Antarmuka CSSRule adalah antarmuka dasar abstrak untuk semua jenis pernyataan CSS. Ini termasuk kumpulan aturan dan at-rules. Implementasi diharapkan untuk mempertahankan semua aturan yang ditentukan dalam lembar gaya CSS, bahkan jika aturan tersebut tidak dikenali oleh parser. Aturan yang tidak dikenal direpresentasikan menggunakan!:ICSSUnknownRule antarmuka.

```csharp
public interface ICSSRule
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | Representasi tekstual aturan yang dapat diuraikan. Ini mencerminkan status aturan saat ini dan bukan nilai awalnya. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | Jika aturan ini terdapat di dalam aturan lain (misalnya aturan gaya di dalam blok @media), ini adalah aturan yang memuatnya. Jika aturan ini tidak bersarang di dalam aturan lain, ini mengembalikan null. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | Style sheet yang berisi aturan ini. |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | Jenis aturan, seperti yang didefinisikan di atas. Harapannya adalah bahwa metode pengecoran khusus binding dapat digunakan untuk menurunkan dari instance antarmuka CSSRule ke antarmuka turunan spesifik yang tersirat oleh tipe. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* perakitan [Aspose.HTML](../../)


