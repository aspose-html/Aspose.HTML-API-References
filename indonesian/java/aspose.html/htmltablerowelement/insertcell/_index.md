---
title: "HTMLTableRowElement.InsertCell"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode HTMLTableRowElement. Menyisipkan sel TD kosong ke dalam baris ini. Jika index adalah -1 atau sama dengan jumlah sel, sel baru akan ditambahkan di akhir"
type: docs

url: /id/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Sisipkan sel `TD` kosong ke dalam baris ini. Jika `index` bernilai -1 atau sama dengan jumlah sel, sel baru akan ditambahkan di akhir.

```java
public HTMLElement InsertCell(int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Tempat untuk menyisipkan sel, dimulai dari 0. |

### Nilai Kembali

Sel yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Dikeluarkan jika `index` yang ditentukan lebih besar dari jumlah sel atau jika index adalah angka negatif selain -1. @version DOM Level 2 |

### Lihat Juga

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
