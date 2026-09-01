---
title: "EventTarget.DispatchEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode EventTarget. Men-dispatch sebuah Event pada EventTarget yang ditentukan secara sinkron, memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan peristiwa normal termasuk fase penangkapan dan fase bubbling opsional juga berlaku untuk peristiwa yang di-dispatch secara manual dengan dispatchEvent"
type: docs

url: /id/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Men-dispatch sebuah Event pada [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan peristiwa normal (termasuk fase penangkapan dan fase bubbling opsional) juga berlaku untuk peristiwa yang di-dispatch secara manual dengan [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| peristiwa | Peristiwa | Menentukan tipe event, perilaku, dan informasi kontekstual yang akan digunakan dalam memproses event. |

### Nilai Kembali

Nilai kembali dari menunjukkan apakah salah satu listener yang menangani event dipanggil. Jika dipanggil nilainya false, jika tidak nilainya true.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Catatan

Event yang disebarkan dengan cara ini akan memiliki perilaku penangkapan dan gelembung yang sama seperti event yang disebarkan langsung oleh implementasi. Target dari event adalah pada yang dipanggil.

### Lihat Juga

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
