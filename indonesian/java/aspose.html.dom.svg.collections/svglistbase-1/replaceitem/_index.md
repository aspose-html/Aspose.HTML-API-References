---
title: "SVGListBase-1.ReplaceItem"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGListBase. Mengganti item yang ada dalam daftar dengan item baru"
type: docs

url: /id/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Mengganti item yang ada dalam daftar dengan item baru.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newItem | T | Item yang akan disisipkan ke dalam daftar. |
| index | UInt64 | Indeks item yang akan diganti. Item pertama adalah nomor 0. |

### Nilai Kembali

Item yang dimasukkan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Dikeluarkan ketika daftar tidak dapat dimodifikasi. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Dikeluarkan jika nomor indeks lebih besar atau sama dengan numberOfItems. |

### Lihat Juga

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
