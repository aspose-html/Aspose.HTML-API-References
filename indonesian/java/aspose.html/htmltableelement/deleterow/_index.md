---
title: "HTMLTableElement.DeleteRow"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode HTMLTableElement. Menghapus baris tabel."
type: docs

url: /id/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Hapus baris tabel.

```java
public void DeleteRow(int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks baris yang akan dihapus. Indeks ini dimulai dari 0 dan relatif terhadap urutan logis (bukan urutan dokumen) semua baris yang terdapat di dalam tabel. Jika indeksnya -1, baris terakhir dalam tabel akan dihapus. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Dikeluarkan jika indeks yang ditentukan lebih besar dari atau sama dengan jumlah baris atau jika indeks adalah angka negatif selain -1. @version DOM Level 2 |

### Lihat Juga

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
