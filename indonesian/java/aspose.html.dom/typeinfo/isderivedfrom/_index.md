---
title: "TypeInfo.IsDerivedFrom"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode TypeInfo. Metode ini mengembalikan apakah ada derivasi antara definisi tipe referensi, yaitu TypeInfo tempat metode dipanggil, dan definisi tipe lain, yaitu yang diberikan sebagai parameter"
type: docs

url: /id/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Metode ini mengembalikan apakah ada derivasi antara definisi tipe referensi, yaitu TypeInfo tempat metode ini dipanggil, dan definisi tipe lainnya, yaitu yang diberikan sebagai parameter.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeNamespaceArg | String | paket dari definisi tipe lain |
| typeNameArg | String | nama definisi tipe lain. |
| derivationMethod | UInt64 | jenis derivasi dan kondisi yang diterapkan antara dua tipe, seperti yang dijelaskan dalam daftar konstanta yang disediakan dalam antarmuka ini. |

### Nilai Kembali

Jika skema dokumen adalah DTD atau tidak ada skema yang terkait dengan dokumen, metode ini selalu mengembalikan false. Jika skema dokumen adalah XML Schema, metode ini akan mengembalikan true jika definisi tipe referensi diturunkan dari definisi tipe lain sesuai dengan parameter derivasi. Jika nilai parameter adalah 0 (tidak ada bit yang diset ke 1 untuk parameter derivationMethod), metode ini akan mengembalikan true jika definisi tipe lain dapat dicapai dengan merekursi kombinasi apa pun dari {base type definition}, {item type definition}, atau {member type definitions} dari definisi tipe referensi.

### Lihat Juga

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
