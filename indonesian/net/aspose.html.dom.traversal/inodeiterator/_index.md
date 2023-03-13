---
title: Interface INodeIterator
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Traversal.INodeIterator antarmuka. Iterators digunakan untuk melangkah melalui satu set node misalnya set node dalam NodeList subpohon dokumen yang diatur oleh Node tertentu hasil kueri atau set node lainnya. Kumpulan node yang akan diulang ditentukan oleh implementasi dari NodeIterator. DOM Level 2 menentukan implementasi NodeIterator tunggal untuk traversal urutan dokumen dari subpohon dokumen. Instance dari iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator.
type: docs
weight: 2500
url: /id/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators digunakan untuk melangkah melalui satu set node, misalnya set node dalam NodeList, subpohon dokumen yang diatur oleh Node tertentu, hasil kueri, atau set node lainnya. Kumpulan node yang akan diulang ditentukan oleh implementasi dari NodeIterator. DOM Level 2 menentukan implementasi NodeIterator tunggal untuk traversal urutan dokumen dari subpohon dokumen. Instance dari iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator().

Lihat juga[Document object Model (DOM) Level 2 Traversal dan Spesifikasi Jangkauan](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sejak DOM Tingkat 2

```csharp
public interface INodeIterator : ITraversal
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Nilai flag ini menentukan apakah turunan dari node referensi entitas dapat dilihat oleh iterator. Jika salah, mereka dan keturunannya akan ditolak. Perhatikan bahwa penolakan ini lebih diutamakan daripada whatToShow dan filter. Perhatikan juga bahwa saat ini ini adalah satu-satunya situasi di mana NodeIterators dapat menolak subtree lengkap daripada melewatkan node individu. Untuk menghasilkan tampilan dokumen yang memiliki referensi entitas diperluas dan tidak mengekspos node referensi entitas itu sendiri, gunakan bendera whatToShow untuk sembunyikan referensi entitas node dan setel expandEntityReferences ke true saat membuat iterator . Untuk menghasilkan tampilan dokumen yang memiliki node reference entitas tetapi tidak ada perluasan entitas, gunakan whatToShow flags untuk menampilkan node referensi entitas dan set expandEntityReferences ke false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Node referensi saat ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | Melepaskan NodeIterator dari set yang diulangi , melepaskan semua sumber daya komputasi dan menempatkan iterator dalam status INVALID. Setelah pelepasan dipanggil, panggilan ke Node berikutnya atau Node sebelumnya akan memunculkan pengecualian INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Mengembalikan node berikutnya di set dan memajukan posisi iterator di set. Setelah NodeIterator dibuat, panggilan pertama ke nextNode() mengembalikan node pertama di set. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Mengembalikan node sebelumnya di set dan memindahkan posisi the NodeIterator mundur di set. |

### Lihat juga

* interface [ITraversal](../itraversal/)
* ruang nama [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* perakitan [Aspose.HTML](../../)


