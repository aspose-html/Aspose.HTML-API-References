---
title: "Antarmuka IXXPathResult"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.xpath.IXPathResult. Antarmuka XPathResult mewakili hasil evaluasi ekspresi XPath 1.0 dalam konteks node tertentu. Karena evaluasi ekspresi XPath dapat menghasilkan berbagai tipe hasil, objek ini memungkinkan penemuan dan manipulasi tipe serta nilai hasil."
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Antarmuka `XPathResult` mewakili hasil evaluasi ekspresi XPath 1.0 dalam konteks node tertentu. Karena evaluasi ekspresi XPath dapat menghasilkan berbagai tipe hasil, objek ini memungkinkan penemuan dan manipulasi tipe serta nilai hasil.

```java
public interface IXPathResult
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) Nilai boolean hasil ini. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Menandakan bahwa iterator telah menjadi tidak valid. True jika `resultType`is `UnorderedNodeIterator` atau `OrderedNodeIterator` dan dokumen telah dimodifikasi sejak hasil ini dikembalikan. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) Nilai numerik hasil ini. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Kode yang mewakili tipe hasil ini, sebagaimana didefinisikan oleh enum http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/). |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) Nilai dari hasil node tunggal ini, yang mungkin `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Jumlah node dalam snapshot hasil. Nilai yang valid untuk indeks snapshotItem adalah `0` hingga `snapshotLength-1` inklusif. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) Nilai dari hasil String ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Iterasi dan mengembalikan node berikutnya dari kumpulan node atau `null` jika tidak ada lagi node. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Mengembalikan item ke-`index` dalam koleksi snapshot. Jika `index` lebih besar atau sama dengan jumlah node dalam daftar, metode ini mengembalikan `null`. Tidak seperti hasil iterator, snapshot tidak menjadi tidak valid, tetapi mungkin tidak sesuai dengan dokumen saat ini jika dimutasi. |

### Lihat Juga

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
