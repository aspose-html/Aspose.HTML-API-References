---
title: Class TimeEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Svg.Events.TimeEvent kelas. Antarmuka TimeEvent menyediakan informasi kontekstual khusus yang terkait dengan peristiwa Waktu. Berbagai jenis peristiwa yang dapat terjadi adalah beginEvent endEvent dan repeatEvent.
type: docs
weight: 1340
url: /id/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Antarmuka TimeEvent menyediakan informasi kontekstual khusus yang terkait dengan peristiwa Waktu. Berbagai jenis peristiwa yang dapat terjadi adalah: beginEvent, endEvent, dan repeatEvent.

```csharp
public class TimeEvent : Event
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) yang[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail/) { get; } | Menentukan beberapa informasi detail tentang Acara, bergantung pada jenis acara. Untuk jenis acara ini, tunjukkan nomor pengulangan untuk animasi. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) ke mana acara tersebut awalnya dikirim. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap zaman) saat peristiwa dibuat. Karena beberapa sistem mungkin tidak memberikan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua peristiwa. Jika tidak tersedia , nilai 0 akan dikembalikan. Contoh waktu zaman adalah waktu sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Nama acara (peka huruf besar-kecil). Nama harus berupa nama XML. |
| [View](../../aspose.html.dom.svg.events/timeevent/view/) { get; } | Atribut view mengidentifikasi AbstractView [DOM2VIEWS] dari mana event dihasilkan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Itu[`InitEvent`](../../aspose.html.dom.events/event/initevent/) Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../../aspose.html.dom.events/event/) dibuat melalui the [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) antarmuka. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | Metode initTimeEvent digunakan untuk menginisialisasi nilai TimeEvent yang dibuat melalui antarmuka DocumentEvent. Metode ini hanya dapat dipanggil sebelum TimeEvent dikirim melalui metode dispatchEvent, meskipun dapat dipanggil beberapa kali selama fase tersebut jika diperlukan. Jika dipanggil beberapa kali, pemanggilan terakhir diutamakan. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Jika suatu acara dapat dibatalkan, maka[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) metode digunakan untuk menandakan bahwa acara tersebut akan dibatalkan, artinya tindakan default apa pun yang biasanya diambil oleh implementasi sebagai akibat dari acara tersebut tidak akan terjadi. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah acara menjangkau pendengar acara apa pun yang terdaftar setelah yang sekarang dan saat dikirim dalam pohon juga mencegah acara menjangkau objek lain. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Itu[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) metode digunakan untuk mencegah penyebaran lebih lanjut dari suatu peristiwa selama aliran peristiwa. |

### Lihat juga

* class [Event](../../aspose.html.dom.events/event/)
* ruang nama [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* perakitan [Aspose.HTML](../../)


