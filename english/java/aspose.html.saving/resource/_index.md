---
title: Resource Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.Resource class. This class describes a resource and provides methods for processing it
type: docs
weight: 4890
url: /java/com.aspose.html.saving/resource/
---
## Resource class

This class describes a resource and provides methods for processing it.

```java
public class Resource
```

## Properties

| Name | Description |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Returns the [`MimeType`](../../com.aspose.html/mimetype/) of this resource. Can be `null` if the resource was not found. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Returns a String containing the original reference to this resource. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Returns a URL indicating where this resource was located. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Returns the current status of the resource. |

## Methods

| Name | Description |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Embeds this resource within its parent by encoding it as Base64. The encoding result will be written to [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Saves the resource to the provided stream. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Specifies the new URL indicating where the resource will be located after processing. |

### See Also

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
