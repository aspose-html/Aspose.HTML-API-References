---
title: Interface IEventTarget
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Events.IEventTarget antarmuka. ItuEventTarget antarmuka diimplementasikan oleh semua Node dalam implementasi yang mendukung DOM Event Model. Oleh karena itu antarmuka ini dapat diperoleh dengan menggunakan metode pengecoran khusus pengikatan pada instance antarmuka Node. Antarmuka memungkinkan pendaftaran dan penghapusan Pendengar Acara di sebuahEventTarget dan pengiriman acara untuk ituIEventTarget .
type: docs
weight: 810
url: /id/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Itu[`EventTarget`](../../aspose.html.dom/eventtarget/) antarmuka diimplementasikan oleh semua Node dalam implementasi yang mendukung DOM Event Model. Oleh karena itu, antarmuka ini dapat diperoleh dengan menggunakan metode pengecoran khusus pengikatan pada instance antarmuka Node. Antarmuka memungkinkan pendaftaran dan penghapusan Pendengar Acara di sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) dan pengiriman acara untuk itu`IEventTarget` .

```csharp
public interface IEventTarget
```

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Metode ini memungkinkan pengiriman event ke dalam model event implementasi. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* perakitan [Aspose.HTML](../../)


