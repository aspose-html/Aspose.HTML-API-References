---
title: "Kelas MouseEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.events.MouseEvent class. Antarmuka MouseEvent menyediakan informasi kontekstual spesifik yang terkait dengan peristiwa Mouse."
type: docs

url: /id/java/com.aspose.html.dom.events/mouseevent/
---
## MouseEvent class

Antarmuka MouseEvent menyediakan informasi kontekstual spesifik yang terkait dengan peristiwa Mouse.

```java
public class MouseEvent : UIEvent
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(String) | Menginisialisasi sebuah instance baru dari kelas `MouseEvent`. |
| [MouseEvent](mouseevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Lihat atribut altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Digunakan untuk menunjukkan apakah sebuah peristiwa adalah peristiwa bubbling atau tidak. Jika peristiwa dapat bubbling, nilainya true, jika tidak nilainya false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Selama peristiwa mouse yang disebabkan oleh penekanan atau pelepasan tombol mouse, button HARUS digunakan untuk menunjukkan tombol perangkat penunjuk mana yang berubah status. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Selama setiap peristiwa mouse, buttons HARUS digunakan untuk menunjukkan kombinasi tombol mouse mana yang sedang ditekan, dinyatakan sebagai bitmask. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Digunakan untuk menunjukkan apakah sebuah peristiwa dapat mencegah aksi defaultnya atau tidak. Jika aksi default dapat dicegah, nilainya true, jika tidak nilainya false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) Koordinat horizontal tempat peristiwa terjadi relatif terhadap viewport yang terkait dengan peristiwa. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) Koordinat vertikal tempat peristiwa terjadi relatif terhadap viewport yang terkait dengan peristiwa. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Lihat atribut ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) yang [`IEventListener`](../ieventlistener/)nya sedang diproses. Ini sangat berguna selama fase capturing dan bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut cancelable adalah true, dan false jika tidak. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Menentukan beberapa informasi detail tentang Event, tergantung pada jenis event. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Digunakan untuk menunjukkan fase mana dari alur peristiwa yang sedang dievaluasi. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika sebuah event dibuat, atribut tersebut harus diinisialisasi ke false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Lihat atribut metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Digunakan untuk mengidentifikasi EventTarget sekunder yang terkait dengan peristiwa UI, tergantung pada jenis peristiwa. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) Koordinat horizontal tempat peristiwa terjadi relatif terhadap asal sistem koordinat layar. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) Koordinat vertikal tempat peristiwa terjadi relatif terhadap asal sistem koordinat layar. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Merujuk pada atribut shiftKey. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) ke mana event awalnya dikirim. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap epoch) saat event dibuat. Karena beberapa sistem mungkin tidak menyediakan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua event. Jika tidak tersedia, nilai 0 akan dikembalikan. Contoh waktu epoch adalah waktu saat sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Nama event (tidak sensitif huruf). Nama harus berupa nama XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Atribut view mengidentifikasi Window tempat event dihasilkan. Nilai yang belum diinisialisasi dari atribut ini HARUS null. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metode [`InitEvent`](../event/initevent/) digunakan untuk menginisialisasi nilai sebuah [`Event`](../event/) yang dibuat melalui antarmuka [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Jika sebuah event dapat dibatalkan, metode [`PreventDefault`](../event/preventdefault/) digunakan untuk menandakan bahwa event tersebut harus dibatalkan, artinya setiap aksi default yang biasanya dilakukan oleh implementasi sebagai hasil dari event tidak akan terjadi. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah event mencapai listener event yang terdaftar setelah yang saat ini dan ketika dikirim dalam sebuah pohon juga mencegah event mencapai objek lain. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metode [`StopPropagation`](../event/stoppropagation/) digunakan untuk mencegah propagasi lebih lanjut dari sebuah event selama alur event. |

### Lihat Juga

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
