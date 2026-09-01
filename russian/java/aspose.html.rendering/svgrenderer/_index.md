---
title: "Класс SvgRenderer"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.SvgRenderer. Представляет отрисовщик SVG‑документов."
type: docs

url: /ru/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

Представляет рендерер SVG-документов.

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | Определяет метод для рендеринга нескольких [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/) в конкретное [`IDevice`](../idevice/), используя токен отмены для запроса отмены операции. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | Определяет метод для рендеринга нескольких [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/) в конкретное [`IDevice`](../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм-аут. |

### См. также

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
