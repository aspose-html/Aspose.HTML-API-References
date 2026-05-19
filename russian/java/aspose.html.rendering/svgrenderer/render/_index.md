---
title: "SvgRenderer.Render"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SvgRenderer. Определяет метод для рендеринга нескольких SVGDocument в конкретный IDevice. Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут."
type: docs

url: /ru/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Определяет метод для рендеринга нескольких [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в конкретный [`IDevice`](../../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| тайм-аут | TimeSpan | TimeSpan, представляющий количество миллисекунд ожидания, или TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |
| документы | SVGDocument[] | Документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Определяет метод для рендеринга нескольких [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в конкретный [`IDevice`](../../idevice/), используя токен отмены для запроса отмены операции.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| cancellationToken | CancellationToken | Токен отмены, который следует отслеживать во время ожидания завершения задачи. |
| источники | SVGDocument[] | SVG‑документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
