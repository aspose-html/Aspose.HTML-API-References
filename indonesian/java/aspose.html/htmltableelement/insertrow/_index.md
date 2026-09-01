---
title: "HTMLTableElement.InsertRow"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "HTMLTableElement method. Menyisipkan baris baru yang kosong ke dalam tabel. Baris baru disisipkan tepat sebelum dan dalam bagian yang sama dengan baris indeks saat ini dalam tabel. Jika indeks adalah -1 atau sama dengan jumlah baris, baris baru ditambahkan di akhir. Selain itu, ketika tabel kosong, baris disisipkan ke dalam sebuah TBODY yang dibuat dan disisipkan ke dalam tabel. Baris tabel tidak boleh kosong menurut HTML 4.01"
type: docs

url: /id/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Sisipkan baris kosong baru ke dalam tabel. Baris baru disisipkan tepat sebelum dan di bagian yang sama dengan baris ke-`index` saat ini dalam tabel. Jika `index` bernilai -1 atau sama dengan jumlah baris, baris baru akan ditambahkan di akhir. Selain itu, ketika tabel kosong, baris tersebut disisipkan ke dalam `TBODY` yang dibuat dan dimasukkan ke dalam tabel. Baris tabel tidak boleh kosong menurut [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Nomor baris tempat menyisipkan baris baru. Indeks ini dimulai dari 0 dan relatif terhadap urutan logis (bukan urutan dokumen) semua baris yang terdapat di dalam tabel. |

### Nilai Kembali

Baris yang baru dibuat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Dikeluarkan jika indeks yang ditentukan lebih besar dari jumlah baris atau jika indeks adalah angka negatif selain -1. @version DOM Level 2 |

### Lihat Juga

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
