---
title: Class WheelEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Events.WheelEvent kelas. Antarmuka WheelEvent menyediakan informasi kontekstual khusus yang terkait dengan peristiwa roda. Untuk membuat instance antarmuka WheelEvent gunakan konstruktor WheelEvent dengan meneruskan kamus WheelEventInit opsional.
type: docs
weight: 860
url: /id/net/aspose.html.dom.events/wheelevent/
---
## WheelEvent class

Antarmuka WheelEvent menyediakan informasi kontekstual khusus yang terkait dengan peristiwa roda. Untuk membuat instance antarmuka WheelEvent, gunakan konstruktor WheelEvent, dengan meneruskan kamus WheelEventInit opsional.

```csharp
public class WheelEvent : MouseEvent
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(string) | Menginisialisasi instance baru dari`WheelEvent` kelas. |
| [WheelEvent](wheelevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Menginisialisasi instance baru dari`WheelEvent` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | Lihat atribut altKey. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | Selama peristiwa mouse yang disebabkan oleh penekanan atau pelepasan tombol mouse, tombol HARUS digunakan untuk menunjukkan tombol perangkat penunjuk mana yang berubah status. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | Selama aktivitas mouse apa pun, tombol HARUS digunakan untuk menunjukkan kombinasi tombol mouse mana yang sedang ditekan, dinyatakan sebagai bitmask. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | Koordinat horizontal tempat terjadinya peristiwa relatif terhadap area pandang yang terkait dengan peristiwa. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | Koordinat vertikal tempat terjadinya peristiwa relatif terhadap area pandang yang terkait dengan peristiwa. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | Lihat atribut ctrlKey. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) yang[`IEventListener`](../ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [DeltaMode](../../aspose.html.dom.events/wheelevent/deltamode/) { get; } | Atribut deltaMode berisi indikasi satuan pengukuran untuk nilai delta. Nilai defaultnya adalah DOM_DELTA_PIXEL (piksel). |
| [DeltaX](../../aspose.html.dom.events/wheelevent/deltax/) { get; } | Di agen pengguna tempat tindakan default acara roda adalah menggulir, nilai HARUS berupa pengukuran sepanjang sumbu x (dalam piksel, garis, atau halaman) yang akan digulir jika acara tidak dibatalkan. Jika tidak, ini adalah pengukuran khusus implementasi (dalam piksel, garis, atau halaman) dari pergerakan perangkat roda di sekitar sumbu x. |
| [DeltaY](../../aspose.html.dom.events/wheelevent/deltay/) { get; } | Di agen pengguna tempat tindakan default acara roda adalah menggulir, nilai HARUS menjadi ukuran sepanjang sumbu y (dalam piksel, garis, atau halaman) yang akan digulir jika acara tidak dibatalkan. Jika tidak, ini adalah pengukuran khusus penerapan (dalam piksel, garis, atau halaman) dari pergerakan perangkat roda di sekitar sumbu y. |
| [DeltaZ](../../aspose.html.dom.events/wheelevent/deltaz/) { get; } | Di agen pengguna tempat tindakan default acara roda adalah menggulir, nilai HARUS menjadi ukuran sepanjang sumbu z (dalam piksel, garis, atau halaman) yang akan digulir jika acara tidak dibatalkan. Jika tidak, ini adalah pengukuran khusus implementasi (dalam piksel, garis, atau halaman) dari pergerakan perangkat roda di sekitar sumbu z. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Menentukan beberapa informasi detail tentang Acara, bergantung pada jenis acara. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | Lihat atribut metaKey. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | Digunakan untuk mengidentifikasi EventTarget sekunder yang terkait dengan peristiwa UI, bergantung pada jenis peristiwa. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | Koordinat horizontal tempat terjadinya peristiwa relatif terhadap asal sistem koordinat layar. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | Koordinat vertikal tempat terjadinya peristiwa relatif terhadap asal sistem koordinat layar. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | Lihat atribut shiftKey. |
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

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.html.dom.events/wheelevent/dom_delta_line/) | Satuan pengukuran untuk delta HARUS berupa baris teks individual. Ini adalah kasus untuk banyak kontrol formulir. |
| const [DOM_DELTA_PAGE](../../aspose.html.dom.events/wheelevent/dom_delta_page/) | Satuan pengukuran untuk delta HARUS berupa halaman, baik yang didefinisikan sebagai satu layar atau sebagai halaman yang dibatasi. |
| const [DOM_DELTA_PIXEL](../../aspose.html.dom.events/wheelevent/dom_delta_pixel/) | Satuan pengukuran untuk delta HARUS piksel. Ini adalah kasus paling umum di sebagian besar sistem operasi dan konfigurasi implementasi. |

### Lihat juga

* class [MouseEvent](../mouseevent/)
* ruang nama [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* perakitan [Aspose.HTML](../../)


