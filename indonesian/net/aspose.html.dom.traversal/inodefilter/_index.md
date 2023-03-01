---
title: Interface INodeFilter
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Traversal.INodeFilter antarmuka. Filter adalah objek yang mengetahui cara memfilter node. Jika NodeIterator atau TreeWalker diberi NodeFilter ini menerapkan filter sebelum mengembalikan node berikutnya. Jika filter mengatakan menerima node logika traversal mengembalikan itu jika tidak traversal mencari node berikutnya dan berpurapura bahwa node yang ditolak tidak ada.
type: docs
weight: 2490
url: /id/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filter adalah objek yang mengetahui cara "memfilter" node. Jika NodeIterator atau TreeWalker diberi NodeFilter, ini menerapkan filter sebelum mengembalikan node berikutnya. Jika filter mengatakan menerima node, logika traversal mengembalikan itu; jika tidak, traversal mencari node berikutnya dan berpura-pura bahwa node yang ditolak tidak ada.

DOM tidak menyediakan filter apa pun. NodeFilter hanyalah antarmuka yang dapat diterapkan pengguna untuk menyediakan filter mereka sendiri.

NodeFilters tidak perlu mengetahui cara melintasi dari node ke node, juga tidak perlu mengetahui apa pun tentang struktur data yang sedang dilalui . Ini membuatnya sangat mudah untuk menulis filter, karena satu-satunya hal yang harus mereka ketahui adalah mengevaluasi satu node. Satu filter dapat digunakan dengan sejumlah jenis traversal yang berbeda, mendorong penggunaan kembali kode.

Lihat juga[Document object Model (DOM) Level 2 Traversal dan Spesifikasi Jangkauan](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sejak DOM Tingkat 2

```csharp
public interface INodeFilter
```

## Metode

| Nama | Keterangan |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Menguji apakah node yang ditentukan terlihat dalam tampilan logis dari TreeWalker atau NodeIterator. Fungsi ini akan dipanggil dengan implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil langsung dari kode pengguna . (Meskipun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk memandu logika aplikasi Anda sendiri.) |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* perakitan [Aspose.HTML](../../)


