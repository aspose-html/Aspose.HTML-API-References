---
title: "Kelas EventTarget"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.EventTarget. Antarmuka EventTarget diimplementasikan oleh objek yang dapat menerima peristiwa dan mungkin memiliki pendengar untuknya. Dengan kata lain, setiap target peristiwa mengimplementasikan tiga metode yang terkait dengan antarmuka ini."
type: docs

url: /id/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

Antarmuka **EventTarget** diimplementasikan oleh objek yang dapat menerima peristiwa dan mungkin memiliki pendengar untuknya. Dengan kata lain, setiap target peristiwa mengimplementasikan tiga metode yang terkait dengan antarmuka ini.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EventTarget](eventtarget/)() | Menginisialisasi instance baru dari objek EventTarget. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | Metode addEventListener() dari antarmuka `EventTarget `menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Menyebarkan sebuah Event pada [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang ditentukan, (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk event yang disebarkan secara manual dengan [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |

### Lihat Juga

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
