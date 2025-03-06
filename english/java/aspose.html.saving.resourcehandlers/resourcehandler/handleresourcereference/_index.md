---
title: ResourceHandler.HandleResourceReference
second_title: Aspose.HTML for Java API Reference
description: ResourceHandler method. This method is responsible for handling the resource reference. In this method you can set what the reference to the resource being handled will look like
type: docs

url: /java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

This method is responsible for handling the resource reference. In this method, you can set what the reference to the resource being handled will look like.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resource | Resource | The [`Resource`](../../../com.aspose.html.saving/resource/) which will be handled. |
| context | ResourceHandlingContext | Resource handling context. |

### Return Value

A String that will be written to the parent resource and which represents a reference to the resource that is currently being handled.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Raised if [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) is `null` and [`Status`](../../../com.aspose.html.saving/resource/status/) is Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) should be specified for saved resource because otherwise it is impossible to specify the correct reference in the resources referencing this one. |

### See Also

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
