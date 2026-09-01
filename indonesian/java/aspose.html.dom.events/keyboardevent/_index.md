---
title: "Kelas KeyboardEvent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.dom.events.KeyboardEvent. Antarmuka KeyboardEvent menyediakan informasi kontekstual spesifik yang terkait dengan perangkat keyboard. Setiap event keyboard merujuk pada sebuah tombol menggunakan nilai. Event keyboard biasanya diarahkan ke elemen yang memiliki fokus."
type: docs

url: /id/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

Antarmuka KeyboardEvent menyediakan informasi kontekstual spesifik yang terkait dengan perangkat keyboard. Setiap peristiwa keyboard merujuk pada sebuah tombol menggunakan nilai. Peristiwa keyboard biasanya diarahkan ke elemen yang memiliki fokus.

```java
public class KeyboardEvent : UIEvent
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Menginisialisasi sebuah instance baru dari kelas `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true jika modifier tombol Alt (alternatif) (atau "Option") aktif. Nilai yang belum diinisialisasi untuk atribut ini HARUS false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Digunakan untuk menunjukkan apakah sebuah peristiwa merupakan peristiwa bubbling atau tidak. Jika peristiwa dapat bubbling, nilainya true, jika tidak nilainya false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Digunakan untuk menunjukkan apakah sebuah peristiwa dapat mencegah aksi defaultnya atau tidak. Jika aksi default dapat dicegah, nilainya true, jika tidak nilainya false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Code berisi String yang mengidentifikasi tombol fisik yang ditekan. Nilai tidak dipengaruhi oleh tata letak keyboard atau status modifier saat ini, sehingga tombol tertentu akan selalu mengembalikan nilai yang sama. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true jika modifier tombol Control (control) aktif. Nilai yang belum diinisialisasi untuk atribut ini HARUS false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) yang [`IEventListener`](../ieventlistener/)nya sedang diproses. Ini sangat berguna selama proses capturing dan bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Mengembalikan true jika preventDefault() dipanggil saat nilai atribut cancelable true, dan false sebaliknya. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Menentukan beberapa informasi detail tentang Event, tergantung pada jenis event. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Digunakan untuk menunjukkan fase alur peristiwa mana yang sedang dievaluasi. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true jika event tombol terjadi sebagai bagian dari sesi komposisi, yaitu setelah event compositionstart dan sebelum event compositionend yang bersesuaian. Nilai yang belum diinisialisasi untuk atribut ini HARUS false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Atribut isTrusted harus mengembalikan nilai yang diinisialisasi. Ketika sebuah event dibuat, atribut tersebut harus diinisialisasi menjadi false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) Key menyimpan nilai tombol yang ditekan. Jika nilai memiliki representasi tercetak, nilai tersebut HARUS berupa String karakter Unicode yang tidak kosong, sesuai dengan algoritma penentuan nilai tombol yang didefinisikan dalam spesifikasi ini. Jika nilai adalah tombol kontrol yang tidak memiliki representasi tercetak, nilai tersebut HARUS menjadi salah satu nilai tombol yang didefinisikan dalam kumpulan nilai tombol, sebagaimana ditentukan oleh algoritma penentuan nilai tombol. Implementasi yang tidak dapat mengidentifikasi sebuah tombol HARUS menggunakan nilai tombol Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Atribut location berisi indikasi lokasi logis tombol pada perangkat. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true jika modifier tombol meta (Meta) aktif. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true jika tombol ditekan secara berkelanjutan. Menahan tombol HARUS menghasilkan pengulangan event keydown, beforeinput, input dalam urutan tersebut, dengan kecepatan yang ditentukan oleh konfigurasi sistem. Untuk perangkat seluler yang memiliki perilaku tekan tombol lama, event tombol pertama dengan nilai atribut repeat true HARUS menjadi indikasi tekan tombol lama. Durasi waktu yang harus tombol ditekan agar mulai mengulang tergantung pada konfigurasi. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true jika modifier tombol shift (Shift) aktif. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Digunakan untuk menunjukkan [`IEventTarget`](../ieventtarget/) ke mana event awalnya dikirim. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Digunakan untuk menentukan waktu (dalam milidetik relatif terhadap epoch) saat event dibuat. Karena beberapa sistem mungkin tidak menyediakan informasi ini, nilai timeStamp mungkin tidak tersedia untuk semua event. Jika tidak tersedia, nilai 0 akan dikembalikan. Contoh waktu epoch adalah waktu mulai sistem atau 0:0:0 UTC 1 Januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Nama event (tidak sensitif huruf). Nama harus berupa nama XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Atribut view mengidentifikasi Window tempat event dihasilkan. Nilai yang belum diinisialisasi untuk atribut ini HARUS null. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metode [`InitEvent`](../event/initevent/) digunakan untuk menginisialisasi nilai sebuah [`Event`](../event/) yang dibuat melalui antarmuka [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Jika sebuah event dapat dibatalkan, metode [`PreventDefault`](../event/preventdefault/) digunakan untuk menunjukkan bahwa event tersebut harus dibatalkan, artinya setiap aksi default yang biasanya dilakukan oleh implementasi sebagai hasil dari event tidak akan terjadi. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Memanggil metode ini mencegah event mencapai listener event apa pun yang terdaftar setelah yang saat ini dan ketika dikirim dalam sebuah pohon juga mencegah event mencapai objek lain. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metode [`StopPropagation`](../event/stoppropagation/) digunakan untuk mencegah propagasi lebih lanjut dari sebuah event selama alur event. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Tombol yang diaktifkan berasal dari lokasi tombol kiri (ketika ada lebih dari satu lokasi yang memungkinkan untuk tombol ini). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Aktivasi kunci berasal dari keypad numerik atau dengan tombol virtual yang sesuai dengan keypad numerik (ketika ada lebih dari satu lokasi yang mungkin untuk tombol ini). Perhatikan bahwa tombol NumLock harus selalu dikodekan dengan lokasi DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Aktivasi kunci berasal dari lokasi kunci kanan (ketika ada lebih dari satu lokasi yang mungkin untuk tombol ini). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Aktivasi kunci TIDAK BOLEH dibedakan sebagai versi kiri atau kanan dari tombol, dan (selain tombol NumLock) tidak berasal dari keypad numerik (atau tidak berasal dengan tombol virtual yang sesuai dengan keypad numerik). |

### Lihat Juga

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
