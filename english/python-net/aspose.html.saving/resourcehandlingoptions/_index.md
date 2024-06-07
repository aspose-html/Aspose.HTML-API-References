---
title: ResourceHandlingOptions class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.html.saving/resourcehandlingoptions/
is_root: false
---

## ResourceHandlingOptions class

Represents resource handling options.



The ResourceHandlingOptions type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [java_script](/html/python-net/aspose.html.saving/resourcehandlingoptions/java_script) | Gets or sets enum which represents the way scripts are handled. Currently [`ResourceHandling.SAVE`](/html/python-net/aspose.html.saving/resourcehandling#SAVE), [`ResourceHandling.IGNORE`](/html/python-net/aspose.html.saving/resourcehandling#IGNORE), [`ResourceHandling.DISCARD`](/html/python-net/aspose.html.saving/resourcehandling#DISCARD) and [`ResourceHandling.EMBED`](/html/python-net/aspose.html.saving/resourcehandling#EMBED) values are supported. Default value is [`ResourceHandling.SAVE`](/html/python-net/aspose.html.saving/resourcehandling#SAVE). |
| [default](/html/python-net/aspose.html.saving/resourcehandlingoptions/default) | Gets or sets enum which represents default way of resources handling. Currently [`ResourceHandling.SAVE`](/html/python-net/aspose.html.saving/resourcehandling#SAVE), [`ResourceHandling.IGNORE`](/html/python-net/aspose.html.saving/resourcehandling#IGNORE) and [`ResourceHandling.EMBED`](/html/python-net/aspose.html.saving/resourcehandling#EMBED) values are supported. Default value is [`ResourceHandling.SAVE`](/html/python-net/aspose.html.saving/resourcehandling#SAVE). |
| [resource_url_restriction](/html/python-net/aspose.html.saving/resourcehandlingoptions/resource_url_restriction) | Gets or sets restriction applied to URLs of handled resources such as css, js, images etc. Default value is [`UrlRestriction.SAME_HOST`](/html/python-net/aspose.html.saving/urlrestriction#SAME_HOST). |
| [page_url_restriction](/html/python-net/aspose.html.saving/resourcehandlingoptions/page_url_restriction) | Gets or sets restriction applied to URLs of handled pages. Default value is [`UrlRestriction.ROOT_AND_SUB_FOLDERS`](/html/python-net/aspose.html.saving/urlrestriction#ROOT_AND_SUB_FOLDERS). |
| [max_handling_depth](/html/python-net/aspose.html.saving/resourcehandlingoptions/max_handling_depth) | Gets or sets maximum depth of pages which will be handled. Depth of 1 means that only pages directly referenced from the saved document will be handled. Setting this property to -1 will lead to handling of all pages. Default value is 0. |



### See Also
* module [`aspose.html.saving`](..)
