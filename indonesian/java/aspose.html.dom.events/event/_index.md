---
title: "Kelas Event"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.events.Event class. Ini digunakan untuk memberikan informasi kontekstual tentang sebuah peristiwa kepada penangkap yang memproses peristiwa tersebut"
type: docs

url: /id/java/com.aspose.html.dom.events/event/
---
## Event class

Ini digunakan untuk menyediakan informasi kontekstual tentang sebuah peristiwa kepada penangkap yang memproses peristiwa tersebut.

```java
public class Event : DOMObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Event](event/#constructor)(String) | Menginisialisasi sebuah instance baru dari kelas `Event`. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Digunakan untuk menunjukkan apakah sebuah peristiwa adalah peristiwa bubbling atau tidak. Jika peristiwa dapat bubbling, nilainya true, jika tidak nilainya false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Digunakan untuk menunjukkan apakah sebuah peristiwa dapat mencegah aksi defaultnya atau tidak. Jika aksi default dapat dicegah, nilainya true, jika tidak nilainya false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) yang [`IEventListener`](../ieventlistener/)nya sedang diproses. Ini sangat berguna selama fase capturing dan bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut cancelable adalah true, dan false jika tidak. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Digunakan untuk menunjukkan fase mana dari alur peristiwa yang sedang dievaluasi. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika sebuah event dibuat, atribut tersebut harus diinisialisasi ke false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) ke mana event awalnya dikirim. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap epoch) saat event dibuat. Karena beberapa sistem mungkin tidak menyediakan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua event. Jika tidak tersedia, nilai 0 akan dikembalikan. Contoh waktu epoch adalah waktu saat sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Nama event (tidak sensitif huruf). Nama harus berupa nama XML. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metode [`InitEvent`](./initevent/) digunakan untuk menginisialisasi nilai sebuah `Event` yang dibuat melalui antarmuka [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Jika sebuah peristiwa dapat dibatalkan, metode [`PreventDefault`](./preventdefault/) digunakan untuk menandakan bahwa peristiwa tersebut harus dibatalkan, artinya setiap aksi default yang biasanya dilakukan oleh implementasi sebagai hasil dari peristiwa tidak akan terjadi. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah event mencapai listener event yang terdaftar setelah yang saat ini dan ketika dikirim dalam sebuah pohon juga mencegah event mencapai objek lain. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metode [`StopPropagation`](./stoppropagation/) digunakan untuk mencegah propagasi lebih lanjut dari sebuah peristiwa selama alur peristiwa. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | Tahap peristiwa saat ini adalah fase penangkapan. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | Tahap peristiwa saat ini adalah fase gelembung. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | Peristiwa saat ini sedang dievaluasi pada target [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Peristiwa yang belum dikirim berada pada fase ini. |

## Catatan

Objek yang mengimplementasikan biasanya diteruskan sebagai parameter pertama ke sebuah penangkap peristiwa. Informasi konteks yang lebih spesifik diteruskan ke penangkap peristiwa dengan menurunkan antarmuka tambahan yang berisi informasi yang langsung berkaitan dengan jenis peristiwa yang menyertainya. Antarmuka yang diturunkan ini juga diimplementasikan oleh objek yang diteruskan ke pendengar peristiwa.

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
