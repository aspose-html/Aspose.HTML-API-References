---
title: EventTarget.AddEventListener
second_title: Aspose.HTML untuk Referensi .NET API
description: EventTarget metode. Metode ini memungkinkan pendaftaran event listener pada target event.
type: docs
weight: 10
url: /id/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

Metode ini memungkinkan pendaftaran event listener pada target event.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis peristiwa yang didaftarkan oleh pengguna |
| handler | DOMEventHandler | Mengambil sebuah[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) dipanggil saat peristiwa terjadi. |
| useCapture | Boolean | Jika benar, useCapture menunjukkan bahwa pengguna ingin memulai penangkapan. Setelah memulai penangkapan, semua kejadian dari jenis yang ditentukan akan dikirim ke registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) sebelum dikirim ke Target Peristiwa mana pun di bawahnya di pohon. Peristiwa yang meluap ke atas melalui pohon tidak akan memicu[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ditunjuk untuk menggunakan capture. |

### Perkataan

Jika sebuah[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ditambahkan ke sebuah[`EventTarget`](../) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu selama tahap alur peristiwa selanjutnya, seperti fase gelembung.

Jika beberapa Pemroses Peristiwa identik didaftarkan pada tempat yang sama[`EventTarget`](../)dengan parameter yang sama instance duplikat dibuang. Mereka tidak menyebabkan[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) untuk dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan the [`RemoveEventListener`](../removeeventlistener/) metode.

### Lihat juga

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* ruang nama [Aspose.Html.Dom](../../eventtarget/)
* perakitan [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

Metode ini memungkinkan pendaftaran event listener pada target event.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis peristiwa yang didaftarkan oleh pengguna |
| listener | IEventListener | Mengambil antarmuka yang diimplementasikan oleh pengguna yang berisi metode yang akan dipanggil saat peristiwa terjadi. |

### Perkataan

Jika sebuah[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ditambahkan ke sebuah[`EventTarget`](../) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu selama tahap alur peristiwa selanjutnya, seperti fase gelembung.

Jika beberapa Pemroses Peristiwa identik didaftarkan pada tempat yang sama[`EventTarget`](../)dengan parameter yang sama instance duplikat dibuang. Mereka tidak menyebabkan[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) untuk dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan the [`RemoveEventListener`](../removeeventlistener/) metode.

### Lihat juga

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* ruang nama [Aspose.Html.Dom](../../eventtarget/)
* perakitan [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

Metode ini memungkinkan pendaftaran event listener pada target event.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis peristiwa yang didaftarkan oleh pengguna |
| listener | IEventListener | Mengambil antarmuka yang diimplementasikan oleh pengguna yang berisi metode yang akan dipanggil saat peristiwa terjadi. |
| useCapture | Boolean | Jika benar, useCapture menunjukkan bahwa pengguna ingin memulai penangkapan. Setelah memulai penangkapan, semua kejadian dari jenis yang ditentukan akan dikirim ke registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) sebelum dikirim ke Target Peristiwa mana pun di bawahnya di pohon. Peristiwa yang meluap ke atas melalui pohon tidak akan memicu[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ditunjuk untuk menggunakan capture. |

### Perkataan

Jika sebuah[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ditambahkan ke sebuah[`EventTarget`](../) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu selama tahap alur peristiwa selanjutnya, seperti fase gelembung.

Jika beberapa Pemroses Peristiwa identik didaftarkan pada tempat yang sama[`EventTarget`](../)dengan parameter yang sama instance duplikat dibuang. Mereka tidak menyebabkan[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) untuk dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan the [`RemoveEventListener`](../removeeventlistener/) metode.

### Lihat juga

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* ruang nama [Aspose.Html.Dom](../../eventtarget/)
* perakitan [Aspose.HTML](../../../)


