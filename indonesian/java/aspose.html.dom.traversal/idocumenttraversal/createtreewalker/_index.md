---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IDocumentTraversal. Membuat TreeWalker baru atas subpohon yang berakar pada node yang ditentukan."
type: docs

url: /id/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Buat TreeWalker baru pada subtree yang berakar di node yang ditentukan.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| root | Node | node yang akan menjadi root untuk TreeWalker. Bendera whatToShow dan NodeFilter tidak dipertimbangkan saat menetapkan nilai ini; semua tipe node akan diterima sebagai root. currentNode dari TreeWalker diinisialisasi ke node ini, terlepas dari apakah node tersebut terlihat atau tidak. Root berfungsi sebagai titik berhenti bagi metode traversal yang melihat ke atas dalam struktur dokumen, seperti parentNode dan nextNode. Root tidak boleh null. |

### Nilai Kembali

TreeWalker yang baru dibuat.

### Lihat Juga

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Buat TreeWalker baru pada subtree yang berakar di node yang ditentukan.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| root | Node | node yang akan menjadi root untuk TreeWalker. Bendera whatToShow dan NodeFilter tidak dipertimbangkan saat menetapkan nilai ini; semua tipe node akan diterima sebagai root. currentNode dari TreeWalker diinisialisasi ke node ini, terlepas dari apakah node tersebut terlihat atau tidak. Root berfungsi sebagai titik berhenti bagi metode traversal yang melihat ke atas dalam struktur dokumen, seperti parentNode dan nextNode. Root tidak boleh null. |
| whatToShow | Int64 | flag menentukan jenis node mana yang dapat muncul dalam tampilan logis pohon yang disajikan oleh tree-walker. Lihat deskripsi NodeFilter untuk kumpulan nilai SHOW_ yang mungkin. Flag ini dapat digabungkan menggunakan OR. |

### Nilai Kembali

TreeWalker yang baru dibuat.

### Lihat Juga

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Buat TreeWalker baru pada subtree yang berakar di node yang ditentukan.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| root | Node | node yang akan menjadi root untuk TreeWalker. Bendera whatToShow dan NodeFilter tidak dipertimbangkan saat menetapkan nilai ini; semua tipe node akan diterima sebagai root. currentNode dari TreeWalker diinisialisasi ke node ini, terlepas dari apakah node tersebut terlihat atau tidak. Root berfungsi sebagai titik berhenti bagi metode traversal yang melihat ke atas dalam struktur dokumen, seperti parentNode dan nextNode. Root tidak boleh null. |
| whatToShow | Int64 | flag menentukan jenis node mana yang dapat muncul dalam tampilan logis pohon yang disajikan oleh tree-walker. Lihat deskripsi NodeFilter untuk kumpulan nilai SHOW_ yang mungkin. Flag ini dapat digabungkan menggunakan OR. |
| filter | INodeFilter | NodeFilter yang akan digunakan dengan TreeWalker ini, atau null untuk menunjukkan tidak ada filter. |

### Nilai Kembali

TreeWalker yang baru dibuat.

### Lihat Juga

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
