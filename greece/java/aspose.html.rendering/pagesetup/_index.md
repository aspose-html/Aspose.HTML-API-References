---
title: "PageSetup Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.PageSetup κλάση. Αντιπροσωπεύει ένα αντικείμενο ρύθμισης σελίδας που χρησιμοποιείται για τη διαμόρφωση της εξόδου page-set."
type: docs

url: /el/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Αναπαριστά ένα αντικείμενο ρύθμισης σελίδας που χρησιμοποιείται για τη διαμόρφωση του συνόλου εξόδου σελίδας.

```java
public class PageSetup
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Λαμβάνει τη διαμόρφωση Odd Page. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Λαμβάνει τη διαμόρφωση Even Page. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Ορίζει τη διαμόρφωση σελίδας Left/Right. |

### Δείτε επίσης

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
