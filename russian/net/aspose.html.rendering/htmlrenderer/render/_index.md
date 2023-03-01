---
title: HtmlRenderer.Render
second_title: Справочник по Aspose.HTML для .NET API
description: HtmlRenderer метод. Определяет метод для рендеринга несколькихDocument в конкретныеIDevice . Рендеринг будет выполнен после того как не будет никаких сетевых операций для загрузки ресурсов активных таймеров задач анимации или истечет указанное время ожидания.
type: docs
weight: 20
url: /ru/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

Определяет метод для рендеринга нескольких[`Document`](../../../aspose.html.dom/document/) в конкретные[`IDevice`](../../idevice/) . Рендеринг будет выполнен после того, как не будет никаких сетевых операций для загрузки ресурсов, активных таймеров, задач анимации или истечет указанное время ожидания.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Выходное устройство. |
| timeout | TimeSpan | АTimeSpan который представляет количество миллисекунд ожидания, илиTimeSpan что представляет собой -1 миллисекунду ожидания на неопределенный срок. |
| documents | Document[] | Документы для оформления. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [Document](../../../aspose.html.dom/document/)
* class [HtmlRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../htmlrenderer/)
* сборка [Aspose.HTML](../../../)


