---
title: "Node.RemoveChild"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Node. Metode removeChild dari antarmuka Node menghapus node anak dari DOM dan mengembalikan node yang dihapus."
type: docs

url: /id/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Metode removeChild() pada antarmuka Node menghapus node anak dari DOM dan mengembalikan node yang dihapus.

Catatan: Selama referensi pada anak yang dihapus dipertahankan, ia masih ada di memori, tetapi tidak lagi menjadi bagian dari DOM. Ia masih dapat digunakan kembali nanti dalam kode. Jika nilai kembali dari removeChild() tidak disimpan, dan tidak ada referensi lain yang dipertahankan, maka ia akan secara otomatis dihapus dari memori setelah waktu singkat.

```java
public Node RemoveChild(Node child)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| child | Node | Sebuah [`Node`](../) yang merupakan node anak yang akan dihapus dari DOM. |

### Nilai Kembali

Berbeda dengan [`Node.cloneNode()`](../clonenode/) nilai kembali mempertahankan objek [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) yang terkait dengannya.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
