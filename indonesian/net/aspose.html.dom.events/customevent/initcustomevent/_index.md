---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: CustomEvent metode. /// ItuInitEvent Metode ini digunakan untuk menginisialisasi nilai anEvent diciptakan melaluiIDocumentEvent antarmuka.
type: docs
weight: 30
url: /id/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Itu[`InitEvent`](../../event/initevent/) Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../../event/) diciptakan melalui[`IDocumentEvent`](../../idocumentevent/) antarmuka.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| type | String | Jenis acara. |
| bubbles | Boolean | jika diatur ke`BENAR` [gelembung]. |
| cancelable | Boolean | jika diatur ke`BENAR` [dibatalkan]. |
| detail | Object | Data kustom. |

### Perkataan

Metode ini hanya dapat dipanggil sebelum Acara dikirim melalui[`DispatchEvent`](../../ieventtarget/dispatchevent/) metode, meskipun dapat dipanggil beberapa kali selama fase itu jika perlu. Jika dipanggil beberapa kali, pemanggilan akhir diutamakan. Jika dipanggil dari subkelas antarmuka Acara, hanya nilai yang ditentukan dalam metode initEvent yang diubah, semua atribut lainnya dibiarkan tidak berubah.

### Lihat juga

* class [CustomEvent](../)
* ruang nama [Aspose.Html.Dom.Events](../../customevent/)
* perakitan [Aspose.HTML](../../../)


