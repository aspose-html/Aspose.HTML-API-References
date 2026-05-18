---
title: "Antarmuka IEventTarget"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.events.IEventTarget. Antarmuka EventTarget diimplementasikan oleh semua Node dalam sebuah implementasi yang mendukung Model Peristiwa DOM. Oleh karena itu antarmuka ini dapat diperoleh dengan menggunakan metode casting khusus binding pada sebuah instance dari antarmuka Node. Antarmuka ini memungkinkan pendaftaran dan penghapusan Event Listener serta pengiriman peristiwa ke sana."
type: docs

url: /id/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Antarmuka EventTarget diimplementasikan oleh semua Node dalam sebuah implementasi yang mendukung Model Peristiwa DOM. Oleh karena itu, antarmuka ini dapat diperoleh dengan menggunakan metode casting spesifik binding pada sebuah instance dari antarmuka Node. Antarmuka ini memungkinkan pendaftaran dan penghapusan Event Listener pada sebuah dan pengiriman peristiwa ke sana.

```java
public interface IEventTarget
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Metode EventTarget addEventListener() menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Metode EventTarget addEventListener() menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Mengirimkan sebuah Event ke EventTarget yang ditentukan, (secara sinkron) memanggil EventListener yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan peristiwa normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk peristiwa yang dikirim secara manual dengan dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus. |

### Lihat Juga

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
