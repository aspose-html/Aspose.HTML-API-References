---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML untuk Referensi .NET API
description: IDocumentTraversal metode. Buat TreeWalker baru di atas subtree yang diroot di node yang ditentukan.
type: docs
weight: 20
url: /id/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Buat TreeWalker baru di atas subtree yang di-root di node yang ditentukan.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| root | Node | node yang akan berfungsi sebagai root untuk the TreeWalker. Bendera whatToShow dan the NodeFilter tidak dipertimbangkan saat menyetel nilai ini; tipe node apa pun akan diterima sebagai root. The currentNode dari TreeWalker is diinisialisasi ke node ini, apakah terlihat atau tidak. Root berfungsi sebagai titik pemberhentian untuk metode traversal yang mencari ke atas dalam struktur dokumen, seperti parentNode dan nextNode. Akar harus tidak menjadi nol. |

### Nilai Pengembalian

TreeWalker. yang baru dibuat

### Lihat juga

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* ruang nama [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* perakitan [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Buat TreeWalker baru di atas subtree yang di-root di node yang ditentukan.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| root | Node | node yang akan berfungsi sebagai root untuk the TreeWalker. Bendera whatToShow dan the NodeFilter tidak dipertimbangkan saat menyetel nilai ini; tipe node apa pun akan diterima sebagai root. The currentNode dari TreeWalker is diinisialisasi ke node ini, apakah terlihat atau tidak. Root berfungsi sebagai titik pemberhentian untuk metode traversal yang mencari ke atas dalam struktur dokumen, seperti parentNode dan nextNode. Akar harus tidak menjadi nol. |
| whatToShow | Int64 | flag menentukan jenis simpul mana yang mungkin muncul di tampilan logis pohon yang disajikan oleh pejalan pohon. Lihat deskripsi NodeFilter untuk kumpulan nilai-nilai yang mungkin SHOW_. Bendera ini dapat digabungkan menggunakan ATAU. |

### Nilai Pengembalian

TreeWalker. yang baru dibuat

### Lihat juga

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* ruang nama [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* perakitan [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Buat TreeWalker baru di atas subtree yang di-root di node yang ditentukan.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| root | Node | node yang akan berfungsi sebagai root untuk the TreeWalker. Bendera whatToShow dan the NodeFilter tidak dipertimbangkan saat menyetel nilai ini; tipe node apa pun akan diterima sebagai root. The currentNode dari TreeWalker is diinisialisasi ke node ini, apakah terlihat atau tidak. Root berfungsi sebagai titik pemberhentian untuk metode traversal yang mencari ke atas dalam struktur dokumen, seperti parentNode dan nextNode. Akar harus tidak menjadi nol. |
| whatToShow | Int64 | flag menentukan jenis simpul mana yang mungkin muncul di tampilan logis pohon yang disajikan oleh pejalan pohon. Lihat deskripsi NodeFilter untuk kumpulan nilai-nilai yang mungkin SHOW_. Bendera ini dapat digabungkan menggunakan ATAU. |
| filter | INodeFilter | NodeFilter untuk digunakan dengan this TreeWalker, atau null untuk menunjukkan tidak ada filter. |

### Nilai Pengembalian

TreeWalker. yang baru dibuat

### Lihat juga

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* ruang nama [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* perakitan [Aspose.HTML](../../../)


