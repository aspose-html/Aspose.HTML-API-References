---
title: "IXPathResult.SnapshotItem"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "IXPathResult method. Mengembalikan item ke-index dalam koleksi snapshot. Jika index lebih besar atau sama dengan jumlah node dalam daftar, metode ini mengembalikan null. Tidak seperti hasil iterator, snapshot tidak menjadi tidak valid tetapi mungkin tidak sesuai dengan dokumen saat ini jika dokumen dimutasi"
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Mengembalikan item ke-`index` dalam koleksi snapshot. Jika `index` lebih besar atau sama dengan jumlah node dalam daftar, metode ini mengembalikan `null`. Tidak seperti hasil iterator, snapshot tidak menjadi tidak valid, tetapi mungkin tidak sesuai dengan dokumen saat ini jika dokumen dimutasi.

```java
public Node SnapshotItem(int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks ke dalam koleksi snapshot. |

### Nilai Kembali

Node pada posisi ke-`index` dalam `NodeList`, atau `null` jika itu bukan indeks yang valid.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: muncul jika `resultType` bukan tipe `UnorderedNodeSnapshot` atau tipe `OrderedNodeSnapshot`. |

### Lihat Juga

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
