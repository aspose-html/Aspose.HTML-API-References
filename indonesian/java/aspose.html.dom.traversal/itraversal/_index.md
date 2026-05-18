---
title: "Antarmuka ITraversal"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.traversal.ITraversal. Iterator digunakan untuk melangkah melalui sekumpulan node, misalnya sekumpulan node dalam NodeList, subpohon dokumen yang diatur oleh Node tertentu, hasil kueri, atau sekumpulan node lainnya. Sekumpulan node yang akan diiterasi ditentukan oleh implementasi NodeIterator. DOM Level 2 menentukan satu implementasi NodeIterator untuk traversal urutan dokumen pada subpohon dokumen. Instance iterator ini dibuat dengan memanggil DocumentTraversal.createNodeIterator"
type: docs

url: /id/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iterator digunakan untuk melangkah melalui sekumpulan node, misalnya sekumpulan node dalam NodeList, subtree dokumen yang diatur oleh Node tertentu, hasil kueri, atau sekumpulan node lainnya. Sekumpulan node yang akan diiterasi ditentukan oleh implementasi NodeIterator. DOM Level 2 menentukan satu implementasi NodeIterator untuk penelusuran urutan dokumen pada subtree dokumen. Instance iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator().

Lihat juga [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) NodeFilter yang digunakan untuk menyaring node. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Node akar dari NodeIterator, sebagaimana ditentukan saat dibuat. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Atribut ini menentukan tipe node mana yang ditampilkan melalui iterator. Sekumpulan konstanta yang tersedia didefinisikan dalam antarmuka NodeFilter. Node yang tidak diterima oleh whatToShow akan dilewati, namun anak-anaknya masih dapat dipertimbangkan. Perhatikan bahwa pengabaian ini memiliki prioritas lebih tinggi daripada filter, jika ada. |

### Lihat Juga

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
