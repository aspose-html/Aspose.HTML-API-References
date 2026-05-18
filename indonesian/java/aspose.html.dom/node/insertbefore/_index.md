---
title: "Node.InsertBefore"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Node. Metode insertBefore dari antarmuka Node menyisipkan sebuah node sebelum node referensi sebagai anak dari node induk yang ditentukan."
type: docs

url: /id/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

Metode insertBefore() dari antarmuka Node menyisipkan sebuah node sebelum node referensi sebagai anak dari node induk yang ditentukan.

Jika node yang diberikan sudah ada dalam dokumen, insertBefore() memindahkannya dari posisi saat ini ke posisi baru. (Artinya, node tersebut secara otomatis akan dihapus dari induknya yang ada sebelum ditambahkan ke induk baru yang ditentukan.)

Ini berarti sebuah node tidak dapat berada di dua lokasi dalam dokumen secara bersamaan.

```java
public Node InsertBefore(Node node, Node child)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node yang akan disisipkan. |
| anak | Node | Node sebelum mana newNode disisipkan. Jika ini null, maka newNode disisipkan di akhir node anak. |

### Nilai Kembali

Mengembalikan anak yang ditambahkan (kecuali newNode adalah sebuah [`DocumentFragment`](../../documentfragment/), dalam hal ini [`DocumentFragment`](../../documentfragment/) kosong yang dikembalikan).

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
