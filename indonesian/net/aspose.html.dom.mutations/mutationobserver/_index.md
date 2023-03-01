---
title: Class MutationObserver
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Mutations.MutationObserver kelas. AMutationObserver objek dapat digunakan untuk mengamati mutasi pada pohonNode .
type: docs
weight: 970
url: /id/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver` objek dapat digunakan untuk mengamati mutasi pada pohon[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Membuat objek MutationObserver dan menyetelnya[`MutationCallback`](../mutationcallback/) untuk menelepon kembali. Callback dipanggil dengan daftar objek MutationRecord sebagai argumen pertama dan objek MutationObserver yang dibangun sebagai argumen kedua. Itu dipanggil setelah node terdaftar dengan!:Observe(Node, IMutationObserverInit) metode, dimutasi. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Menghentikan pengamat untuk mengamati mutasi apa pun. Sampai metode observasi() digunakan lagi, panggilan balik pengamat tidak akan dipanggil. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Menginstruksikan agen pengguna untuk mengamati target yang diberikan (node) dan melaporkan setiap mutasi berdasarkan kriteria yang diberikan oleh opsi (objek). Argumen opsi memungkinkan pengaturan opsi observasi mutasi melalui anggota objek. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Menginstruksikan agen pengguna untuk mengamati target yang diberikan (node) dan melaporkan setiap mutasi berdasarkan kriteria yang diberikan oleh opsi (objek). Argumen opsi memungkinkan pengaturan opsi observasi mutasi melalui anggota objek. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | Metode mengembalikan salinan antrean rekaman lalu mengosongkan antrean rekaman. |

### Lihat juga

* class [DOMObject](../../aspose.html.dom/domobject/)
* ruang nama [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* perakitan [Aspose.HTML](../../)


