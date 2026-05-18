---
title: "Kelas EpubRenderer"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.rendering.EpubRenderer. Mewakili renderer dokumen EPub"
type: docs

url: /id/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Mewakili renderer dokumen EPub.

```java
public class EpubRenderer : Renderer<Stream>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Mendefinisikan metode untuk merender beberapa dokumen EPub ke dalam sebuah [`IDevice`](../idevice/) tertentu, menggunakan token pembatalan untuk meminta pembatalan operasi. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Merender beberapa dokumen EPub ke dalam [`IDevice`](../idevice/) yang ditentukan. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Merender dokumen EPub ke dalam [`IDevice`](../idevice/) yang ditentukan. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Mendefinisikan metode untuk merender beberapa Stream EPub ke dalam [`IDevice`](../idevice/) tertentu. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Merender beberapa dokumen EPub ke dalam [`IDevice`](../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Merender dokumen EPub ke dalam [`IDevice`](../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu. |

### Lihat Juga

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
