---
title: "INodeFilter.AcceptNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode INodeFilter. Menguji apakah node tertentu terlihat dalam tampilan logis TreeWalker atau NodeIterator. Fungsi ini akan dipanggil oleh implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil langsung oleh kode pengguna. Namun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk mengarahkan logika aplikasi Anda."
type: docs

url: /id/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Uji apakah sebuah node tertentu terlihat dalam tampilan logis TreeWalker atau NodeIterator. Fungsi ini akan dipanggil oleh implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil secara langsung dari kode pengguna. (Meskipun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk mengarahkan logika aplikasi Anda.)

```java
public short AcceptNode(Node n)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| n | Node | node untuk memeriksa apakah ia melewati filter atau tidak. |

### Nilai Kembali

konstanta untuk menentukan apakah node diterima, ditolak, atau dilewati, seperti yang didefinisikan di atas.

### Lihat Juga

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
