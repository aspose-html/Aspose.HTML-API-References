---
title: Class KeyboardEvent
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Events.KeyboardEvent kelas. Antarmuka KeyboardEvent menyediakan informasi kontekstual khusus yang terkait dengan perangkat keyboard. Setiap peristiwa keyboard mereferensikan kunci menggunakan nilai. Peristiwa keyboard umumnya diarahkan pada elemen yang memiliki fokus.
type: docs
weight: 830
url: /id/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

Antarmuka KeyboardEvent menyediakan informasi kontekstual khusus yang terkait dengan perangkat keyboard. Setiap peristiwa keyboard mereferensikan kunci menggunakan nilai. Peristiwa keyboard umumnya diarahkan pada elemen yang memiliki fokus.

```csharp
public class KeyboardEvent : UIEvent
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Menginisialisasi instance baru dari`KeyboardEvent` kelas. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Menginisialisasi instance baru dari`KeyboardEvent` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | true jika pengubah kunci Alt (alternatif) (atau "Option") aktif. Nilai yang tidak diinisialisasi dari atribut ini HARUS false. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa merupakan peristiwa menggelegak atau tidak. Jika peristiwa dapat menggembungkan nilainya benar, jika tidak, nilainya salah. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Digunakan untuk menunjukkan apakah suatu peristiwa dapat dicegah tindakan defaultnya atau tidak. Jika tindakan default dapat dicegah, nilainya benar, jika tidak, nilainya salah. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | Kode menyimpan string yang mengidentifikasi tombol fisik yang ditekan. Nilai tidak terpengaruh oleh tata letak keyboard atau status pengubah saat ini, jadi kunci tertentu akan selalu mengembalikan nilai yang sama. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | true jika pengubah tombol Kontrol (kontrol) aktif. Nilai yang tidak diinisialisasi dari atribut ini HARUS salah. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Digunakan untuk menunjukkan[`IEventTarget`](../ieventtarget/) yang[`IEventListener`](../ieventlistener/) s sedang diproses. Ini sangat berguna selama menangkap dan menggelegak. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Mengembalikan true jika preventDefault() dipanggil sementara nilai atribut yang dapat dibatalkan adalah true, dan false jika sebaliknya. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Menentukan beberapa informasi detail tentang Acara, bergantung pada jenis acara. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Digunakan untuk menunjukkan fase aliran peristiwa mana yang sedang dievaluasi. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | true jika peristiwa utama terjadi sebagai bagian dari sesi komposisi, yaitu setelah peristiwa komposisi mulai dan sebelum peristiwa komposisi akhir yang sesuai. Nilai yang tidak diinisialisasi dari atribut ini HARUS false. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika suatu peristiwa dibuat, atribut harus diinisialisasi ke false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | Kunci menyimpan nilai kunci dari tombol yang ditekan. Jika nilainya memiliki representasi tercetak, itu HARUS berupa string karakter Unicode yang tidak kosong, sesuai dengan algoritme untuk menentukan nilai kunci yang ditentukan dalam spesifikasi ini. Jika nilainya adalah kunci kontrol yang tidak memiliki representasi tercetak, itu HARUS menjadi salah satu nilai kunci yang ditentukan dalam rangkaian nilai kunci, seperti yang ditentukan oleh algoritme untuk menentukan nilai kunci. Implementasi yang tidak dapat mengidentifikasi kunci HARUS menggunakan nilai kunci Unidentified. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | Atribut lokasi berisi indikasi lokasi logis kunci pada perangkat. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | benar jika pengubah kunci meta (Meta) aktif. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | benar jika tombol ditekan terus menerus. Menahan tombol HARUS menghasilkan pengulangan peristiwa keydown, sebelum memasukkan, memasukkan dalam urutan ini, dengan kecepatan yang ditentukan oleh konfigurasi sistem. Untuk perangkat seluler yang memiliki perilaku penekanan tombol lama, peristiwa tombol pertama dengan nilai atribut pengulangan true HARUS berfungsi sebagai indikasi penekanan tombol lama. Lamanya waktu tombol HARUS ditekan untuk memulai pengulangan bergantung pada konfigurasi. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | true jika pengubah tombol shift (Shift) aktif. |
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
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Kunci yang diaktifkan berasal dari lokasi kunci kiri (ketika ada lebih dari satu kemungkinan lokasi untuk kunci ini). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Aktivasi tombol berasal dari keypad numerik atau dengan tombol virtual yang sesuai dengan keypad numerik (bila ada lebih dari satu kemungkinan lokasi untuk tombol ini). Perhatikan bahwa kunci NumLock harus selalu dikodekan dengan lokasi DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Aktivasi kunci berasal dari lokasi kunci yang benar (ketika ada lebih dari satu kemungkinan lokasi untuk kunci ini). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Aktivasi kunci TIDAK HARUS dibedakan sebagai versi kunci kiri atau kanan, dan (selain tombol NumLock) tidak berasal dari keypad numerik (atau tidak berasal dari tombol virtual yang sesuai dengan keypad numerik). |

### Lihat juga

* class [UIEvent](../uievent/)
* ruang nama [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* perakitan [Aspose.HTML](../../)


