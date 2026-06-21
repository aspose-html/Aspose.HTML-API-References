---
title: "NodeFilter.AcceptNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode NodeFilter. Menguji apakah sebuah node tertentu terlihat dalam tampilan logis TreeWalker atau NodeIterator. Fungsi ini akan dipanggil oleh implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil secara langsung dari kode pengguna. Namun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk membimbing logika aplikasi Anda."
type: docs

url: /id/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Uji apakah sebuah node tertentu terlihat dalam tampilan logis TreeWalker atau NodeIterator. Fungsi ini akan dipanggil oleh implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil secara langsung dari kode pengguna. (Meskipun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk mengarahkan logika aplikasi Anda.)

```java
public abstract short AcceptNode(Node n)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| n | Node | node untuk memeriksa apakah ia melewati filter atau tidak. |

### Nilai Kembali

konstanta untuk menentukan apakah node diterima, ditolak, atau dilewati, sebagaimana didefinisikan di atas.

### Lihat Juga

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)
