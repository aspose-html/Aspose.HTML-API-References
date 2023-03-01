---
title: Document.CreateNodeIterator
second_title: Aspose.HTML untuk Referensi .NET API
description: Document metode. Buat NodeIterator baru di atas subtree yang diroot pada node yang ditentukan.
type: docs
weight: 900
url: /id/net/aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Buat NodeIterator baru di atas subtree yang di-root pada node yang ditentukan.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| root | Node | simpul yang akan diiterasi bersama dengan anaknya. Iterator awalnya diposisikan tepat sebelum simpul ini. Bendera whatToShow dan filter, jika ada, tidak dipertimbangkan saat menyetel posisi ini. Root tidak boleh null. |

### Nilai Pengembalian

NodeIterator. yang baru dibuat

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dibesarkan jika root yang ditentukan adalah null. |

### Lihat juga

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Buat NodeIterator baru di atas subtree yang di-root pada node yang ditentukan.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| root | Node | simpul yang akan diiterasi bersama dengan anaknya. Iterator awalnya diposisikan tepat sebelum simpul ini. Bendera whatToShow dan filter, jika ada, tidak dipertimbangkan saat menyetel posisi ini. Root tidak boleh null. |
| whatToShow | Int64 | flag menentukan jenis simpul mana yang mungkin muncul di tampilan logis pohon yang disajikan oleh iterator. Lihat the deskripsi NodeFilter untuk kumpulan nilai-nilai yang memungkinkan SHOW_. Bendera ini dapat digabungkan menggunakan ATAU. |

### Nilai Pengembalian

NodeIterator. yang baru dibuat

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dibesarkan jika root yang ditentukan adalah null. |

### Lihat juga

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Buat NodeIterator baru di atas subtree yang di-root pada node yang ditentukan.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| root | Node | simpul yang akan diiterasi bersama dengan anaknya. Iterator awalnya diposisikan tepat sebelum simpul ini. Bendera whatToShow dan filter, jika ada, tidak dipertimbangkan saat menyetel posisi ini. Root tidak boleh null. |
| whatToShow | Int64 | flag menentukan jenis simpul mana yang mungkin muncul di tampilan logis pohon yang disajikan oleh iterator. Lihat the deskripsi NodeFilter untuk kumpulan nilai-nilai yang memungkinkan SHOW_. Bendera ini dapat digabungkan menggunakan ATAU. |
| filter | INodeFilter | NodeFilter untuk digunakan dengan this TreeWalker, atau null untuk menunjukkan tidak ada filter. |

### Nilai Pengembalian

NodeIterator. yang baru dibuat

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dibesarkan jika root yang ditentukan adalah null. |

### Lihat juga

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)


