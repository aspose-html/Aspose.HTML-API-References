---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: EventTarget metode. Metode ini memungkinkan pengiriman event ke dalam model event implementasi.
type: docs
weight: 20
url: /id/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Metode ini memungkinkan pengiriman event ke dalam model event implementasi.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| event | Event | Menentukan jenis kejadian, perilaku, dan informasi kontekstual yang akan digunakan dalam memproses kejadian. |

### Nilai Pengembalian

Nilai pengembalian dari`DispatchEvent` menunjukkan apakah ada pendengar yang menangani acara yang dipanggil[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Jika[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) disebut nilainya salah, jika tidak nilainya benar.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Perkataan

Peristiwa yang dikirim dengan cara ini akan memiliki perilaku penangkapan dan gelembung yang sama dengan peristiwa yang dikirim langsung oleh implementasi. Target peristiwa adalah[`EventTarget`](../) di mana`DispatchEvent` disebut.

### Lihat juga

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* ruang nama [Aspose.Html.Dom](../../eventtarget/)
* perakitan [Aspose.HTML](../../../)


