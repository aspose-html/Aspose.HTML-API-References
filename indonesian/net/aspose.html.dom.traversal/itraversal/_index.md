---
title: Interface ITraversal
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Traversal.ITraversal antarmuka. Iterators digunakan untuk melangkah melalui satu set node misalnya set node dalam NodeList subpohon dokumen yang diatur oleh Node tertentu hasil kueri atau set node lainnya. Kumpulan node yang akan diulang ditentukan oleh implementasi dari NodeIterator. DOM Level 2 menentukan implementasi NodeIterator tunggal untuk traversal urutan dokumen dari subpohon dokumen. Instance dari iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator.
type: docs
weight: 2510
url: /id/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iterators digunakan untuk melangkah melalui satu set node, misalnya set node dalam NodeList, subpohon dokumen yang diatur oleh Node tertentu, hasil kueri, atau set node lainnya. Kumpulan node yang akan diulang ditentukan oleh implementasi dari NodeIterator. DOM Level 2 menentukan implementasi NodeIterator tunggal untuk traversal urutan dokumen dari subpohon dokumen. Instance dari iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator().

Lihat juga[Document object Model (DOM) Level 2 Traversal dan Spesifikasi Jangkauan](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sejak DOM Tingkat 2

```csharp
public interface ITraversal : IDisposable
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | NodeFilter digunakan untuk menyaring node. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | Node root dari NodeIterator, sebagaimana ditentukan saat it dibuat. |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | Atribut ini menentukan tipe node mana yang ditampilkan melalui iterator . Kumpulan konstanta yang tersedia ditentukan dalam antarmuka NodeFilter. Node yang tidak diterima oleh whatToShow akan dilewati, tetapi turunannya mungkin masih dipertimbangkan. Perhatikan bahwa pelewatan ini lebih diutamakan daripada filter, jika ada. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* perakitan [Aspose.HTML](../../)


