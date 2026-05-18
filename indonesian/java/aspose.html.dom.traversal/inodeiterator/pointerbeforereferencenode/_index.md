---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "INodeIterator property. Nilai bendera ini menentukan apakah anak dari node referensi entitas terlihat oleh iterator. Jika false, mereka dan keturunan mereka akan ditolak. Perhatikan bahwa penolakan ini memiliki prioritas lebih tinggi daripada whatToShow dan filter. Juga perhatikan bahwa ini saat ini satu-satunya situasi di mana NodeIterators dapat menolak seluruh subtree alih-alih melewati node individu. Untuk menghasilkan tampilan dokumen yang memiliki referensi entitas yang diperluas dan tidak menampilkan node referensi entitas itu sendiri, gunakan flag whatToShow untuk menyembunyikan node referensi entitas dan setel expandEntityReferences ke true saat membuat iterator. Untuk menghasilkan tampilan dokumen yang memiliki node referensi entitas tetapi tanpa ekspansi entitas, gunakan flag whatToShow untuk menampilkan node referensi entitas dan setel expandEntityReferences ke false."
type: docs

url: /id/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Nilai bendera ini menentukan apakah anak dari node referensi entitas terlihat oleh iterator. Jika false, mereka dan keturunan mereka akan ditolak. Perhatikan bahwa penolakan ini memiliki prioritas lebih tinggi daripada whatToShow dan filter. Juga perhatikan bahwa ini saat ini satu-satunya situasi di mana NodeIterators dapat menolak seluruh subtree alih-alih melewati node individu. Untuk menghasilkan tampilan dokumen yang memiliki referensi entitas yang diperluas dan tidak menampilkan node referensi entitas itu sendiri, gunakan flag whatToShow untuk menyembunyikan node referensi entitas dan setel expandEntityReferences ke true saat membuat iterator. Untuk menghasilkan tampilan dokumen yang memiliki node referensi entitas tetapi tanpa ekspansi entitas, gunakan flag whatToShow untuk menampilkan node referensi entitas dan setel expandEntityReferences ke false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` jika [expand entity references]; selainnya, `false`.

### Lihat Juga

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
