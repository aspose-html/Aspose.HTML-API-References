---
title: "SVGListBase-1.Item"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti SVGListBase. Mengembalikan item pada indeks ke‑n dalam daftar"
type: docs

url: /id/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Mengembalikan item pada indeks ke‑n dalam daftar.

```java
public T this[ulong index] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| index | Indeks dalam daftar. |

### Nilai Kembali

Objek yang disimpan pada posisi indeks ke‑n dalam daftar.

### Property Value

Tipe item yang disimpan dalam daftar.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Dikeluarkan ketika daftar tidak dapat dimodifikasi. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Dikeluarkan jika nomor indeks lebih besar atau sama dengan numberOfItems. |

### Lihat Juga

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
