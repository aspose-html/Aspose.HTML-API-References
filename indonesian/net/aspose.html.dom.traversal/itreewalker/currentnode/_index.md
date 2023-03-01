---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML untuk Referensi .NET API
description: ITreeWalker Properti. Node di mana TreeWalker saat ini diposisikan. Perubahan pada pohon DOM dapat menyebabkan node saat ini tidak lagi diterima oleh filter terkait TreeWalker. currentNode juga dapat secara eksplisit diatur ke node mana pun apakah itu atau tidak dalam subtree yang ditentukan oleh node root atau akan diterima oleh filter dan flag whatToShow. Penjelajahan lebih lanjut terjadi relatif terhadap Node sekarang bahkan jika itu bukan bagian dari tampilan saat ini dengan menerapkan filter ke arah yang diminta jika traversal tidak memungkinkan currentNode tidak diubah.
type: docs
weight: 10
url: /id/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Node di mana TreeWalker saat ini diposisikan. Perubahan pada pohon DOM dapat menyebabkan node saat ini tidak lagi diterima oleh filter terkait TreeWalker. currentNode juga dapat secara eksplisit diatur ke node mana pun, apakah itu atau tidak dalam subtree yang ditentukan oleh node root atau akan diterima oleh filter dan flag whatToShow. Penjelajahan lebih lanjut terjadi relatif terhadap Node sekarang bahkan jika itu bukan bagian dari tampilan saat ini, dengan menerapkan filter ke arah yang diminta; jika traversal tidak memungkinkan, currentNode tidak diubah.

```csharp
public Node CurrentNode { get; set; }
```

### Nilai properti

Node saat ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dimunculkan jika upaya dilakukan untuk menyetel currentNode ke null. |

### Lihat juga

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* ruang nama [Aspose.Html.Dom.Traversal](../../itreewalker/)
* perakitan [Aspose.HTML](../../../)


