---
title: "IDocumentEvent.CreateEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IDocumentEvent. Metode createEvent digunakan untuk membuat Event ketika tidak praktis atau tidak diperlukan bagi pengguna untuk membuat Event sendiri."
type: docs

url: /id/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Metode createEvent digunakan untuk membuat Event ketika tidak praktis atau tidak diperlukan bagi pengguna untuk membuat Event sendiri.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | String | Parameter eventType menentukan tipe antarmuka yang akan dibuat. Jika antarmuka yang ditentukan didukung oleh implementasi, metode ini akan mengembalikan sebuah objek baru dari tipe antarmuka yang diminta. Jika yang akan disebarkan melalui metode tersebut, metode yang tepat harus dipanggil setelah pembuatan untuk menginisialisasi nilai-nilai. Metode ini digunakan untuk membuat s ketika tidak praktis atau tidak diperlukan bagi pengguna untuk membuatnya sendiri. Dalam kasus di mana implementasi yang disediakan tidak memadai, pengguna dapat menyediakan implementasi mereka sendiri untuk digunakan dengan metode tersebut. |

### Nilai Kembali

Mengembalikan event yang baru dibuat dengan tipe event yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika implementasi tidak mendukung tipe antarmuka yang diminta |

### Lihat Juga

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
