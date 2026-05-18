---
title: "Kelas Resource"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.saving.Resource. Kelas ini mendeskripsikan sebuah sumber daya dan menyediakan metode untuk memprosesnya"
type: docs

url: /id/java/com.aspose.html.saving/resource/
---
## Resource class

Kelas ini mendeskripsikan sebuah sumber daya dan menyediakan metode untuk memprosesnya.

```java
public class Resource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Mengembalikan [`MimeType`](../../com.aspose.html/mimetype/) dari sumber daya ini. Bisa `null` jika sumber daya tidak ditemukan. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Mengembalikan String yang berisi referensi asli ke sumber daya ini. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Mengembalikan URL yang menunjukkan lokasi sumber daya ini. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Mengembalikan status terkini dari sumber daya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Menyematkan sumber daya ini ke dalam induknya dengan mengkodekannya sebagai Base64. Hasil enkoding akan ditulis ke [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Menyimpan sumber daya ke aliran yang disediakan. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Menentukan URL baru yang menunjukkan di mana sumber daya akan berada setelah pemrosesan. |

### Lihat Juga

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
