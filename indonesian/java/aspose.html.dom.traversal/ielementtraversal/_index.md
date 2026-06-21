---
title: "Antarmuka IElementTraversal"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.traversal.IElementTraversal. Antarmuka ElementTraversal adalah sekumpulan atribut read‑only yang memungkinkan penulis dengan mudah menavigasi antar elemen dalam sebuah dokumen. Pada implementasi yang mematuhi Element Traversal, semua objek yang mengimplementasikan Element juga harus mengimplementasikan antarmuka ElementTraversal."
type: docs

url: /id/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Antarmuka ElementTraversal adalah sekumpulan atribut hanya-baca yang memungkinkan penulis untuk dengan mudah menavigasi antar elemen dalam sebuah dokumen. Pada implementasi yang mematuhi Element Traversal, semua objek yang mengimplementasikan Element juga harus mengimplementasikan antarmuka ElementTraversal.

```java
public interface IElementTraversal
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Mengembalikan jumlah saat ini dari node elemen yang merupakan anak dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Mengembalikan node elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Mengembalikan node elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Mengembalikan node elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki node saudara elemen yang datang setelahnya dalam pohon dokumen. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Mengembalikan node elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki node saudara elemen yang datang sebelumnya dalam pohon dokumen. |

### Lihat Juga

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
