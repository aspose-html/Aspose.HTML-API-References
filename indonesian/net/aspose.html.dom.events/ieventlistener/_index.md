---
title: Interface IEventListener
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Events.IEventListener antarmuka. ItuIEventListenerantarmuka adalah metode utama untuk menangani peristiwa. Pengguna mengimplementasikanIEventListener antarmuka dan mendaftarkan pendengar mereka pada sebuahEventTarget menggunakanAddEventListener method. Pengguna juga harus menghapusnyaIEventListener dari ituEventTarget setelah selesai menggunakan listener.
type: docs
weight: 800
url: /id/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Itu`IEventListener`antarmuka adalah metode utama untuk menangani peristiwa. Pengguna mengimplementasikan`IEventListener` antarmuka dan mendaftarkan pendengar mereka pada sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) menggunakan[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. Pengguna juga harus menghapusnya`IEventListener` dari itu[`EventTarget`](../../aspose.html.dom/eventtarget/) setelah selesai menggunakan listener.

```csharp
public interface IEventListener
```

## Metode

| Nama | Keterangan |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Metode ini dipanggil setiap kali terjadi peristiwa dari jenis yang`IEventListener` antarmuka telah terdaftar. |

### Perkataan

Ketika Node disalin menggunakan metode cloneNode, Pendengar Acara yang dilampirkan ke Node sumber tidak dilampirkan ke Node yang disalin. Jika pengguna menginginkan Pendengar Acara yang sama ditambahkan ke salinan yang baru dibuat, pengguna harus menambahkannya secara manual.

### Lihat juga

* ruang nama [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* perakitan [Aspose.HTML](../../)


