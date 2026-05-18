---
title: "InputEvent Kelas"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.events.InputEvent class. Peristiwa Input dikirim sebagai notifikasi setiap kali DOM diperbarui."
type: docs

url: /id/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

Peristiwa input dikirim sebagai notifikasi setiap kali DOM diperbarui.

```java
public class InputEvent : UIEvent
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | Menginisialisasi sebuah instance baru dari kelas `InputEvent`. |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Digunakan untuk menunjukkan apakah sebuah peristiwa adalah peristiwa bubbling atau tidak. Jika peristiwa dapat bubbling, nilainya true, jika tidak nilainya false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Digunakan untuk menunjukkan apakah sebuah peristiwa dapat mencegah aksi defaultnya atau tidak. Jika aksi default dapat dicegah, nilainya true, jika tidak nilainya false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) yang [`IEventListener`](../ieventlistener/)nya sedang diproses. Ini sangat berguna selama fase capturing dan bubbling. |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) Data menyimpan nilai karakter yang dihasilkan oleh metode input. Ini BISA berupa satu karakter Unicode atau urutan karakter Unicode yang tidak kosong [Unicode]. Karakter SEHARUSNYA dinormalisasi sebagaimana didefinisikan oleh bentuk normalisasi Unicode NFC, yang didefinisikan dalam [UAX15]. Atribut ini BISA berisi String kosong. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut cancelable adalah true, dan false jika tidak. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Menentukan beberapa informasi detail tentang Event, tergantung pada jenis event. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Digunakan untuk menunjukkan fase mana dari alur peristiwa yang sedang dievaluasi. |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) true jika peristiwa input terjadi sebagai bagian dari sesi komposisi, yaitu setelah peristiwa compositionstart dan sebelum peristiwa compositionend yang bersesuaian. Nilai belum diinisialisasi dari atribut ini HARUS false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika sebuah event dibuat, atribut tersebut harus diinisialisasi ke false. |
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
