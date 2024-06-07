---
title: Resource class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.html.saving/resource/
is_root: false
---

## Resource class

This class describes a resource and provides methods for processing it.



The Resource type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [status](/html/python-net/aspose.html.saving/resource/status) | Returns the current status of the resource. |
| [mime_type](/html/python-net/aspose.html.saving/resource/mime_type) | Returns the [`MimeType`](/html/python-net/aspose.html/mimetype) of this resource. Can be  if the resource was not found. |
| [original_url](/html/python-net/aspose.html.saving/resource/original_url) | Returns a URL indicating where this resource was located. |
| [original_reference](/html/python-net/aspose.html.saving/resource/original_reference) | Returns a string containing the original reference to this resource. |
| [output_url](/html/python-net/aspose.html.saving/resource/output_url) | Gets or sets the URL indicating where the resource will be located after processing. |


### Methods
| Method | Description |
| :- | :- |
| [save](/html/python-net/aspose.html.saving/resource/save/#io.RawIOBase-aspose.html.saving.ResourceHandlingContext) | Saves the resource to the provided stream. |
| [embed](/html/python-net/aspose.html.saving/resource/embed/#aspose.html.saving.ResourceHandlingContext) | Embeds this resource within its parent by encoding it as Base64. The encoding result will be written to [`Resource.output_url`](/html/python-net/aspose.html.saving/resource#output_url). |
| [with_output_url](/html/python-net/aspose.html.saving/resource/with_output_url/#aspose.html.Url) | Specifies the new URL indicating where the resource will be located after processing. |



### See Also
* module [`aspose.html.saving`](..)
* class [`MimeType`](/html/python-net/aspose.html/mimetype)
