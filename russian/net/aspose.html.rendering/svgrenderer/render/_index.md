---
title: SvgRenderer.Render
second_title: Справочник по Aspose.HTML для .NET API
description: SvgRenderer метод. Определяет метод для рендеринга несколькихSVGDocument в конкретныеIDevice . Рендеринг будет выполнен после того как не будет никаких сетевых операций для загрузки ресурсов активных таймеров задач анимации или истечет указанное время ожидания.
type: docs
weight: 20
url: /ru/net/aspose.html.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Определяет метод для рендеринга нескольких[`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/) в конкретные[`IDevice`](../../idevice/) . Рендеринг будет выполнен после того, как не будет никаких сетевых операций для загрузки ресурсов, активных таймеров, задач анимации или истечет указанное время ожидания.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Выходное устройство. |
| timeout | TimeSpan | АTimeSpan который представляет количество миллисекунд ожидания, илиTimeSpan что представляет собой -1 миллисекунду ожидания на неопределенный срок. |
| documents | SVGDocument[] | Документы для оформления. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../svgrenderer/)
* сборка [Aspose.HTML](../../../)


