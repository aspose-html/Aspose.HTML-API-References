---
title: "HtmlRenderer.Render"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HtmlRenderer. Определяет метод для рендеринга нескольких HTMLDocuments в конкретный IDevice"
type: docs

url: /ru/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Определяет метод для рендеринга нескольких [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в конкретный [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| тайм-аут | TimeSpan | TimeSpan, представляющий количество миллисекунд ожидания, или TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |
| источники | HTMLDocument[] | HTML‑документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Определяет метод для рендеринга нескольких [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в конкретный [`IDevice`](../../idevice/), используя токен отмены для запроса отмены операции.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| cancellationToken | CancellationToken | Токен CancellationToken, наблюдаемый во время ожидания завершения задачи. |
| источники | HTMLDocument[] | HTML‑документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
