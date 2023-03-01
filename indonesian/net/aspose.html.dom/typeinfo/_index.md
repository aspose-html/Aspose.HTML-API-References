---
title: Class TypeInfo
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.TypeInfo kelas. TypeInfo merepresentasikan tipe yang direferensikan dari node Element atau Attr ditentukan dalam skema yang terkait dengan dokumen.
type: docs
weight: 2530
url: /id/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo merepresentasikan tipe yang direferensikan dari node Element atau Attr, ditentukan dalam skema yang terkait dengan dokumen.

```csharp
public class TypeInfo : DOMObject
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | Nama tipe yang dideklarasikan untuk elemen atau atribut terkait, atau null jika tidak diketahui. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Mendapat namespace tipe. Namespace dari tipe yang dideklarasikan untuk elemen atau atribut terkait atau null jika elemen tidak memiliki deklarasi atau jika tidak ada informasi namespace yang tersedia. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Metode ini kembali jika ada turunan antara definisi tipe referensi, yaitu TypeInfo tempat metode dipanggil, dan definisi tipe lainnya, yaitu yang diteruskan sebagai parameter. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Jika skema dokumen adalah Skema XML [Skema XML Bagian 1], konstanta ini merepresentasikan derivasi dengan ekstensi. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Jika skema dokumen adalah Skema XML [Skema XML Bagian 1], konstanta ini mewakili daftar. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Jika skema dokumen adalah Skema XML [Skema XML Bagian 1], konstanta ini merepresentasikan derivasi dengan pembatasan jika melibatkan tipe kompleks, atau pembatasan jika melibatkan tipe sederhana. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Jika skema dokumen adalah Skema XML [Skema XML Bagian 1], konstanta ini mewakili penyatuan jika tipe sederhana terlibat. |

### Lihat juga

* class [DOMObject](../domobject/)
* ruang nama [Aspose.Html.Dom](../../aspose.html.dom/)
* perakitan [Aspose.HTML](../../)


