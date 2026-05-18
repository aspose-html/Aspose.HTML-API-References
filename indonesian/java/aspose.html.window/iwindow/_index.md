---
title: "Antarmuka IWindow"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.window.IWindow antarmuka. Objek window mewakili sebuah jendela yang berisi dokumen DOM"
type: docs

url: /id/java/com.aspose.html.window/iwindow/
---
## IWindow interface

Objek window mewakili sebuah jendela yang berisi dokumen DOM.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) Atribut document harus mengembalikan objek Document terbaru dari objek Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Objek frameElement dari sebuah Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Mengembalikan objek Storage yang memungkinkan Anda menyimpan pasangan kunci/nilai di agen pengguna. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Atribut location dari antarmuka Window harus mengembalikan objek Location untuk Document objek Window tersebut. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Atribut IDL opener pada objek Window, saat dibaca, harus mengembalikan objek WindowProxy dari konteks penjelajahan yang membuat konteks penjelajahan saat ini (konteks penjelajahan pembukanya), jika ada, jika masih tersedia, dan jika konteks penjelajahan saat ini belum melepaskan pembukanya; jika tidak, harus mengembalikan null. Saat disetel, jika nilai baru adalah null maka konteks penjelajahan saat ini harus melepaskan pembukanya; jika nilai baru bukan null maka agen pengguna harus memanggil metode internal [[DefineOwnProperty]] dari objek Window, dengan melewatkan nama properti "opener" sebagai kunci properti, dan Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } sebagai deskriptor properti, di mana value adalah nilai baru. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) Atribut IDL parent pada objek Window dari sebuah Document dalam konteks penjelajahan b harus mengembalikan objek WindowProxy dari konteks penjelajahan induk, jika ada (misalnya jika b adalah konteks penjelajahan anak), atau objek WindowProxy dari konteks penjelajahan b itu sendiri, jika tidak (misalnya jika itu adalah konteks penjelajahan tingkat atas atau konteks penjelajahan bersarang yang terlepas). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Mengembalikan objek WindowProxy dari konteks penjelajahan objek Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) Atribut IDL top pada objek Window dari sebuah Document dalam konteks penjelajahan b harus mengembalikan objek WindowProxy dari konteks penjelajahan tingkat atasnya (yang akan menjadi objek WindowProxy miliknya sendiri jika ia merupakan konteks penjelajahan tingkat atas), jika ada, atau objek WindowProxy miliknya sendiri jika tidak (misalnya jika ia merupakan konteks penjelajahan bersarang yang terlepas). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Mengembalikan objek WindowProxy dari konteks penjelajahan objek Window. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Menampilkan peringatan modal dengan pesan yang diberikan, dan menunggu pengguna untuk menutupnya. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Mengambil data masukan, dalam bentuk String Unicode yang berisi data biner yang dikodekan base64, mendekodenya, dan mengembalikan String yang terdiri dari karakter dalam rentang U+0000 hingga U+00FF, masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan, yang sesuai dengan data biner tersebut. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Mengambil data masukan, dalam bentuk String Unicode yang hanya berisi karakter dalam rentang U+0000 hingga U+00FF, masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan, dan mengonversinya ke representasi base64-nya, yang kemudian dikembalikan. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Menampilkan prompt modal OK/Batal dengan pesan yang diberikan, menunggu pengguna untuk menutupnya, dan mengembalikan true jika pengguna mengklik OK dan false jika pengguna mengklik Batal. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Mengembalikan objek MediaQueryList baru yang kemudian dapat digunakan untuk menentukan apakah dokumen cocok dengan String kueri media, serta untuk memantau dokumen guna mendeteksi kapan ia cocok (atau berhenti cocok) dengan kueri media tersebut. Lihat spesifikasi CSSOM View Module: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Menampilkan prompt bidang teks modal dengan pesan yang diberikan, menunggu pengguna untuk menutupnya, dan mengembalikan nilai yang dimasukkan pengguna. Jika pengguna membatalkan prompt, maka mengembalikan null sebagai gantinya. Jika argumen kedua ada, maka nilai yang diberikan digunakan sebagai nilai default. |

### Lihat Juga

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
