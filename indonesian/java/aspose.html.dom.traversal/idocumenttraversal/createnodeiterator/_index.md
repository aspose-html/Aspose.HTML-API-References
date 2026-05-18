---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IDocumentTraversal. Membuat NodeIterator baru atas subpohon yang berakar pada node yang ditentukan."
type: docs

url: /id/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| akar | Node | node yang akan diiterasi bersama anak-anaknya. Iterator awalnya ditempatkan tepat sebelum node ini. Bendera whatToShow dan filter, bila ada, tidak dipertimbangkan saat mengatur posisi ini. Akar tidak boleh null. |

### Nilai Kembali

NodeIterator yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika akar yang ditentukan bernilai null. |

### Lihat Juga

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| akar | Node | node yang akan diiterasi bersama anak-anaknya. Iterator awalnya ditempatkan tepat sebelum node ini. Bendera whatToShow dan filter, bila ada, tidak dipertimbangkan saat mengatur posisi ini. Akar tidak boleh null. |
| whatToShow | Int64 | bendera menentukan jenis node mana yang dapat muncul dalam tampilan logis pohon yang disajikan oleh iterator. Lihat deskripsi NodeFilter untuk kumpulan nilai SHOW_ yang mungkin. Bendera ini dapat digabungkan menggunakan OR. |

### Nilai Kembali

NodeIterator yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika akar yang ditentukan bernilai null. |

### Lihat Juga

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| akar | Node | node yang akan diiterasi bersama anak-anaknya. Iterator awalnya ditempatkan tepat sebelum node ini. Bendera whatToShow dan filter, bila ada, tidak dipertimbangkan saat mengatur posisi ini. Akar tidak boleh null. |
| whatToShow | Int64 | bendera menentukan jenis node mana yang dapat muncul dalam tampilan logis pohon yang disajikan oleh iterator. Lihat deskripsi NodeFilter untuk kumpulan nilai SHOW_ yang mungkin. Bendera ini dapat digabungkan menggunakan OR. |
| filter | INodeFilter | NodeFilter yang akan digunakan dengan TreeWalker ini, atau null untuk menunjukkan tidak ada filter. |

### Nilai Kembali

NodeIterator yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika akar yang ditentukan bernilai null. |

### Lihat Juga

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
