---
title: MhtmlRenderingOptions class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.html.rendering/mhtmlrenderingoptions/
is_root: false
---

## MhtmlRenderingOptions class

Represents options for rendering MHTML documents with attachment selection.



The MhtmlRenderingOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/__init__/#) | Initializes a new instance of the [`MhtmlRenderingOptions`](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [render_all_attachments](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/render_all_attachments) | Gets or sets a value indicating whether to render all attachments found in the MHTML document.<br/>When true (default), all attachments are rendered.<br/>When false, only explicitly selected attachments are rendered. |


### Methods
| Method | Description |
| :- | :- |
| [select_attachment](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/select_attachment/#str) | Selects a specific attachment for rendering by its URL. |
| [select_attachments](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/select_attachments/#list) |  |
| [exclude_attachment](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/exclude_attachment/#str) | Excludes a specific attachment from rendering by its URL.<br/>Only used when [`MhtmlRenderingOptions.render_all_attachments`](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions#render_all_attachments) is true. |
| [exclude_attachments](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/exclude_attachments/#list) |  |
| [reset](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/reset/#) | Clears all attachment selection/exclusion settings and restores default behavior. |
| [should_render_attachment](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions/should_render_attachment/#str) | Determines whether a specific attachment should be rendered based on the current options. |



### See Also
* module [`aspose.html.rendering`](..)
* class [`MhtmlRenderingOptions`](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions)
