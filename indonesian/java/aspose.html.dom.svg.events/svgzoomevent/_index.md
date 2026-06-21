---
title: "Kelas SVGZoomEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.dom.svg.events.SVGZoomEvent. Peristiwa zoom terjadi ketika pengguna memulai aksi yang menyebabkan tampilan saat ini dari fragmen dokumen SVG diubah skalanya. Penangan peristiwa hanya dikenali pada elemen svg."
type: docs

url: /id/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Peristiwa zoom terjadi ketika pengguna memulai aksi yang menyebabkan tampilan saat ini dari fragmen dokumen SVG diubah skalanya. Penangan peristiwa hanya dikenali pada elemen ‘svg’.

```java
public class SVGZoomEvent : Event
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Digunakan untuk menunjukkan apakah sebuah peristiwa merupakan peristiwa bubbling atau tidak. Jika peristiwa dapat bubbling, nilainya true, jika tidak nilainya false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Digunakan untuk menunjukkan apakah sebuah peristiwa dapat mencegah aksi defaultnya atau tidak. Jika aksi default dapat dicegah, nilainya true, jika tidak nilainya false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Digunakan untuk menunjukkan [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)nya sedang diproses. Ini sangat berguna selama proses penangkapan dan bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Mengembalikan true jika preventDefault() dipanggil saat nilai atribut cancelable true, dan false sebaliknya. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Digunakan untuk menunjukkan fase alur peristiwa mana yang sedang dievaluasi. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika sebuah event dibuat, atribut tersebut harus diinisialisasi menjadi false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Faktor skala yang akan berlaku setelah operasi zoom diproses. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Nilai translasi yang akan berlaku setelah operasi zoom diproses. Objek SVGPoint bersifat read only. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Faktor skala dari operasi zoom sebelumnya yang berlaku sebelum operasi zoom terjadi. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Nilai translasi dari operasi zoom sebelumnya yang berlaku sebelum operasi zoom terjadi. Objek SVGPoint bersifat read only. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Digunakan untuk menunjukkan [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) ke mana peristiwa awalnya dikirim. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap epoch) saat event dibuat. Karena beberapa sistem mungkin tidak menyediakan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua event. Jika tidak tersedia, nilai 0 akan dikembalikan. Contoh waktu epoch adalah waktu mulai sistem atau 0:0:0 UTC 1 Januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Nama event (tidak sensitif huruf). Nama harus berupa nama XML. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Kotak zoom yang ditentukan dalam satuan layar. Objek SVGRect bersifat read only. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metode [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) digunakan untuk menginisialisasi nilai sebuah [`Event`](../../com.aspose.html.dom.events/event/) yang dibuat melalui antarmuka [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Jika sebuah peristiwa dapat dibatalkan, metode [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) digunakan untuk menandakan bahwa peristiwa tersebut akan dibatalkan, artinya tindakan default apa pun yang biasanya dilakukan oleh implementasi sebagai hasil peristiwa tidak akan terjadi. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah event mencapai listener event apa pun yang terdaftar setelah yang saat ini dan ketika dikirim dalam sebuah pohon juga mencegah event mencapai objek lain. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metode [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) digunakan untuk mencegah propagasi lebih lanjut dari sebuah peristiwa selama alur peristiwa. |

### Lihat Juga

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
