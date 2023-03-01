---
title: Class EventTarget
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.EventTarget kelas. ItuEventTarget antarmuka diimplementasikan oleh semua Node dalam implementasi yang mendukung DOM Event Model. Oleh karena itu antarmuka ini dapat diperoleh dengan menggunakan metode pengecoran khusus pengikatan pada instance antarmuka Node. Antarmuka memungkinkan pendaftaran dan penghapusan Pendengar Acara di sebuahEventTarget dan pengiriman acara untuk ituIEventTarget .
type: docs
weight: 720
url: /id/net/aspose.html.dom/eventtarget/
---
## EventTarget class

Itu`EventTarget` antarmuka diimplementasikan oleh semua Node dalam implementasi yang mendukung DOM Event Model. Oleh karena itu, antarmuka ini dapat diperoleh dengan menggunakan metode pengecoran khusus pengikatan pada instance antarmuka Node. Antarmuka memungkinkan pendaftaran dan penghapusan Pendengar Acara di sebuah`EventTarget` dan pengiriman acara untuk itu[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Metode ini memungkinkan pengiriman event ke dalam model event implementasi. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah`EventTarget` saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah`EventTarget` saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah`EventTarget` saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |

### Lihat juga

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* ruang nama [Aspose.Html.Dom](../../aspose.html.dom/)
* perakitan [Aspose.HTML](../../)


