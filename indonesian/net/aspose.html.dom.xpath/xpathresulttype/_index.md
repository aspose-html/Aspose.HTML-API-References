---
title: Enum XPathResultType
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.XPath.XPathResultType enum. Short unsigned yang menunjukkan jenis hasil apa ini. Jika tertentujenisditentukan maka hasilnya akan dikembalikan sebagai tipe yang sesuai menggunakan konversi tipe XPath jika diperlukan dan memungkinkan.
type: docs
weight: 2610
url: /id/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Short unsigned yang menunjukkan jenis hasil apa ini. Jika tertentu`jenis`ditentukan, maka hasilnya akan dikembalikan sebagai tipe yang sesuai, menggunakan konversi tipe XPath jika diperlukan dan memungkinkan.

```csharp
public enum XPathResultType
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Any | `0` | Kode ini tidak mewakili jenis tertentu. Evaluasi ekspresi XPath tidak akan pernah menghasilkan tipe ini. Jika tipe ini diminta, maka evaluasi mengembalikan tipe apa pun yang secara alami dihasilkan dari evaluasi ekspresi. Jika hasil alami adalah simpul yang ditetapkan kapan`Setiap` jenis diminta, lalu`UnorderedNodeIterator` selalu merupakan tipe yang dihasilkan. Representasi lain dari kumpulan simpul harus diminta secara eksplisit. |
| Number | `1` | Hasilnya adalah angka seperti yang ditentukan oleh [XPath 1.0]. Modifikasi dokumen tidak membatalkan nomor, tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan nomor yang sama. |
| String | `2` | Hasilnya adalah string seperti yang didefinisikan oleh [XPath 1.0]. Modifikasi dokumen tidak membatalkan string, tetapi dapat berarti bahwa string tidak lagi sesuai dengan dokumen saat ini. |
| Boolean | `3` | Hasilnya adalah boolean seperti yang didefinisikan oleh [XPath 1.0]. Modifikasi dokumen tidak membatalkan boolean, tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan boolean yang sama. |
| UnorderedNodeIterator | `4` | Hasilnya adalah kumpulan node seperti yang ditentukan oleh [XPath 1.0] yang akan diakses secara iteratif, yang mungkin tidak menghasilkan node dalam urutan tertentu. Modifikasi dokumen membatalkan iterasi . Ini adalah tipe default yang dikembalikan jika hasilnya adalah set node dan`Setiap` Jenis diminta. |
| OrderedNodeIterator | `5` | Hasilnya adalah kumpulan node seperti yang ditentukan oleh [XPath 1.0] yang akan diakses secara iteratif, yang akan menghasilkan node yang dipesan berdasarkan dokumen. Modifikasi dokumen membatalkan iterasi. |
| UnorderedNodeSnapshot | `6` | Hasilnya adalah kumpulan node seperti yang ditentukan oleh [XPath 1.0] yang akan diakses sebagai snapshot daftar node yang mungkin tidak berada dalam urutan tertentu. Modifikasi dokumen tidak membatalkan snapshot tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan snapshot yang sama dan node dalam snapshot mungkin telah diubah, dipindahkan, atau dihapus dari dokumen. |
| OrderedNodeSnapshot | `7` | Hasilnya adalah kumpulan node seperti yang didefinisikan oleh [XPath 1.0] yang akan diakses sebagai snapshot daftar node yang akan berada dalam urutan dokumen asli. Modifikasi dokumen tidak membatalkan snapshot tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan snapshot yang sama dan node dalam snapshot mungkin telah diubah, dipindahkan, atau dihapus dari dokumen. |
| AnyUnorderedNode | `8` | Hasilnya adalah kumpulan node seperti yang ditentukan oleh [XPath 1.0] dan akan diakses sebagai node tunggal, yang mungkin`batal`jika set node kosong. Modifikasi dokumen tidak membatalkan node, tetapi dapat berarti bahwa node hasil tidak lagi sesuai dengan dokumen saat ini. Ini adalah kemudahan yang memungkinkan pengoptimalan karena implementasi dapat berhenti setelah node mana pun dalam set yang dihasilkan ditemukan. Jika ada lebih dari satu simpul dalam hasil aktual, simpul tunggal yang dikembalikan mungkin bukan yang pertama dalam urutan dokumen. |
| FirstOrderedNode | `9` | Hasilnya adalah kumpulan node seperti yang ditentukan oleh [XPath 1.0] dan akan diakses sebagai node tunggal, yang mungkin`batal`jika set node kosong. Modifikasi dokumen tidak membatalkan node, tetapi dapat berarti bahwa node hasil tidak lagi sesuai dengan dokumen saat ini. Ini adalah kemudahan yang memungkinkan pengoptimalan karena implementasi dapat berhenti setelah node pertama dalam urutan dokumen dari set yang dihasilkan telah ditemukan. Jika ada lebih dari satu simpul dalam hasil aktual, simpul tunggal yang dikembalikan akan menjadi yang pertama dalam urutan dokumen. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* perakitan [Aspose.HTML](../../)


