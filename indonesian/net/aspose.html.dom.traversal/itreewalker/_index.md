---
title: Interface ITreeWalker
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Traversal.ITreeWalker antarmuka. Objek TreeWalker digunakan untuk menavigasi pohon dokumen atau subpohon menggunakan tampilan dokumen yang ditentukan oleh tanda dan filter whatToShow mereka jika ada. Fungsi apa pun yang melakukan navigasi menggunakan TreeWalker akan secara otomatis mendukung tampilan apa pun yang ditentukan oleh TreeWalker.
type: docs
weight: 2520
url: /id/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Objek TreeWalker digunakan untuk menavigasi pohon dokumen atau subpohon menggunakan tampilan dokumen yang ditentukan oleh tanda dan filter whatToShow mereka (jika ada). Fungsi apa pun yang melakukan navigasi menggunakan TreeWalker akan secara otomatis mendukung tampilan apa pun yang ditentukan oleh TreeWalker.

Menghilangkan node dari tampilan logis subtree dapat menghasilkan struktur yang secara substansial berbeda dari subtree yang sama dalam dokumen lengkap dan tidak difilter. Node yang bersaudara dalam tampilan TreeWalker mungkin anak-anak dari node yang berbeda dan terpisah secara luas dalam tampilan aslinya. Misalnya, pertimbangkan NodeFilter yang melewati semua node kecuali untuk node Teks dan node root dari sebuah dokumen. Dalam tampilan logis yang dihasilkan, semua node teks akan menjadi saudara kandung dan muncul sebagai anak langsung dari node root, tidak peduli seberapa dalam bersarang struktur dokumen asli.

Lihat juga[Document object Model (DOM) Level 2 Traversal dan Spesifikasi Jangkauan](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sejak DOM Tingkat 2

```csharp
public interface ITreeWalker : ITraversal
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | Node di mana TreeWalker saat ini diposisikan. Perubahan pada pohon DOM dapat menyebabkan node saat ini tidak lagi diterima oleh filter terkait TreeWalker. currentNode juga dapat secara eksplisit diatur ke node mana pun, apakah itu atau tidak dalam subtree yang ditentukan oleh node root atau akan diterima oleh filter dan flag whatToShow. Penjelajahan lebih lanjut terjadi relatif terhadap Node sekarang bahkan jika itu bukan bagian dari tampilan saat ini, dengan menerapkan filter ke arah yang diminta; jika traversal tidak memungkinkan, currentNode tidak diubah. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | Memindahkan TreeWalker ke anak pertama yang terlihat dari node saat ini, dan mengembalikan node baru. Jika simpul saat ini tidak memiliki anak yang terlihat no , kembalikan null, dan pertahankan simpul current . |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | Memindahkan TreeWalker ke anak terakhir yang terlihat dari node saat ini, dan mengembalikan node baru. Jika simpul saat ini tidak memiliki anak yang terlihat no , kembalikan null, dan pertahankan simpul current . |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | Memindahkan TreeWalker ke node terlihat berikutnya dalam urutan document relatif terhadap node saat ini, dan mengembalikan node baru. Jika the node saat ini tidak memiliki node berikutnya, atau jika pencarian untuk nextNode mencoba untuk melangkah ke atas dari node root TreeWalker, mengembalikan null, dan mempertahankan node saat ini. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | Memindahkan TreeWalker ke saudara selanjutnya dari node current , dan mengembalikan node baru. Jika simpul saat ini tidak memiliki saudara berikutnya yang terlihat , kembalikan null, dan pertahankan simpul saat ini. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | Berpindah ke dan mengembalikan node leluhur terdekat yang terlihat dari node current . Jika pencarian parentNode mencoba step ke atas dari node root TreeWalker, atau jika gagal menemukan node ancestor yang terlihat, metode ini mempertahankan posisi saat ini dan mengembalikan null. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | Memindahkan TreeWalker ke node terlihat sebelumnya dalam urutan dokumen relatif terhadap node saat ini, dan mengembalikan node baru. Jika simpul saat ini tidak memiliki simpul sebelumnya, atau jika pencarian untuk Node sebelumnya mencoba melangkah ke atas dari simpul akar TreeWalker, mengembalikan null, dan mempertahankan simpul saat ini. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | Memindahkan TreeWalker ke saudara sebelumnya dari node saat ini, dan mengembalikan node baru. Jika no no node saat ini terlihat saudara sebelumnya, kembalikan null, dan pertahankan current node. |

### Lihat juga

* interface [ITraversal](../itraversal/)
* ruang nama [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* perakitan [Aspose.HTML](../../)


