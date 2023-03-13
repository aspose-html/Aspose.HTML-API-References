---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration antarmuka. Antarmuka CSSStyleDeclaration mewakili satu blok deklarasi CSS. Antarmuka ini dapat digunakan untuk menentukan properti gaya yang saat ini disetel di blok atau untuk menyetel properti gaya secara eksplisit di dalam blok.
type: docs
weight: 490
url: /id/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Antarmuka CSSStyleDeclaration mewakili satu blok deklarasi CSS. Antarmuka ini dapat digunakan untuk menentukan properti gaya yang saat ini disetel di blok atau untuk menyetel properti gaya secara eksplisit di dalam blok.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | Representasi tekstual parsable dari blok deklarasi (tidak termasuk kurung kurawal di sekitarnya). Menyetel atribut ini akan menghasilkan penguraian nilai baru dan menyetel ulang semua properti di blok deklarasi termasuk penghapusan atau penambahan properti. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Digunakan untuk mengambil properti yang telah diatur secara eksplisit di blok deklarasi ini. Urutan properti yang diambil menggunakan metode ini tidak harus sesuai dengan urutan pengaturannya. Metode ini dapat digunakan untuk mengulangi semua properti di blok deklarasi ini. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | Jumlah properti yang telah ditetapkan secara eksplisit di blok deklarasi ini. Kisaran indeks yang valid adalah 0 hingga panjang-1 inklusif. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | Aturan CSS yang berisi blok deklarasi ini atau null jika CSSStyleDeclaration ini tidak dilampirkan ke CSSRule. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Digunakan untuk mengambil representasi objek dari nilai properti CSS jika telah ditetapkan secara eksplisit dalam blok deklarasi ini. Metode ini mengembalikan nol jika properti adalah properti steno. Nilai properti singkatan hanya dapat diakses dan dimodifikasi sebagai string, menggunakan metode getPropertyValue dan setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Digunakan untuk mengambil prioritas properti CSS (misalnya kualifikasi "penting") jika properti telah ditetapkan secara eksplisit di blok deklarasi ini. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Digunakan untuk mengambil nilai properti CSS jika telah ditetapkan secara eksplisit dalam blok deklarasi ini. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Digunakan untuk menghapus properti CSS jika telah ditetapkan secara eksplisit dalam blok deklarasi ini. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Digunakan untuk menetapkan nilai properti dengan prioritas default dalam blok deklarasi ini. Prioritas default tidak "penting" yaitu String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Digunakan untuk menetapkan nilai properti dan prioritas dalam blok deklarasi ini. |

### Lihat juga

* interface [ICSS2Properties](../icss2properties/)
* ruang nama [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* perakitan [Aspose.HTML](../../)


