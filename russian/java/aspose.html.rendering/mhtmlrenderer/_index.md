---
title: "Класс MhtmlRenderer"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.MhtmlRenderer. Представляет рендерер MHTML‑документов"
type: docs

url: /ru/java/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

Представляет рендерер MHTML-документов.

```java
public class MhtmlRenderer : Renderer<Stream>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Определяет метод для рендеринга нескольких MHTML‑документов в конкретный [`IDevice`](../idevice/), используя токен отмены для запроса отмены операции. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Рендерит несколько MHTML‑документов в указанный [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | Рендерит MHTML‑документ в указанный [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Рендерит несколько MHTML‑документов в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Рендерит несколько MHTML‑документов в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Рендерит MHTML‑документ в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут. |

### См. также

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
