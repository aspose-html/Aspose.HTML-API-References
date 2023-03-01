---
title: SVGSVGElement.CreateEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: SVGSVGElement metode. Membuat sebuahEvent dari jenis yang didukung oleh implementasi.
type: docs
weight: 110
url: /id/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Membuat sebuah[`Event`](../../../aspose.html.dom.events/event/) dari jenis yang didukung oleh implementasi.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| eventType | String | Parameter eventType menentukan tipe dari[`Event`](../../../aspose.html.dom.events/event/) antarmuka yang akan dibuat.  Jika[`Event`](../../../aspose.html.dom.events/event/)antarmuka yang ditentukan didukung oleh implementasi metode ini akan mengembalikan new [`Event`](../../../aspose.html.dom.events/event/) dari jenis antarmuka yang diminta. Jika[`Event`](../../../aspose.html.dom.events/event/)akan dikirim melalui[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) metode yang sesuai [`InitEvent`](../../../aspose.html.dom.events/event/initevent/) metode harus dipanggil setelah pembuatan untuk menginisialisasi[`Event`](../../../aspose.html.dom.events/event/) nilai s. |

### Nilai Pengembalian

Yang baru dibuat[`Event`](../../../aspose.html.dom.events/event/)

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Dimunculkan jika implementasi tidak mendukung jenis[`Event`](../../../aspose.html.dom.events/event/) antarmuka diminta |

### Lihat juga

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* ruang nama [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* perakitan [Aspose.HTML](../../../)


