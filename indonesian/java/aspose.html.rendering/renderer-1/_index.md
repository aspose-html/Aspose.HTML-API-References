---
title: "Kelas RendererTSource"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.rendering.Renderer1TSource. Mewakili kelas abstrak untuk semua renderer"
type: docs

url: /id/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Mewakili kelas abstrak untuk semua renderer.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Deskripsi |
| --- | --- |
| TDocument | Tipe dokumen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Mendefinisikan metode untuk merender !:TDocument ke [`IDevice`](../idevice/) yang ditentukan. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Mendefinisikan metode untuk merender !:TDocument ke [`IDevice`](../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Mendefinisikan metode untuk merender !:TDocument ke [`IDevice`](../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu. |

### Lihat Juga

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
