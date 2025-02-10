---
title: Resource.Embed
second_title: Aspose.HTML for Java API Reference
description: Resource method. Embeds this resource within its parent by encoding it as Base64. The encoding result will be written to OutputUrl
type: docs
weight: 60
url: /java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Embeds this resource within its parent by encoding it as Base64. The encoding result will be written to [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Type | Description |
| --- | --- | --- |
| context | ResourceHandlingContext | Resource handling context. |

### Return Value

This resource so that you can chain calls.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Raised if there is no [`ParentResource`](../../resourcehandlingcontext/parentresource/) because there is nowhere to embed the result. |

### See Also

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
