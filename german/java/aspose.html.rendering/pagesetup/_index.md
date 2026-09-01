---
title: "PageSetup‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.PageSetup‑Klasse. Stellt ein Seiten-Setup‑Objekt dar, das zur Konfiguration des Ausgabe‑Page‑Sets verwendet wird"
type: docs

url: /de/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Stellt ein Seiten-Einrichtungsobjekt dar, das zur Konfiguration des Ausgabe-Seitensatzes verwendet wird.

```java
public class PageSetup
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Ruft die Konfiguration der ungeraden Seite ab. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Ruft die Konfiguration der geraden Seite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Setzt die Links-/Rechts‑Seitenkonfiguration. |

### Siehe auch

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
