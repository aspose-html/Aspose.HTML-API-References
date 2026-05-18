---
title: "Kelas MutationObserver"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.mutations.MutationObserver class. Sebuah objek dapat digunakan untuk mengamati mutasi pada pohon"
type: docs

url: /id/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Sebuah objek dapat digunakan untuk mengamati mutasi pada pohon [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Membuat objek MutationObserver dan menetapkan [`MutationCallback`](../mutationcallback/)nya ke callback. Callback dipanggil dengan daftar objek MutationRecord sebagai argumen pertama dan objek MutationObserver yang dibuat sebagai argumen kedua. Callback dipanggil setelah node yang terdaftar dengan metode !:Observe(Node, IMutationObserverInit) mengalami mutasi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Menghentikan pengamat dari mengamati mutasi apa pun. Sampai metode observe() digunakan lagi, callback pengamat tidak akan dipanggil. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Menginstruksikan agen pengguna untuk mengamati target tertentu (sebuah node) dan melaporkan mutasi apa pun berdasarkan kriteria yang diberikan oleh opsi (sebuah objek). Argumen opsi memungkinkan pengaturan opsi pengamatan mutasi melalui anggota objek. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Menginstruksikan agen pengguna untuk mengamati target tertentu (sebuah node) dan melaporkan mutasi apa pun berdasarkan kriteria yang diberikan oleh opsi (sebuah objek). Argumen opsi memungkinkan pengaturan opsi pengamatan mutasi melalui anggota objek. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | Metode ini mengembalikan salinan antrian catatan dan kemudian mengosongkan antrian catatan. |

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
