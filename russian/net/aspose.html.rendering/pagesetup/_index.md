---
title: Class PageSetup
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Rendering.PageSetup сорт. Представляет объект настройки страницы используемый для набора страниц вывода конфигурации.
type: docs
weight: 4390
url: /ru/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Представляет объект настройки страницы, используемый для набора страниц вывода конфигурации.

```csharp
public class PageSetup
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | Получает или устанавливает флаг, определяющий случай, когда размер страницы будет приведен в соответствие с самой широкой страницей в документе. Эта опция занимает много времени, поэтому время обработки документа может быть увеличено в два раза. Настройка будет иметь место только в том случае, если самая широкая страница в документе шире, чем размер страницы, определенный в`PageSetup` . Размер страницы Adjusted будет использоваться для всех страниц документа. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | Получает или задает конфигурацию всех страниц в последовательности страниц. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | Получает или устанавливает[`AtPagePriority`](../atpagepriority/) который будет определять порядок применения объявлений размера страницы. По умолчанию параметры переопределяют css`@страница` правила . |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | Получает или задает конфигурацию первой страницы. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | Получает конфигурацию нечетной страницы. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | Получает или задает[`PageLayoutOptions`](../pagelayoutoptions/) . Значение по умолчаниюNone , любое другое значение переопределит[`AdjustToWidestPage`](./adjusttowidestpage/) поведение. Работает только с документами HTML. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | Получает конфигурацию четной страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Устанавливает конфигурацию левой/правой страницы. |

### Смотрите также

* пространство имен [Aspose.Html.Rendering](../../aspose.html.rendering/)
* сборка [Aspose.HTML](../../)


