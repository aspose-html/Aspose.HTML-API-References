---
title: Resource.Save
second_title: Aspose.HTML for Java API Reference
description: Resource method. Saves the resource to the provided stream
type: docs
weight: 70
url: /java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Saves the resource to the provided stream.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which the resource will be saved. |
| context | ResourceHandlingContext | Resource handling context. |

### Return Value

This resource so that you can chain calls.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Raised if [`OutputUrl`](../outputurl/) is `null`. [`OutputUrl`](../outputurl/) should be specified before saving the resource because otherwise it is impossible to specify the correct reference in the resources referencing this one. |

### See Also

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
