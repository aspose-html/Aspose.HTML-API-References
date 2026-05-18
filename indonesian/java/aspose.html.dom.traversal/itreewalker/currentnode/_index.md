---
title: "ITreeWalker.CurrentNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "ITreeWalker properti. Node tempat TreeWalker saat ini berada. Perubahan pada pohon DOM dapat menyebabkan node saat ini tidak lagi diterima oleh filter yang terkait dengan TreeWalker. currentNode juga dapat secara eksplisit diatur ke node apa pun, baik berada dalam subtree yang ditentukan oleh node akar maupun tidak, atau akan diterima oleh filter dan flag whatToShow. Penelusuran lebih lanjut terjadi relatif terhadap currentNode bahkan jika tidak termasuk dalam tampilan saat ini dengan menerapkan filter pada arah yang diminta; jika penelusuran tidak memungkinkan, currentNode tidak diubah."
type: docs

url: /id/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Node tempat TreeWalker saat ini berada. Perubahan pada pohon DOM dapat menyebabkan node saat ini tidak lagi diterima oleh filter yang terkait dengan TreeWalker. currentNode juga dapat secara eksplisit diatur ke node apa pun, baik berada dalam subtree yang ditentukan oleh node akar maupun tidak, atau akan diterima oleh filter dan flag whatToShow. Penelusuran lebih lanjut terjadi relatif terhadap currentNode bahkan jika tidak termasuk dalam tampilan saat ini, dengan menerapkan filter pada arah yang diminta; jika penelusuran tidak memungkinkan, currentNode tidak berubah.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Node saat ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika ada upaya untuk mengatur currentNode menjadi null. |

### Lihat Juga

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
