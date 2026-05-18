---
title: "TimeEvent.InitTimeEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode TimeEvent. Metode initTimeEvent digunakan untuk menginisialisasi nilai dari TimeEvent yang dibuat melalui antarmuka DocumentEvent. Metode ini hanya dapat dipanggil sebelum TimeEvent didistribusikan melalui metode dispatchEvent meskipun dapat dipanggil berkali-kali selama fase tersebut jika diperlukan. Jika dipanggil berkali-kali, pemanggilan terakhir yang akan diutamakan."
type: docs

url: /id/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Metode initTimeEvent digunakan untuk menginisialisasi nilai sebuah TimeEvent yang dibuat melalui antarmuka DocumentEvent. Metode ini hanya dapat dipanggil sebelum TimeEvent dikirim melalui metode dispatchEvent, meskipun dapat dipanggil berkali-kali selama fase tersebut jika diperlukan. Jika dipanggil berkali-kali, pemanggilan terakhir yang diutamakan.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeArg | String | Menentukan jenis peristiwa. |
| viewArg | IAbstractView | Menentukan AbstractView peristiwa. |
| detailArg | Int64 | Menentukan detail peristiwa. |

### Lihat Juga

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
