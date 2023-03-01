---
title: Document.CreateTreeWalker
second_title: Aspose.HTML untuk Referensi .NET API
description: Document metode. Buat TreeWalker baru di atas subtree yang diroot di node yang ditentukan.
type: docs
weight: 940
url: /id/net/aspose.html.dom/document/createtreewalker/
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

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dibesarkan jika root yang ditentukan adalah null. |

### Lihat juga

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
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

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dibesarkan jika root yang ditentukan adalah null. |

### Lihat juga

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
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

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dibesarkan jika root yang ditentukan adalah null. |

### Lihat juga

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)


