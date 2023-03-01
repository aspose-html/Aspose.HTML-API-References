---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML untuk Referensi .NET API
description: SVGListBase metode. Mengganti item yang ada dalam daftar dengan item baru.
type: docs
weight: 110
url: /id/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Mengganti item yang ada dalam daftar dengan item baru.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newItem | T | Item yang akan dimasukkan ke dalam daftar. |
| index | UInt64 | Indeks item yang akan diganti. Item pertama adalah nomor 0. |

### Nilai Pengembalian

Item yang dimasukkan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Dimunculkan saat daftar tidak dapat diubah. |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Dimunculkan jika nomor indeks lebih besar atau sama dengan jumlahItem. |

### Lihat juga

* class [SVGListBase&lt;T&gt;](../)
* ruang nama [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* perakitan [Aspose.HTML](../../../)


