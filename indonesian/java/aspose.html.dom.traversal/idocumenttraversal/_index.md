---
title: "Antarmuka IDocumentTraversal"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.traversal.IDocumentTraversal. DocumentTraversal berisi metode yang membuat iterator dan tree-walker untuk menelusuri sebuah node dan anak‑anaknya dalam urutan dokumen dengan penelusuran depth‑first pre‑order yang setara dengan urutan tag pembuka dalam representasi teks dokumen. Pada DOM yang mendukung fitur Traversal, DocumentTraversal akan diimplementasikan oleh objek yang sama yang mengimplementasikan antarmuka Document."
type: docs

url: /id/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal berisi metode yang membuat iterator dan tree-walker untuk menelusuri sebuah node dan anak‑anaknya dalam urutan dokumen (depth first, pre‑order traversal, yang setara dengan urutan di mana tag pembuka muncul dalam representasi teks dokumen). Pada DOM yang mendukung fitur Traversal, DocumentTraversal akan diimplementasikan oleh objek yang sama yang mengimplementasikan antarmuka Document.

Lihat juga [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Membuat TreeWalker baru atas subtree yang berakar pada node yang ditentukan. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Membuat TreeWalker baru atas subtree yang berakar pada node yang ditentukan. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Membuat TreeWalker baru atas subtree yang berakar pada node yang ditentukan. |

### Lihat Juga

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
