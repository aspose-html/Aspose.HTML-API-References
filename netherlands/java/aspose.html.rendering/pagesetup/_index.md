---
title: "PageSetup Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.PageSetup klasse. Vertegenwoordigt een paginainstellingsobject dat wordt gebruikt voor de configuratie van de uitvoerpagina-set"
type: docs

url: /nl/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Stelt een page-setup-object voor dat wordt gebruikt voor de configuratie van de uitvoer-page-set.

```java
public class PageSetup
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Haalt de configuratie van de oneven pagina op. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Haalt de configuratie van de even pagina op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Stelt de linker/rechter paginaconfiguratie in. |

### Zie ook

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
