---
title: "Kelas MediaQueryList"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.window.MediaQueryList. Sebuah objek MediaQueryList menyimpan informasi tentang kueri media yang diterapkan pada dokumen dengan dukungan untuk pencocokan langsung maupun berbasis peristiwa terhadap status dokumen. Lihat spesifikasi CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /id/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Objek MediaQueryList menyimpan informasi tentang kueri media yang diterapkan pada dokumen, dengan dukungan untuk pencocokan langsung maupun berbasis peristiwa terhadap status dokumen. Lihat spesifikasi CSSOM View Module: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Dokumen yang terkait dengan objek konteks. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Nilai boolean yang mengembalikan true jika dokumen saat ini cocok dengan daftar kueri media, atau false jika tidak. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Sebuah String yang mewakili kueri media yang diserialkan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Metode addEventListener() dari antarmuka [`EventTarget `](../../com.aspose.html.dom/eventtarget/) menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Tambahkan pendengar peristiwa perubahan status cocok MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Menyebarkan sebuah Event pada [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang ditentukan, (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk event yang disebarkan secara manual dengan [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Hapus pendengar peristiwa perubahan status cocok MediaQueryList. |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Peristiwa yang dipicu pada MediaQueryList ketika status cocok berubah. |

### Lihat Juga

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
