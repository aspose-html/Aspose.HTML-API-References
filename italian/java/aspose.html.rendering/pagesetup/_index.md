---
title: "PageSetup Classe"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.rendering.PageSetup classe. Rappresenta un oggetto di configurazione della pagina utilizzato per la configurazione dell'output del set di pagine"
type: docs

url: /it/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Rappresenta un oggetto di configurazione della pagina utilizzato per la configurazione dell'output del set di pagine.

```java
public class PageSetup
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Ottiene la configurazione della Pagina Dispari. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Ottiene la configurazione della Pagina Pari. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Imposta la configurazione della pagina Sinistra/Destra. |

### Vedi anche

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
