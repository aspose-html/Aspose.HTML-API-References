---
title: Interface IElementTraversal
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Traversal.IElementTraversal antarmuka. Antarmuka ElementTraversal adalah sekumpulan atribut hanyabaca yang memungkinkan penulis untuk dengan mudah menavigasi antar elemen dalam dokumen. Dalam menyesuaikan implementasi Element Traversal semua objek yang mengimplementasikan Element juga harus mengimplementasikan antarmuka ElementTraversal.
type: docs
weight: 2480
url: /id/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Antarmuka ElementTraversal adalah sekumpulan atribut hanya-baca yang memungkinkan penulis untuk dengan mudah menavigasi antar elemen dalam dokumen. Dalam menyesuaikan implementasi Element Traversal, semua objek yang mengimplementasikan Element juga harus mengimplementasikan antarmuka ElementTraversal.

```csharp
public interface IElementTraversal
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Mengembalikan jumlah node elemen saat ini yang merupakan turunan dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Mengembalikan simpul elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Mengembalikan simpul elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Mengembalikan simpul elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang muncul setelah elemen ini di pohon dokumen. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Mengembalikan simpul elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang datang sebelum elemen ini di pohon dokumen. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* perakitan [Aspose.HTML](../../)


