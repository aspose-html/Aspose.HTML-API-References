---
title: "Antarmuka IEventTarget"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.dom.events.IEventTarget. Antarmuka EventTarget diimplementasikan oleh semua Node dalam sebuah implementasi yang mendukung Model Peristiwa DOM. Oleh karena itu antarmuka ini dapat diperoleh dengan menggunakan metode casting khusus binding pada sebuah instance antarmuka Node. Antarmuka ini memungkinkan pendaftaran dan penghapusan Event Listener serta pengiriman peristiwa ke sana."
type: docs

url: /id/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Antarmuka EventTarget diimplementasikan oleh semua Node dalam implementasi yang mendukung Model Peristiwa DOM. Oleh karena itu, antarmuka ini dapat diperoleh dengan menggunakan metode casting khusus binding pada sebuah instance antarmuka Node. Antarmuka ini memungkinkan pendaftaran dan penghapusan Event Listener pada sebuah objek serta pengiriman peristiwa ke objek tersebut.

```java
public interface IEventTarget
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Metode EventTarget addEventListener() menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan disampaikan ke target. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Metode EventTarget addEventListener() menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan disampaikan ke target. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Mengirimkan sebuah Event ke EventTarget yang ditentukan, (secara sinkron) memanggil EventListener yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan peristiwa normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk peristiwa yang dikirim secara manual dengan dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |

### Lihat Juga

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
