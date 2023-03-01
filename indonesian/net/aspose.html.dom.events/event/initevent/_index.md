---
title: Event.InitEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: Event metode. ItuInitEvent Metode ini digunakan untuk menginisialisasi nilai anEvent dibuat melalui the IDocumentEvent antarmuka.
type: docs
weight: 110
url: /id/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Itu`InitEvent` Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../) dibuat melalui the [`IDocumentEvent`](../../idocumentevent/) antarmuka.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis acara. |
| bubbles | Boolean | jika diatur ke`BENAR` [gelembung]. |
| cancelable | Boolean | jika diatur ke`BENAR` [dibatalkan]. |

### Perkataan

Metode ini hanya dapat dipanggil sebelum Acara dikirim melalui[`DispatchEvent`](../../ieventtarget/dispatchevent/) metode, meskipun dapat dipanggil beberapa kali selama fase itu jika perlu. Jika dipanggil beberapa kali, pemanggilan akhir diutamakan. Jika dipanggil dari subkelas antarmuka Acara, hanya nilai yang ditentukan dalam metode initEvent yang diubah, semua atribut lainnya dibiarkan tidak berubah.

### Lihat juga

* class [Event](../)
* ruang nama [Aspose.Html.Dom.Events](../../event/)
* perakitan [Aspose.HTML](../../../)


