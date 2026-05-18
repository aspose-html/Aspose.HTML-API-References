---
title: "Antarmuka INodeFilter"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.traversal.INodeFilter. Filter adalah objek yang mengetahui cara menyaring node. Jika sebuah NodeIterator atau TreeWalker diberikan sebuah NodeFilter, ia menerapkan filter tersebut sebelum mengembalikan node berikutnya. Jika filter menyatakan untuk menerima node, logika traversal mengembalikannya; jika tidak, traversal mencari node berikutnya dan berperilaku seolah-olah node yang ditolak tidak ada."
type: docs

url: /id/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filter adalah objek yang mengetahui cara "menyaring" node. Jika sebuah NodeIterator atau TreeWalker diberikan NodeFilter, ia menerapkan filter sebelum mengembalikan node berikutnya. Jika filter menyatakan untuk menerima node, logika penelusuran mengembalikannya; jika tidak, penelusuran mencari node berikutnya dan menganggap node yang ditolak tidak ada.

DOM tidak menyediakan filter apa pun. NodeFilter hanyalah sebuah antarmuka yang dapat diimplementasikan pengguna untuk menyediakan filter mereka sendiri.

NodeFilter tidak perlu mengetahui cara menelusuri dari satu node ke node lainnya, juga tidak perlu mengetahui apa pun tentang struktur data yang sedang ditelusuri. Hal ini membuat penulisan filter menjadi sangat mudah, karena satu-satunya hal yang harus mereka ketahui adalah cara mengevaluasi satu node. Satu filter dapat digunakan dengan berbagai jenis traversal, mendorong penggunaan kembali kode.

Lihat juga [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Uji apakah sebuah node tertentu terlihat dalam tampilan logis TreeWalker atau NodeIterator. Fungsi ini akan dipanggil oleh implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil secara langsung dari kode pengguna. (Meskipun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk mengarahkan logika aplikasi Anda.) |

### Lihat Juga

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
