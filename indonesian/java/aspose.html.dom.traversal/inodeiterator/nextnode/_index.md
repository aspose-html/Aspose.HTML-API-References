---
title: "INodeIterator.NextNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode INodeIterator. Mengembalikan node berikutnya dalam set dan memajukan posisi iterator dalam set. Setelah NodeIterator dibuat, pemanggilan pertama ke nextNode mengembalikan node pertama dalam set."
type: docs

url: /id/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Mengembalikan node berikutnya dalam set dan memajukan posisi iterator dalam set. Setelah NodeIterator dibuat, panggilan pertama ke nextNode() mengembalikan node pertama dalam set.

```java
public Node NextNode()
```

### Nilai Kembali

Node berikutnya dalam set yang sedang diiterasi, atau null jika tidak ada lagi anggota dalam set tersebut.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Dikeluarkan jika metode ini dipanggil setelah metode detach dipanggil. |

### Lihat Juga

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
