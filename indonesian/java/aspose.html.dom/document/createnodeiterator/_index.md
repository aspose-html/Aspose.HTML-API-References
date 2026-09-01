---
title: "Document.CreateNodeIterator"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Document method. Membuat NodeIterator baru atas subpohon yang berakar pada node yang ditentukan"
type: docs

url: /id/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Buat NodeIterator baru pada subtree yang berakar di node yang ditentukan.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| root | Node | node yang akan diiterasi bersama dengan anak-anaknya. Iterator awalnya diposisikan tepat sebelum node ini. Bendera whatToShow dan filter, jika ada, tidak dipertimbangkan saat menetapkan posisi ini. Root tidak boleh null. |

### Nilai Kembali

NodeIterator yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika root yang ditentukan bernilai null. |

### Lihat Juga

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Buat NodeIterator baru pada subtree yang berakar di node yang ditentukan.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| root | Node | node yang akan diiterasi bersama dengan anak-anaknya. Iterator awalnya diposisikan tepat sebelum node ini. Bendera whatToShow dan filter, jika ada, tidak dipertimbangkan saat menetapkan posisi ini. Root tidak boleh null. |
| whatToShow | Int64 | bendera menentukan tipe node mana yang dapat muncul dalam tampilan logis pohon yang disajikan oleh iterator. Lihat deskripsi NodeFilter untuk kumpulan nilai SHOW_ yang mungkin. Bendera ini dapat digabungkan menggunakan OR. |

### Nilai Kembali

NodeIterator yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika root yang ditentukan bernilai null. |

### Lihat Juga

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Buat NodeIterator baru pada subtree yang berakar di node yang ditentukan.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| root | Node | node yang akan diiterasi bersama dengan anak-anaknya. Iterator awalnya diposisikan tepat sebelum node ini. Bendera whatToShow dan filter, jika ada, tidak dipertimbangkan saat menetapkan posisi ini. Root tidak boleh null. |
| whatToShow | Int64 | bendera menentukan tipe node mana yang dapat muncul dalam tampilan logis pohon yang disajikan oleh iterator. Lihat deskripsi NodeFilter untuk kumpulan nilai SHOW_ yang mungkin. Bendera ini dapat digabungkan menggunakan OR. |
| filter | INodeFilter | NodeFilter yang akan digunakan dengan TreeWalker ini, atau null untuk menunjukkan tidak ada filter. |

### Nilai Kembali

NodeIterator yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika root yang ditentukan bernilai null. |

### Lihat Juga

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
