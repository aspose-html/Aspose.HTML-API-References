---
title: "Event.InitEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Event. Metode InitEvent digunakan untuk menginisialisasi nilai dari sebuah Event yang dibuat melalui antarmuka IDocumentEvent."
type: docs

url: /id/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Metode `InitEvent` digunakan untuk menginisialisasi nilai dari sebuah [`Event`](../) yang dibuat melalui antarmuka [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Tipe peristiwa. |
| bubbles | Boolean | jika diatur ke `true` [bubbles]. |
| cancelable | Boolean | jika diatur ke `true` [cancelable]. |

## Catatan

Metode ini hanya dapat dipanggil sebelum Event didistribusikan melalui metode [`DispatchEvent`](../../ieventtarget/dispatchevent/), meskipun dapat dipanggil berkali-kali selama fase tersebut jika diperlukan. Jika dipanggil berkali-kali, pemanggilan terakhir yang diutamakan. Jika dipanggil dari subclass antarmuka Event, hanya nilai yang ditentukan dalam metode initEvent yang diubah, semua atribut lainnya tetap tidak berubah.

### Lihat Juga

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
