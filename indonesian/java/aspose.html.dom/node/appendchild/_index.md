---
title: "Node.AppendChild"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Node. Metode appendChild dari antarmuka Node menambahkan sebuah node ke akhir daftar anak dari node induk yang ditentukan. Jika anak yang diberikan adalah referensi ke node yang sudah ada dalam dokumen, appendChild memindahkannya dari posisi saat ini ke posisi baru; tidak ada keharusan untuk menghapus node tersebut dari node induknya sebelum menambahkannya ke node lain."
type: docs

url: /id/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

Metode appendChild() dari antarmuka Node menambahkan sebuah node ke akhir daftar anak dari node induk yang ditentukan. Jika anak yang diberikan merupakan referensi ke node yang sudah ada dalam dokumen, appendChild() memindahkannya dari posisi saat ini ke posisi baru (tidak ada keharusan untuk menghapus node dari node induknya sebelum menambahkannya ke node lain).

Ini berarti sebuah node tidak dapat berada di dua titik dalam dokumen secara bersamaan. Jadi jika node sudah memiliki induk, node tersebut pertama-tama dihapus, kemudian ditambahkan di posisi baru. Metode [`Node.cloneNode()`](../clonenode/) dapat digunakan untuk membuat salinan node sebelum menambahkannya ke induk baru. Salinan yang dibuat dengan [`cloneNode`](../clonenode/) tidak secara otomatis disinkronkan.

```java
public Node AppendChild(Node node)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node yang akan ditambahkan ke node induk yang diberikan (biasanya sebuah elemen). |

### Nilai Kembali

Sebuah Node yang merupakan anak yang ditambahkan (aChild), kecuali ketika aChild adalah sebuah [`DocumentFragment`](../../documentfragment/), dalam hal ini [`DocumentFragment`](../../documentfragment/) kosong yang dikembalikan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../domexception/) | Dilemparkan ketika batasan pohon DOM dilanggar. |

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
