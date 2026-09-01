---
title: "Kelas ErrorEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.dom.events.ErrorEvent. ErrorEvent menyediakan informasi kontekstual tentang kesalahan yang terjadi selama runtime"
type: docs

url: /id/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

ErrorEvent menyediakan informasi kontekstual tentang kesalahan yang terjadi selama runtime.

```java
public class ErrorEvent : Event
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Menginisialisasi sebuah instance baru dari kelas `ErrorEvent`. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Digunakan untuk menunjukkan apakah sebuah peristiwa merupakan peristiwa bubbling atau tidak. Jika peristiwa dapat bubbling, nilainya true, jika tidak nilainya false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Digunakan untuk menunjukkan apakah sebuah peristiwa dapat mencegah aksi defaultnya atau tidak. Jika aksi default dapat dicegah, nilainya true, jika tidak nilainya false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) Atribut kolno harus mengembalikan nilai yang telah diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke nol. Ini mewakili nomor kolom tempat kesalahan terjadi dalam skrip. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) yang [`IEventListener`](../ieventlistener/)nya sedang diproses. Ini sangat berguna selama proses capturing dan bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Mengembalikan true jika preventDefault() dipanggil saat nilai atribut cancelable true, dan false sebaliknya. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) Atribut error harus mengembalikan nilai yang telah diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke null. Bila sesuai, atribut ini diatur ke objek yang mewakili kesalahan (misalnya objek pengecualian dalam kasus pengecualian DOM yang tidak tertangkap). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Digunakan untuk menunjukkan fase alur peristiwa mana yang sedang dievaluasi. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) Atribut filename harus mengembalikan nilai yang telah diinisialisasi. Saat objek dibuat, atribut ini harus diinisialisasi ke String kosong. Ini mewakili URL absolut dari skrip tempat kesalahan awalnya terjadi. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika sebuah event dibuat, atribut tersebut harus diinisialisasi menjadi false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) Atribut lineno harus mengembalikan nilai yang diinisialisasi. Ketika objek dibuat, atribut ini harus diinisialisasi menjadi nol. Ini mewakili nomor baris tempat kesalahan terjadi dalam skrip. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) Atribut message harus mengembalikan nilai yang diinisialisasi. Ketika objek dibuat, atribut ini harus diinisialisasi menjadi String kosong. Ini mewakili pesan kesalahan. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) ke mana event awalnya dikirim. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap epoch) saat event dibuat. Karena beberapa sistem mungkin tidak menyediakan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua event. Jika tidak tersedia, nilai 0 akan dikembalikan. Contoh waktu epoch adalah waktu mulai sistem atau 0:0:0 UTC 1 Januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Nama event (tidak sensitif huruf). Nama harus berupa nama XML. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metode [`InitEvent`](../event/initevent/) digunakan untuk menginisialisasi nilai sebuah [`Event`](../event/) yang dibuat melalui antarmuka [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Jika sebuah event dapat dibatalkan, metode [`PreventDefault`](../event/preventdefault/) digunakan untuk menunjukkan bahwa event tersebut harus dibatalkan, artinya setiap aksi default yang biasanya dilakukan oleh implementasi sebagai hasil dari event tidak akan terjadi. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah event mencapai listener event apa pun yang terdaftar setelah yang saat ini dan ketika dikirim dalam sebuah pohon juga mencegah event mencapai objek lain. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metode [`StopPropagation`](../event/stoppropagation/) digunakan untuk mencegah propagasi lebih lanjut dari sebuah event selama alur event. |

### Lihat Juga

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
