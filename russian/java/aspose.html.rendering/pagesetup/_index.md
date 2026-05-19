---
title: "Класс PageSetup"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.PageSetup. Представляет объект настройки страницы, используемый для конфигурации вывода набора страниц."
type: docs

url: /ru/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Представляет объект настройки страницы, используемый для конфигурации набора выводимых страниц.

```java
public class PageSetup
```

## Свойства

| Имя | Описание |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Получает конфигурацию нечётной страницы. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Получает конфигурацию чётной страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Устанавливает конфигурацию левой/правой страницы. |

### См. также

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
