---
title: "Antarmuka ITreeWalker"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.traversal.ITreeWalker. Objek TreeWalker digunakan untuk menavigasi pohon dokumen atau subpohon menggunakan tampilan dokumen yang ditentukan oleh flag whatToShow mereka dan filter jika ada. Setiap fungsi yang melakukan navigasi menggunakan TreeWalker secara otomatis akan mendukung tampilan apa pun yang didefinisikan oleh TreeWalker."
type: docs

url: /id/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Objek TreeWalker digunakan untuk menavigasi pohon dokumen atau subtree menggunakan tampilan dokumen yang didefinisikan oleh flag whatToShow dan filter mereka (jika ada). Setiap fungsi yang melakukan navigasi menggunakan TreeWalker secara otomatis akan mendukung tampilan apa pun yang didefinisikan oleh TreeWalker.

Menghilangkan node dari tampilan logis sebuah subpohon dapat menghasilkan struktur yang secara substansial berbeda dari subpohon yang sama dalam dokumen lengkap yang tidak difilter. Node yang bersaudara dalam tampilan TreeWalker mungkin menjadi anak dari node yang berbeda, jauh terpisah, dalam tampilan asli. Misalnya, pertimbangkan sebuah NodeFilter yang melewatkan semua node kecuali node Teks dan node akar dokumen. Dalam tampilan logis yang dihasilkan, semua node teks akan menjadi saudara dan muncul sebagai anak langsung node akar, tidak peduli seberapa dalam struktur dokumen asli.

Lihat juga [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Properti

| Nama | Deskripsi |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Memindahkan TreeWalker ke anak pertama yang terlihat dari node saat ini, dan mengembalikan node baru. Jika node saat ini tidak memiliki anak yang terlihat, mengembalikan null, dan mempertahankan node saat ini. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Memindahkan TreeWalker ke anak terakhir yang terlihat dari node saat ini, dan mengembalikan node baru. Jika node saat ini tidak memiliki anak yang terlihat, mengembalikan null, dan mempertahankan node saat ini. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Memindahkan TreeWalker ke node berikutnya yang terlihat dalam urutan dokumen relatif terhadap node saat ini, dan mengembalikan node baru. Jika node saat ini tidak memiliki node berikutnya, atau jika pencarian nextNode mencoba melangkah ke atas dari node akar TreeWalker, mengembalikan null, dan mempertahankan node saat ini. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Memindahkan TreeWalker ke saudara berikutnya yang terlihat dari node saat ini, dan mengembalikan node baru. Jika node saat ini tidak memiliki saudara berikutnya yang terlihat, mengembalikan null, dan mempertahankan node saat ini. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Berpindah ke dan mengembalikan node nenek moyang terdekat yang terlihat dari node saat ini. Jika pencarian parentNode mencoba melangkah ke atas dari node akar TreeWalker, atau jika tidak menemukan node nenek moyang yang terlihat, metode ini mempertahankan posisi saat ini dan mengembalikan null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Memindahkan TreeWalker ke node terlihat sebelumnya dalam urutan dokumen relatif terhadap node saat ini, dan mengembalikan node baru. Jika node saat ini tidak memiliki node sebelumnya, atau jika pencarian previousNode mencoba naik dari node akar TreeWalker, mengembalikan null, dan mempertahankan node saat ini. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Memindahkan TreeWalker ke saudara sebelumnya dari node saat ini, dan mengembalikan node baru. Jika node saat ini tidak memiliki saudara sebelumnya yang terlihat, mengembalikan null, dan mempertahankan node saat ini. |

### Lihat Juga

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
