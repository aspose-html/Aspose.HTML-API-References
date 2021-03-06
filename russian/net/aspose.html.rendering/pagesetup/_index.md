---
title: PageSetup
second_title: Справочник по Aspose.HTML для .NET API
description: Представляет объект настройки страницы используемый для настройки вывода набора страниц.
type: docs
weight: 4470
url: /ru/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Представляет объект настройки страницы, используемый для настройки вывода набора страниц.

```csharp
public class PageSetup
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage) { get; set; } | Получает или устанавливает флаг, определяющий случай, когда размер страницы будет скорректирован до самой широкой страницы в документе. Этот вариант требует много времени, поэтому время обработки документов может быть увеличено в два раза. Регулировка будет иметь место, только если самая широкая страница в документе шире, чем размер страницы, определенный в[`PageSetup`](../pagesetup). Скорректированный размер страницы будет использоваться для всех страниц в документе. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage) { get; set; } | Получает или задает конфигурацию всех страниц в последовательности страниц. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority) { get; set; } | Получает или устанавливает[`AtPagePriority`](../atpagepriority), который будет определять порядок применения объявлений размера страницы. По умолчанию параметры переопределяют css` @page` rules. |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage) { get; set; } | Получает или задает конфигурацию первой страницы. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage) { get; } | Получает конфигурацию нечетной страницы. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions) { get; set; } | Получает или задает[`PageLayoutOptions`](../pagelayoutoptions). Значение по умолчанию —None, любое другое значение переопределит поведение[`AdjustToWidestPage`](./adjusttowidestpage). Работает только с документами HTML. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage) { get; } | Получает конфигурацию четной страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage)(Page, Page) | Устанавливает конфигурацию левой/правой страницы. |

### Смотрите также

* пространство имен [Aspose.Html.Rendering](../../aspose.html.rendering)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
