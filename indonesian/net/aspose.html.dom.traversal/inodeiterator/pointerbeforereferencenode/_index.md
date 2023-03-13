---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML untuk Referensi .NET API
description: INodeIterator Properti. Nilai flag ini menentukan apakah turunan dari node referensi entitas dapat dilihat oleh iterator. Jika salah mereka dan keturunannya akan ditolak. Perhatikan bahwa penolakan ini lebih diutamakan daripada whatToShow dan filter. Perhatikan juga bahwa saat ini ini adalah satusatunya situasi di mana NodeIterators dapat menolak subtree lengkap daripada melewatkan node individu. Untuk menghasilkan tampilan dokumen yang memiliki referensi entitas diperluas dan tidak mengekspos node referensi entitas itu sendiri gunakan bendera whatToShow untuk sembunyikan referensi entitas node dan setel expandEntityReferences ke true saat membuat iterator . Untuk menghasilkan tampilan dokumen yang memiliki node reference entitas tetapi tidak ada perluasan entitas gunakan whatToShow flags untuk menampilkan node referensi entitas dan set expandEntityReferences ke false.
type: docs
weight: 10
url: /id/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Nilai flag ini menentukan apakah turunan dari node referensi entitas dapat dilihat oleh iterator. Jika salah, mereka dan keturunannya akan ditolak. Perhatikan bahwa penolakan ini lebih diutamakan daripada whatToShow dan filter. Perhatikan juga bahwa saat ini ini adalah satu-satunya situasi di mana NodeIterators dapat menolak subtree lengkap daripada melewatkan node individu. Untuk menghasilkan tampilan dokumen yang memiliki referensi entitas diperluas dan tidak mengekspos node referensi entitas itu sendiri, gunakan bendera whatToShow untuk sembunyikan referensi entitas node dan setel expandEntityReferences ke true saat membuat iterator . Untuk menghasilkan tampilan dokumen yang memiliki node reference entitas tetapi tidak ada perluasan entitas, gunakan whatToShow flags untuk menampilkan node referensi entitas dan set expandEntityReferences ke false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Nilai properti

`BENAR`if [perluas referensi entitas]; jika tidak,`PALSU` .

### Lihat juga

* interface [INodeIterator](../)
* ruang nama [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* perakitan [Aspose.HTML](../../../)


