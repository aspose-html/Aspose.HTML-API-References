---
title: exclude_attachment method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.rendering/mhtmlrenderingoptions/exclude_attachment/
is_root: false
---

## exclude_attachment {#str}

Excludes a specific attachment from rendering by its URL.
Only used when [`MhtmlRenderingOptions.render_all_attachments`](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions#render_all_attachments) is true.



```python
def exclude_attachment(self, attachment_url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| attachment_url | str | The URL of the attachment to exclude. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `attachment_url` is null. |
| ArgumentException | Thrown when `attachment_url` is empty. |





### See Also
* module [`aspose.html.rendering`](../../)
* class [`MhtmlRenderingOptions`](/html/python-net/aspose.html.rendering/mhtmlrenderingoptions)
