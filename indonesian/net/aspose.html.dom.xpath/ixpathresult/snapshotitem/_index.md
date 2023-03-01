---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML untuk Referensi .NET API
description: IXPathResult metode. Mengembalikanindeks item th dalam koleksi snapshot. Jikaindekslebih besar dari atau sama dengan jumlah node dalam daftar metode ini kembalibatal . Berbeda dengan hasil iterator  snapshot tidak menjadi tidak valid tetapi mungkin tidak sesuai dengan dokumen saat ini jika dimutasikan.
type: docs
weight: 90
url: /id/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Mengembalikan`indeks` item th dalam koleksi snapshot. Jika`indeks`lebih besar dari atau sama dengan jumlah node dalam daftar, metode ini kembali`batal` . Berbeda dengan hasil iterator , snapshot tidak menjadi tidak valid, tetapi mungkin tidak sesuai dengan dokumen saat ini jika dimutasikan.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| index | Int32 | Indeks ke dalam koleksi snapshot. |

### Nilai Pengembalian

Node di`indeks` posisi th di`Daftar Node` , atau`batal` jika itu bukan indeks yang valid.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: dinaikkan jika`jenishasil` bukan `UnorderedNodeSnapshot` ketik atau`OrderedNodeSnapshot` jenis. |

### Lihat juga

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* ruang nama [Aspose.Html.Dom.XPath](../../ixpathresult/)
* perakitan [Aspose.HTML](../../../)


