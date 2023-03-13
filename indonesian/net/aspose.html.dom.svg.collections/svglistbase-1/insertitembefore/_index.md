---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML untuk Referensi .NET API
description: SVGListBase metode. Menyisipkan item baru ke dalam daftar pada posisi yang ditentukan. Item pertama adalah nomor 0.
type: docs
weight: 90
url: /id/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Menyisipkan item baru ke dalam daftar pada posisi yang ditentukan. Item pertama adalah nomor 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newItem | T | Item yang akan dimasukkan ke dalam daftar. |
| index | UInt64 | Indeks item sebelum item baru disisipkan. Item pertama adalah angka 0. Jika indeks sama dengan 0, maka item baru disisipkan paling depan dari daftar. Jika indeks lebih besar dari atau sama dengan numberOfItems, item baru ditambahkan ke akhir daftar. |

### Nilai Pengembalian

Item yang dimasukkan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Dimunculkan saat daftar tidak dapat diubah. |

### Lihat juga

* class [SVGListBase&lt;T&gt;](../)
* ruang nama [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* perakitan [Aspose.HTML](../../../)


