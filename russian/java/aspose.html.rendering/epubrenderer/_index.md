---
title: "Класс EpubRenderer"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.EpubRenderer. Представляет рендерер EPub‑документов"
type: docs

url: /ru/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Представляет рендерер EPub-документов.

```java
public class EpubRenderer : Renderer<Stream>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Определяет метод для рендеринга нескольких EPub‑документов в конкретное [`IDevice`](../idevice/), используя токен отмены для запроса отмены операции. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Рендерит несколько EPub‑документов в указанный [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Рендерит EPub‑документ в указанный [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Определяет метод для рендеринга нескольких EPub‑потоков в конкретное [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет сетевых операций загрузки ресурсов, активных таймеров, анимационных задач или по истечении указанного тайм‑аута. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Рендерит несколько EPub‑документов в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет сетевых операций загрузки ресурсов, активных таймеров, анимационных задач или по истечении указанного тайм‑аута. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Рендерит EPub‑документ в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет сетевых операций загрузки ресурсов, активных таймеров, анимационных задач или по истечении указанного тайм‑аута. |

### См. также

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
