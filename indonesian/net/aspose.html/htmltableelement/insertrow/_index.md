---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML untuk Referensi .NET API
description: HTMLTableElement metode. Masukkan baris kosong baru ke dalam tabel. Baris baru dimasukkan tepat sebelum dan di bagian yang sama dengan saat iniindeks baris keth dalam tabel. Jikaindeks adalah 1 atau sama dengan jumlah baris baris baru ditambahkan. Selain itu saat tabel kosong baris disisipkan ke aTBODY yang dibuat dan dimasukkan ke dalam tabel. Baris tabel tidak boleh kosong menurut HTML4.01 .
type: docs
weight: 220
url: /id/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Masukkan baris kosong baru ke dalam tabel. Baris baru dimasukkan tepat sebelum dan di bagian yang sama dengan saat ini`indeks` baris ke-th dalam tabel. Jika`indeks` adalah -1 atau sama dengan jumlah baris, baris baru ditambahkan. Selain itu, saat tabel kosong, baris disisipkan ke a`TBODY` yang dibuat dan dimasukkan ke dalam tabel. Baris tabel tidak boleh kosong menurut [[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| index | Int32 | Nomor baris tempat menyisipkan baris baru. Indeks ini dimulai dari 0 dan relatif terhadap urutan logis (bukan urutan dokumen ) dari semua baris yang terdapat di dalam tabel. |

### Nilai Pengembalian

Baris yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Dibesarkan jika indeks yang ditentukan lebih besar dari jumlah baris atau jika indeks adalah angka negatif selain -1. @version DOM Level 2 |

### Lihat juga

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* ruang nama [Aspose.Html](../../htmltableelement/)
* perakitan [Aspose.HTML](../../../)


