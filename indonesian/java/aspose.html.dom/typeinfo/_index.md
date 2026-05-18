---
title: "Kelas TypeInfo"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.dom.TypeInfo. TypeInfo mewakili tipe yang dirujuk dari node Element atau Attr yang ditentukan dalam skema yang terkait dengan dokumen."
type: docs

url: /id/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

Antarmuka **TypeInfo** mewakili tipe yang dirujuk dari node **Element** atau **Attr**, yang ditentukan dalam skema yang terkait dengan dokumen.

```java
public class TypeInfo : DOMObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Nama sebuah tipe yang dideklarasikan untuk elemen atau atribut yang terkait, atau null jika tidak diketahui. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Mendapatkan paket tipe. Paket dari tipe yang dideklarasikan untuk elemen atau atribut yang terkait atau null jika elemen tidak memiliki deklarasi atau jika tidak ada informasi paket yang tersedia. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Metode ini mengembalikan apakah ada derivasi antara definisi tipe referensi, yaitu TypeInfo tempat metode ini dipanggil, dan definisi tipe lainnya, yaitu yang diberikan sebagai parameter. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Jika skema dokumen adalah XML Schema [XML Schema Part 1], konstanta ini mewakili derivasi melalui ekstensi. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Jika skema dokumen adalah XML Schema [XML Schema Part 1], konstanta ini mewakili daftar. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Jika skema dokumen adalah XML Schema [XML Schema Part 1], konstanta ini mewakili derivasi melalui restriksi jika tipe kompleks terlibat, atau restriksi jika tipe sederhana terlibat. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Jika skema dokumen adalah XML Schema [XML Schema Part 1], konstanta ini mewakili union jika tipe sederhana terlibat. |

### Lihat Juga

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
