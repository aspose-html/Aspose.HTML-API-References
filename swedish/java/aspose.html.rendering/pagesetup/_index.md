---
title: "PageSetup klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.PageSetup klass. Representerar ett sidinställningsobjekt som används för konfiguration av utdata‑siduppsättning"
type: docs

url: /sv/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Representerar ett sidinställningsobjekt som används för konfiguration av utskriftssiduppsättning.

```java
public class PageSetup
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Hämtar konfigurationen för udda sidor. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Hämtar konfigurationen för jämna sidor. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Ställer in konfigurationen för vänster/höger sida. |

### Se även

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
