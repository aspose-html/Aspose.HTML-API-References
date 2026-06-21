---
title: "SVGSVGElement.CreateEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGSVGElement. Membuat sebuah Event dengan tipe yang didukung oleh implementasi."
type: docs

url: /id/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Membuat sebuah [`Event`](../../../com.aspose.html.dom.events/event/) dengan tipe yang didukung oleh implementasi.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | String | Parameter eventType menentukan jenis antarmuka [`Event`](../../../com.aspose.html.dom.events/event/) yang akan dibuat. Jika antarmuka [`Event`](../../../com.aspose.html.dom.events/event/) yang ditentukan didukung oleh implementasi, metode ini akan mengembalikan sebuah [`Event`](../../../com.aspose.html.dom.events/event/) baru dengan jenis antarmuka yang diminta. Jika [`Event`](../../../com.aspose.html.dom.events/event/) akan dikirim melalui metode [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) metode [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) yang sesuai harus dipanggil setelah pembuatan untuk menginisialisasi nilai-nilai [`Event`](../../../com.aspose.html.dom.events/event/). |

### Nilai Kembali

[`Event`](../../../com.aspose.html.dom.events/event/) yang baru dibuat

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Dikeluarkan jika implementasi tidak mendukung jenis antarmuka [`Event`](../../../com.aspose.html.dom.events/event/) yang diminta |

### Lihat Juga

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
