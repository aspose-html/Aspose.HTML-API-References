---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGListBase. Menyisipkan item baru ke dalam daftar pada posisi yang ditentukan. Item pertama adalah nomor 0"
type: docs

url: /id/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Menyisipkan item baru ke dalam daftar pada posisi yang ditentukan. Item pertama adalah nomor 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newItem | T | Item yang akan disisipkan ke dalam daftar. |
| index | UInt64 | Indeks item sebelum mana item baru akan disisipkan. Item pertama adalah nomor 0. Jika indeks sama dengan 0, maka item baru disisipkan di depan daftar. Jika indeks lebih besar atau sama dengan numberOfItems, maka item baru ditambahkan di akhir daftar. |

### Nilai Kembali

Item yang dimasukkan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Dikeluarkan ketika daftar tidak dapat dimodifikasi. |

### Lihat Juga

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
