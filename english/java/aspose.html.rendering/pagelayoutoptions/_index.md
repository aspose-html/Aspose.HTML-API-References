---
title: PageLayoutOptions Enum
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.PageLayoutOptions enum. Specifies flags that together with other PageSetup options determine sizes and layouts of pages. These flags can be combined together according to their descriptions
type: docs
weight: 4590
url: /java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Specifies flags that together with other PageSetup options determine sizes and layouts of pages. These flags can be combined together according to their descriptions.

```java
[Flags]
public enum PageLayoutOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | Default value which indicates that the PageLayoutOptions will not affect the sizes and layouts of pages. |
| FitToContentWidth | `1` | This flag indicates that the width of the pages is determined from the content size itself, not from the specified page width. The width of content is calculated individually for every page. |
| UseWidestPage | `2` | When combined with FitToContentWidth indicates that the width of every page will be the same and will be equal to the widest content size among all pages. |
| FitToWidestContentWidth | `3` | This flag indicates that the width of the page is determined from the content size itself, not from the specified page width. The width of every page will be the same and will be equal to the widest content size among all pages. |
| FitToContentHeight | `10` | This flag indicates that the height of the page is determined from the content size itself, not from the specified page height. All the documents content will be located on the single page if this flag is specified. |
| ScaleToPageWidth | `100` | This flag indicates that the content of the document will be scaled to fit the page where the difference between the available page width and the overlapping content is greatest. It collides with FitToContentWidth flag and if both flags are specified only ScaleToPageWidth will take affect. |
| ScaleToPageHeight | `1000` | This flag indicates that the content of the document will be scaled to fit the height of the first page. It collides with FitToContentHeight flag and if both flags are specified only ScaleToPageHeight will take affect. All document content will be placed on the single page only. |

### See Also

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
