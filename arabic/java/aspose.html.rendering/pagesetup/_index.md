---
title: "PageSetup فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.rendering.PageSetup فئة. تمثل كائن إعداد الصفحة ويُستخدم لتكوين مجموعة صفحات الإخراج."
type: docs

url: /ar/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

يمثل كائن إعداد الصفحة يُستخدم لتكوين مجموعة صفحات الإخراج.

```java
public class PageSetup
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) يحصل على تكوين الصفحة الفردية. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) يحصل على تكوين الصفحة الزوجية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | يضبط تكوين الصفحة اليسرى/اليمنى. |

### انظر أيضًا

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
