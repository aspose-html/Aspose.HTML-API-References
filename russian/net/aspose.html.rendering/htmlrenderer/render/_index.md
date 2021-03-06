---
title: Render
second_title: Справочник по Aspose.HTML для .NET API
description: Определяет метод для рендеринга несколькихDocumentaspose.html.dom/documents в конкретныйIDeviceaspose.html.rendering/idevice. Рендеринг будет выполнен после того как не будет никаких сетевых операций по загрузке ресурсов активных таймеров задач анимации или истечет указанный тайм-аут.
type: docs
weight: 20
url: /ru/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

Определяет метод для рендеринга нескольких[`Document`](../../../aspose.html.dom/document)s в конкретный[`IDevice`](../../idevice). Рендеринг будет выполнен после того, как не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, задач анимации или истечет указанный тайм-аут.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Устройство вывода. |
| timeout | TimeSpan | ATimeSpanкоторый представляет количество миллисекунд ожидания, илиTimeSpan, который представляет собой -1 миллисекунду для бесконечного ожидания. |
| documents | Document[] | Документы для визуализации. |

### Смотрите также

* interface [IDevice](../../idevice)
* class [Document](../../../aspose.html.dom/document)
* class [HtmlRenderer](../../htmlrenderer)
* пространство имен [Aspose.Html.Rendering](../../htmlrenderer)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
