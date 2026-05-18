---
title: "IEventTarget.DispatchEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IEventTarget. Menyebarkan (dispatch) sebuah Event pada EventTarget yang ditentukan secara sinkron dengan memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal termasuk fase penangkapan dan fase bubbling opsional juga berlaku untuk event yang disebarkan secara manual dengan dispatchEvent."
type: docs

url: /id/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Mengirimkan sebuah Event ke EventTarget yang ditentukan, (secara sinkron) memanggil EventListener yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan peristiwa normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk peristiwa yang dikirim secara manual dengan dispatchEvent().

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| peristiwa | Event | Menentukan tipe event, perilaku, dan informasi kontekstual yang akan digunakan dalam memproses event. |

### Nilai Kembali

Nilai kembali dari menunjukkan apakah ada listener yang menangani event yang dipanggil. Jika dipanggil nilai adalah false, jika tidak nilai adalah true.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Pengecualian yang dilempar oleh penangan event dilaporkan sebagai pengecualian yang tidak tertangkap. Penangan event berjalan pada callstack bersarang; mereka memblokir pemanggil sampai selesai, tetapi pengecualian tidak menyebar ke pemanggil. |

## Catatan

Event yang disebarkan dengan cara ini akan memiliki perilaku penangkapan dan bubbling yang sama seperti event yang disebarkan langsung oleh implementasi. Target dari event adalah pada yang dipanggil.

### Lihat Juga

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
