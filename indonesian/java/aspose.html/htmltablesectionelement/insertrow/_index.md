---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode HTMLTableSectionElement. Menyisipkan baris ke dalam bagian ini. Baris baru disisipkan tepat sebelum baris ke-index saat ini dalam bagian ini. Jika indeks adalah -1 atau sama dengan jumlah baris dalam bagian ini, baris baru akan ditambahkan di akhir"
type: docs

url: /id/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Sisipkan sebuah baris ke dalam bagian ini. Baris baru disisipkan tepat sebelum baris ke-`index` saat ini dalam bagian ini. Jika `index` adalah -1 atau sama dengan jumlah baris dalam bagian ini, baris baru akan ditambahkan di akhir.

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Nomor baris tempat menyisipkan baris baru. Indeks ini dimulai dari 0 dan hanya relatif terhadap baris yang terdapat di dalam bagian ini, bukan semua baris dalam tabel. |

### Nilai Kembali

The newly created row.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Dikeluarkan jika indeks yang ditentukan lebih besar dari jumlah baris atau jika indeks adalah angka negatif selain -1. @version DOM Level 2 |

### Lihat Juga

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
