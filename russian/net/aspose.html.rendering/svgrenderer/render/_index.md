---
title: Render
second_title: Справочник по Aspose.HTML для .NET API
description: Определяет метод для рендеринга несколькихSVGDocumentaspose.html.dom.svg/svgdocuments в определенныеIDeviceaspose.html.rendering/idevice. Рендеринг будет выполнен после того как не будет никаких сетевых операций по загрузке ресурсов активных таймеров задач анимации или истечет указанный тайм-аут.
type: docs
weight: 20
url: /ru/net/aspose.html.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Определяет метод для рендеринга нескольких[`SVGDocument`](../../../aspose.html.dom.svg/svgdocument)s в определенные[`IDevice`](../../idevice). Рендеринг будет выполнен после того, как не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, задач анимации или истечет указанный тайм-аут.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Устройство вывода. |
| timeout | TimeSpan | ATimeSpanкоторый представляет количество миллисекунд ожидания, илиTimeSpan, который представляет собой -1 миллисекунду для бесконечного ожидания. |
| documents | SVGDocument[] | Документы для визуализации. |

### Смотрите также

* interface [IDevice](../../idevice)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [SvgRenderer](../../svgrenderer)
* пространство имен [Aspose.Html.Rendering](../../svgrenderer)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->