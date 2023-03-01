---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML untuk Referensi .NET API
description: IEventTarget metode. Metode ini memungkinkan pendaftaran event listener pada target event.
type: docs
weight: 10
url: /id/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Metode ini memungkinkan pendaftaran event listener pada target event.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis peristiwa yang didaftarkan oleh pengguna |
| listener | IEventListener | Mengambil antarmuka yang diimplementasikan oleh pengguna yang berisi metode yang akan dipanggil saat peristiwa terjadi. |

### Perkataan

Jika sebuah[`IEventListener`](../../ieventlistener/) ditambahkan ke sebuah[`EventTarget`](../../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu selama tahap alur peristiwa selanjutnya, seperti fase gelembung.

Jika beberapa Pemroses Peristiwa identik didaftarkan pada tempat yang sama[`EventTarget`](../../../aspose.html.dom/eventtarget/)dengan parameter yang sama instance duplikat dibuang. Mereka tidak menyebabkan[`IEventListener`](../../ieventlistener/) untuk dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan the [`RemoveEventListener`](../removeeventlistener/) metode.

### Lihat juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ruang nama [Aspose.Html.Dom.Events](../../ieventtarget/)
* perakitan [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Metode ini memungkinkan pendaftaran event listener pada target event.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis peristiwa yang didaftarkan oleh pengguna |
| listener | IEventListener | Mengambil antarmuka yang diimplementasikan oleh pengguna yang berisi metode yang akan dipanggil saat peristiwa terjadi. |
| useCapture | Boolean | Jika benar, useCapture menunjukkan bahwa pengguna ingin memulai penangkapan. Setelah memulai penangkapan, semua kejadian dari jenis yang ditentukan akan dikirim ke registered [`IEventListener`](../../ieventlistener/) sebelum dikirim ke Target Peristiwa mana pun di bawahnya di pohon. Peristiwa yang meluap ke atas melalui pohon tidak akan memicu[`IEventListener`](../../ieventlistener/) ditunjuk untuk menggunakan capture. |

### Perkataan

Jika sebuah[`IEventListener`](../../ieventlistener/) ditambahkan ke sebuah[`EventTarget`](../../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu selama tahap alur peristiwa selanjutnya, seperti fase gelembung.

Jika beberapa Pemroses Peristiwa identik didaftarkan pada tempat yang sama[`EventTarget`](../../../aspose.html.dom/eventtarget/)dengan parameter yang sama instance duplikat dibuang. Mereka tidak menyebabkan[`IEventListener`](../../ieventlistener/) untuk dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan the [`RemoveEventListener`](../removeeventlistener/) metode.

### Lihat juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ruang nama [Aspose.Html.Dom.Events](../../ieventtarget/)
* perakitan [Aspose.HTML](../../../)


