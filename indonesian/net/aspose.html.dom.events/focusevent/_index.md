---
title: Class FocusEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Events.FocusEvent kelas. Antarmuka FocusEvent menyediakan informasi kontekstual khusus yang terkait dengan peristiwa Fokus.
type: docs
weight: 780
url: /id/net/aspose.html.dom.events/focusevent/
---
## FocusEvent class

Antarmuka FocusEvent menyediakan informasi kontekstual khusus yang terkait dengan peristiwa Fokus.

```csharp
public class FocusEvent : UIEvent
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [FocusEvent](focusevent/#constructor)(string) | Menginisialisasi instance baru dari`FocusEvent` kelas. |
| [FocusEvent](focusevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Menginisialisasi instance baru dari`FocusEvent` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) yang[`IEventListener`](../ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Menentukan beberapa informasi detail tentang Acara, bergantung pada jenis acara. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [RelatedTarget](../../aspose.html.dom.events/focusevent/relatedtarget/) { get; } | Digunakan untuk mengidentifikasi EventTarget sekunder yang terkait dengan acara Focus, bergantung pada jenis acara. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) ke mana acara tersebut awalnya dikirim. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap zaman) saat peristiwa dibuat. Karena beberapa sistem mungkin tidak memberikan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua peristiwa. Jika tidak tersedia , nilai 0 akan dikembalikan. Contoh waktu zaman adalah waktu sistem mulai atau 0:0:0 UTC 1 Januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Nama acara (peka huruf besar-kecil). Nama harus berupa nama XML. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | Atribut view mengidentifikasi Window dari mana event dihasilkan. Nilai yang tidak diinisialisasi dari atribut ini HARUS null. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Itu[`InitEvent`](../event/initevent/) Metode ini digunakan untuk menginisialisasi nilai an[`Event`](../event/) dibuat melalui the [`IDocumentEvent`](../idocumentevent/) antarmuka. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Jika suatu acara dapat dibatalkan, maka[`PreventDefault`](../event/preventdefault/) metode digunakan untuk menandakan bahwa acara tersebut akan dibatalkan, artinya tindakan default apa pun yang biasanya diambil oleh implementasi sebagai akibat dari acara tersebut tidak akan terjadi. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah acara menjangkau pendengar acara apa pun yang terdaftar setelah yang sekarang dan saat dikirim dalam pohon juga mencegah acara menjangkau objek lain. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Itu[`StopPropagation`](../event/stoppropagation/) metode digunakan untuk mencegah penyebaran lebih lanjut dari suatu peristiwa selama aliran peristiwa. |

### Lihat juga

* class [UIEvent](../uievent/)
* ruang nama [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* perakitan [Aspose.HTML](../../)


