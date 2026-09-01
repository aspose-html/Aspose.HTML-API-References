---
title: "Antarmuka INodeIterator"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.traversal.INodeIterator. Iterator digunakan untuk melangkah melalui sekumpulan node, misalnya sekumpulan node dalam NodeList, subtree dokumen yang diatur oleh Node tertentu, hasil kueri, atau sekumpulan node lainnya. Sekumpulan node yang akan diiterasi ditentukan oleh implementasi NodeIterator. DOM Level 2 menentukan satu implementasi NodeIterator untuk penelusuran urutan dokumen pada subtree dokumen. Instance iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator."
type: docs

url: /id/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterator digunakan untuk melangkah melalui sekumpulan node, misalnya sekumpulan node dalam NodeList, subtree dokumen yang diatur oleh Node tertentu, hasil kueri, atau sekumpulan node lainnya. Sekumpulan node yang akan diiterasi ditentukan oleh implementasi NodeIterator. DOM Level 2 menentukan satu implementasi NodeIterator untuk penelusuran urutan dokumen pada subtree dokumen. Instance iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator().

Lihat juga [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Nilai flag ini menentukan apakah anak‑anak dari node referensi entitas terlihat oleh iterator. Jika false, mereka dan keturunan mereka akan ditolak. Perhatikan bahwa penolakan ini memiliki prioritas lebih tinggi daripada whatToShow dan filter. Juga perhatikan bahwa ini saat ini satu‑satunya situasi di mana NodeIterators dapat menolak seluruh subtree alih‑alih melewati node individu. Untuk menghasilkan tampilan dokumen yang memiliki referensi entitas yang diperluas dan tidak menampilkan node referensi entitas itu sendiri, gunakan flag whatToShow untuk menyembunyikan node referensi entitas dan setel expandEntityReferences ke true saat membuat iterator. Untuk menghasilkan tampilan dokumen yang memiliki node referensi entitas tetapi tanpa ekspansi entitas, gunakan flag whatToShow untuk menampilkan node referensi entitas dan setel expandEntityReferences ke false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Node referensi saat ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Melepaskan NodeIterator dari set yang telah diiterasinya, membebaskan semua sumber daya komputasi dan menempatkan iterator dalam keadaan INVALID. Setelah detach dipanggil, panggilan ke nextNode atau previousNode akan menghasilkan pengecualian INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Mengembalikan node berikutnya dalam set dan memajukan posisi iterator dalam set. Setelah NodeIterator dibuat, panggilan pertama ke nextNode() mengembalikan node pertama dalam set. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Mengembalikan node sebelumnya dalam set dan memindahkan posisi NodeIterator mundur dalam set. |

### Lihat Juga

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
