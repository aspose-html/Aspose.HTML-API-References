---
title: "CustomEvent.InitCustomEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode CustomEvent. /// Metode InitEvent digunakan untuk menginisialisasi nilai dari sebuah Event yang dibuat melalui antarmuka IDocumentEvent"
type: docs

url: /id/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Metode [`InitEvent`](../../event/initevent/) digunakan untuk menginisialisasi nilai dari sebuah [`Event`](../../event/) yang dibuat melalui antarmuka [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Tipe peristiwa. |
| bubbles | Boolean | jika disetel ke `true` [bubbles]. |
| cancelable | Boolean | jika disetel ke `true` [cancelable]. |
| detail | Objek | Data khusus. |

## Catatan

Metode ini hanya dapat dipanggil sebelum Event didistribusikan melalui metode [`DispatchEvent`](../../ieventtarget/dispatchevent/), meskipun dapat dipanggil berkali-kali selama fase tersebut bila diperlukan. Jika dipanggil berkali-kali, pemanggilan terakhir yang diutamakan. Jika dipanggil dari subclass antarmuka Event, hanya nilai yang ditentukan dalam metode initEvent yang diubah, semua atribut lain tetap tidak berubah.

### Lihat Juga

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
