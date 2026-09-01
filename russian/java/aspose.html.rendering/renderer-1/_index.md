---
title: "Класс RendererTSource"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.rendering.Renderer1TSource класс. Представляет абстрактный класс для всех рендереров"
type: docs

url: /ru/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Представляет абстрактный класс для всех рендереров.

```java
public abstract class Renderer<TSource> : Renderer
```

| Параметр | Описание |
| --- | --- |
| TDocument | Тип документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Определяет метод для рендеринга !:TDocument в указанный [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Определяет метод для рендеринга !:TDocument в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм-аут. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Определяет метод для рендеринга !:TDocument в указанный [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм-аут. |

### См. также

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
