---
title: "SVGListBase-1.RemoveItem"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGListBase. Menghapus item yang ada dari daftar."
type: docs

url: /id/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Menghapus item yang ada dari daftar.

```java
public T RemoveItem(ulong index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | UInt64 | Indeks item yang akan dihapus. Item pertama memiliki nomor 0. |

### Nilai Kembali

Item yang dihapus.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Dikeluarkan ketika daftar tidak dapat dimodifikasi. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Dikeluarkan jika nomor indeks lebih besar atau sama dengan numberOfItems. |

### Lihat Juga

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
