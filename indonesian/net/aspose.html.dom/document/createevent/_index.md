---
title: Document.CreateEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: Document metode. Membuat sebuahEvent dari jenis yang didukung oleh implementasi.
type: docs
weight: 880
url: /id/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Membuat sebuah[`Event`](../../../aspose.html.dom.events/event/) dari jenis yang didukung oleh implementasi.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| eventType | String | Parameter eventType menentukan tipe dari[`Event`](../../../aspose.html.dom.events/event/) antarmuka yang akan dibuat.  Jika[`Event`](../../../aspose.html.dom.events/event/) antarmuka yang ditentukan didukung oleh implementasi metode ini will mengembalikan yang baru[`Event`](../../../aspose.html.dom.events/event/) dari jenis antarmuka yang diminta. Jika[`Event`](../../../aspose.html.dom.events/event/)akan dikirim melalui[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) metode yang sesuai[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) Metode harus dipanggil setelah pembuatan untuk menginisialisasi[`Event`](../../../aspose.html.dom.events/event/) nilai s. |

### Nilai Pengembalian

Yang baru dibuat[`Event`](../../../aspose.html.dom.events/event/)

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Dimunculkan jika implementasinya tidak mendukung jenis[`Event`](../../../aspose.html.dom.events/event/) antarmuka yang diminta |

### Lihat juga

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)


