---
title: PageSetup class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 90
url: /python-net/aspose.html.rendering/pagesetup/
is_root: false
---

## PageSetup class

Represents a page setup object is used for configuration output page-set.



The PageSetup type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [at_page_priority](/html/python-net/aspose.html.rendering/pagesetup/at_page_priority) | Gets or sets [`AtPagePriority`](/html/python-net/aspose.html.rendering/atpagepriority) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
| [page_layout_options](/html/python-net/aspose.html.rendering/pagesetup/page_layout_options) | Gets or sets the [`PageLayoutOptions`](/html/python-net/aspose.html.rendering/pagelayoutoptions). Default value is [`PageLayoutOptions.NONE`](/html/python-net/aspose.html.rendering/pagelayoutoptions#NONE), any other value will override the [`PageSetup.adjust_to_widest_page`](/html/python-net/aspose.html.rendering/pagesetup#adjust_to_widest_page) behaviour. Works only with HTML documents. |
| [adjust_to_widest_page](/html/python-net/aspose.html.rendering/pagesetup/adjust_to_widest_page) | Gets or sets flag that determines case when page size will be adjusted to widest page in document.<br/>This options is time-consuming so time of document processing can be increased in two times. Adjustment will<br/>take place only if widest page in document is wider than page size determined in [`PageSetup`](/html/python-net/aspose.html.rendering/pagesetup). Adjusted<br/>page size will be used for all pages in document. |
| [left_page](/html/python-net/aspose.html.rendering/pagesetup/left_page) | Gets the Odd Page configuration. |
| [right_page](/html/python-net/aspose.html.rendering/pagesetup/right_page) | Gets the Even Page configuration. |
| [any_page](/html/python-net/aspose.html.rendering/pagesetup/any_page) | Gets or sets all pages configuration in the the page-sequence. |
| [first_page](/html/python-net/aspose.html.rendering/pagesetup/first_page) | Gets or sets the first page configuration. |


### Methods
| Method | Description |
| :- | :- |
| [set_left_right_page](/html/python-net/aspose.html.rendering/pagesetup/set_left_right_page/#aspose.html.drawing.Page-aspose.html.drawing.Page) | Sets the Left/Right page configuration. |



### See Also
* module [`aspose.html.rendering`](..)
* class [`AtPagePriority`](/html/python-net/aspose.html.rendering/atpagepriority)
* class [`PageLayoutOptions`](/html/python-net/aspose.html.rendering/pagelayoutoptions)
* class [`PageSetup`](/html/python-net/aspose.html.rendering/pagesetup)
