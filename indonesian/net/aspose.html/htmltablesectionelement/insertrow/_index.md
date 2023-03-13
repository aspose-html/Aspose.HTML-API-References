---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML untuk Referensi .NET API
description: HTMLTableSectionElement metode. Masukkan baris ke bagian ini. Baris baru dimasukkan segera sebelum arusindeks baris keth di bagian ini. Jika indeks adalah 1 atau sama dengan jumlah baris di bagian ini baris baru ditambahkan.
type: docs
weight: 70
url: /id/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Masukkan baris ke bagian ini. Baris baru dimasukkan segera sebelum arus`indeks` baris ke-th di bagian ini. Jika `indeks` adalah -1 atau sama dengan jumlah baris di bagian ini, baris baru ditambahkan.

```csharp
public HTMLElement InsertRow(int index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| index | Int32 | Nomor baris tempat menyisipkan baris baru. Indeks ini dimulai dari 0 dan relatif hanya untuk baris yang terdapat di dalam bagian ini, tidak semua baris dalam tabel. |

### Nilai Pengembalian

Baris yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Dibesarkan jika indeks yang ditentukan lebih besar dari jumlah baris jika indeks adalah angka negatif selain -1. @version DOM Level 2 |

### Lihat juga

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* ruang nama [Aspose.Html](../../htmltablesectionelement/)
* perakitan [Aspose.HTML](../../../)


