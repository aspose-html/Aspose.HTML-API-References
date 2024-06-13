﻿---
title: PageLayoutOptions enumeration
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/aspose.html.rendering/pagelayoutoptions/
is_root: false
---

## PageLayoutOptions enumeration

Specifies flags that together with other PageSetup options determine sizes and layouts of pages.
These flags can be combined together according to their descriptions.



The PageLayoutOptions type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NONE | Default value which indicates that the PageLayoutOptions will not affect the sizes and layouts of pages. |
| FIT_TO_CONTENT_WIDTH | This flag indicates that the width of the pages is determined from the content size itself, not from the specified page width.
| USE_WIDEST_PAGE | When combined with [`PageLayoutOptions.FIT_TO_CONTENT_WIDTH`](/html/python-net/aspose.html.rendering/pagelayoutoptions#FIT_TO_CONTENT_WIDTH) indicates that the width of every page will be the same and will be equal to the widest content size among all pages. |
| FIT_TO_WIDEST_CONTENT_WIDTH | This flag indicates that the width of the page is determined from the content size itself, not from the specified page width.
| FIT_TO_CONTENT_HEIGHT | This flag indicates that the height of the page is determined from the content size itself, not from the specified page height.
| SCALE_TO_PAGE_WIDTH | This flag indicates that the content of the document will be scaled to fit the page where the difference between the available page width and the overlapping content is greatest.
| SCALE_TO_PAGE_HEIGHT | This flag indicates that the content of the document will be scaled to fit the height of the first page.



### See Also
* module [`aspose.html.rendering`](..)