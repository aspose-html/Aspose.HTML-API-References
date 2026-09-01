---
title: "Enum XPathResultType"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "enum com.aspose.html.dom.xpath.XPathResultType. Sebuah unsigned short yang menunjukkan tipe hasil apa ini. Jika tipe tertentu ditentukan, maka hasil akan dikembalikan sebagai tipe yang sesuai menggunakan konversi tipe XPath bila diperlukan dan memungkinkan."
type: docs

url: /id/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Sebuah unsigned short yang menunjukkan tipe hasil apa ini. Jika `type` tertentu ditentukan, maka hasil akan dikembalikan sebagai tipe yang sesuai, menggunakan konversi tipe XPath bila diperlukan dan memungkinkan.

```java
public enum XPathResultType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Any | `0` | Kode ini tidak mewakili tipe tertentu. Evaluasi sebuah ekspresi XPath tidak akan pernah menghasilkan tipe ini. Jika tipe ini diminta, maka evaluasi mengembalikan tipe apa pun yang secara alami dihasilkan dari evaluasi ekspresi. Jika hasil alami adalah kumpulan node ketika tipe `Any` diminta, maka `UnorderedNodeIterator` selalu menjadi tipe hasil. Representasi lain dari kumpulan node harus diminta secara eksplisit. |
| Number | `1` | Hasilnya adalah sebuah angka sebagaimana didefinisikan oleh [XPath 1.0]. Modifikasi dokumen tidak membuat angka menjadi tidak valid, tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan angka yang sama. |
| String | `2` | Hasilnya adalah sebuah String sebagaimana didefinisikan oleh [XPath 1.0]. Modifikasi dokumen tidak membuat String menjadi tidak valid, tetapi dapat berarti bahwa String tidak lagi sesuai dengan dokumen saat ini. |
| Boolean | `3` | Hasilnya adalah sebuah boolean sebagaimana didefinisikan oleh [XPath 1.0]. Modifikasi dokumen tidak membuat boolean menjadi tidak valid, tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan boolean yang sama. |
| UnorderedNodeIterator | `4` | Hasilnya adalah sebuah kumpulan node sebagaimana didefinisikan oleh [XPath 1.0] yang akan diakses secara iteratif, yang mungkin tidak menghasilkan node dalam urutan tertentu. Modifikasi dokumen membuat iterasi menjadi tidak valid. Ini adalah tipe default yang dikembalikan jika hasilnya adalah kumpulan node dan tipe `Any` diminta. |
| OrderedNodeIterator | `5` | Hasilnya adalah sebuah kumpulan node sebagaimana didefinisikan oleh [XPath 1.0] yang akan diakses secara iteratif, yang akan menghasilkan node berurutan sesuai dokumen. Modifikasi dokumen membuat iterasi menjadi tidak valid. |
| UnorderedNodeSnapshot | `6` | Hasilnya adalah sebuah kumpulan node sebagaimana didefinisikan oleh [XPath 1.0] yang akan diakses sebagai daftar snapshot node yang mungkin tidak berada dalam urutan tertentu. Modifikasi dokumen tidak membuat snapshot menjadi tidak valid tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan snapshot yang sama dan node dalam snapshot mungkin telah diubah, dipindahkan, atau dihapus dari dokumen. |
| OrderedNodeSnapshot | `7` | Hasilnya adalah sebuah kumpulan node sebagaimana didefinisikan oleh [XPath 1.0] yang akan diakses sebagai daftar snapshot node yang akan berada dalam urutan dokumen asli. Modifikasi dokumen tidak membuat snapshot menjadi tidak valid tetapi dapat berarti bahwa evaluasi ulang tidak akan menghasilkan snapshot yang sama dan node dalam snapshot mungkin telah diubah, dipindahkan, atau dihapus dari dokumen. |
| AnyUnorderedNode | `8` | Hasilnya adalah sebuah kumpulan node sebagaimana didefinisikan oleh [XPath 1.0] dan akan diakses sebagai satu node, yang mungkin `null` jika kumpulan node kosong. Modifikasi dokumen tidak membuat node menjadi tidak valid, tetapi dapat berarti bahwa node hasil tidak lagi sesuai dengan dokumen saat ini. Ini adalah kemudahan yang memungkinkan optimasi karena implementasi dapat berhenti begitu satu node dalam set hasil ditemukan. Jika ada lebih dari satu node dalam hasil sebenarnya, node tunggal yang dikembalikan mungkin bukan yang pertama dalam urutan dokumen. |
| FirstOrderedNode | `9` | Hasilnya adalah sebuah kumpulan node sebagaimana didefinisikan oleh [XPath 1.0] dan akan diakses sebagai satu node, yang mungkin `null` jika kumpulan node kosong. Modifikasi dokumen tidak membuat node menjadi tidak valid, tetapi dapat berarti bahwa node hasil tidak lagi sesuai dengan dokumen saat ini. Ini adalah kemudahan yang memungkinkan optimasi karena implementasi dapat berhenti begitu node pertama dalam urutan dokumen dari set hasil ditemukan. Jika ada lebih dari satu node dalam hasil sebenarnya, node tunggal yang dikembalikan akan menjadi yang pertama dalam urutan dokumen. |

### Lihat Juga

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
