---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML untuk Referensi .NET API
description: TypeInfo metode. Metode ini kembali jika ada turunan antara definisi tipe referensi yaitu TypeInfo tempat metode dipanggil dan definisi tipe lainnya yaitu yang diteruskan sebagai parameter.
type: docs
weight: 30
url: /id/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Metode ini kembali jika ada turunan antara definisi tipe referensi, yaitu TypeInfo tempat metode dipanggil, dan definisi tipe lainnya, yaitu yang diteruskan sebagai parameter.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| typeNamespaceArg | String | namespace dari definisi tipe lainnya |
| typeNameArg | String | nama definisi tipe lainnya. |
| derivationMethod | UInt64 | jenis derivasi dan kondisi yang diterapkan antara dua jenis, seperti yang dijelaskan dalam daftar konstanta yang tersedia di antarmuka ini. |

### Nilai Pengembalian

Jika skema dokumen adalah DTD atau tidak ada skema yang dikaitkan dengan dokumen, metode ini akan selalu menghasilkan false. Jika skema dokumen adalah Skema XML, metode akan benar jika definisi tipe referensi berasal dari definisi tipe lain sesuai dengan parameter derivasi. Jika nilai parameter adalah 0 (tidak ada bit yang disetel ke 1 untuk parameter derivationMethod), metode akan mengembalikan true jika definisi tipe lain dapat dicapai dengan mengulangi kombinasi apa pun dari {definisi tipe dasar}, {definisi tipe item} , atau {member type definition} dari referensi type definition.

### Lihat juga

* class [TypeInfo](../)
* ruang nama [Aspose.Html.Dom](../../typeinfo/)
* perakitan [Aspose.HTML](../../../)


