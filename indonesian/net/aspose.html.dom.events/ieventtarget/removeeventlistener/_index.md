---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML untuk Referensi .NET API
description: IEventTarget metode. Metode ini memungkinkan penghapusan pendengar acara dari target acara. JikaIEventListener dihapus dari sebuahEventTarget saat sedang memproses suatu peristiwa peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus.
type: docs
weight: 30
url: /id/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../ieventlistener/) dihapus dari sebuah[`EventTarget`](../../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Menentukan jenis acara dari[`IEventListener`](../../ieventlistener/) sedang dihapus. |
| listener | IEventListener | Itu[`IEventListener`](../../ieventlistener/) parameter menunjukkan[`IEventListener`](../../ieventlistener/) untuk dihapus. |

### Lihat juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ruang nama [Aspose.Html.Dom.Events](../../ieventtarget/)
* perakitan [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../ieventlistener/) dihapus dari sebuah[`EventTarget`](../../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Menentukan jenis acara dari[`IEventListener`](../../ieventlistener/) sedang dihapus. |
| listener | IEventListener | Itu[`IEventListener`](../../ieventlistener/) parameter menunjukkan[`IEventListener`](../../ieventlistener/) untuk dihapus. |
| useCapture | Boolean | Menentukan apakah EventListener yang dihapus terdaftar sebagai pendengar penangkap atau tidak. Jika pendengar terdaftar dua kali, satu dengan penangkap dan satu tanpa, masing-masing harus dihapus secara terpisah. Penghapusan pendengar penangkap tidak memengaruhi versi yang tidak menangkap pendengar yang sama, dan sebaliknya. |

### Lihat juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* ruang nama [Aspose.Html.Dom.Events](../../ieventtarget/)
* perakitan [Aspose.HTML](../../../)


