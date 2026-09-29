---
title: ResourceHandler.HandleResourceAsync
second_title: Aspose.HTML for .NET API Reference
description: ResourceHandler HandleResourceAsync method. This method is responsible for handling the resource asynchronously when the document is saved with a SaveAsync method. In it you can save the Resource to the stream or embed it into the parent resource and then complete the work asynchronously for example write the saved content to a remote storage
type: docs
weight: 20
url: /net/aspose.html.saving.resourcehandlers/resourcehandler/handleresourceasync/
---
## ResourceHandler.HandleResourceAsync method

This method is responsible for handling the resource asynchronously when the document is saved with a `SaveAsync` method. In it you can save the [`Resource`](../../../aspose.html.saving/resource/) to the stream or embed it into the parent resource, and then complete the work asynchronously, for example write the saved content to a remote storage.

```csharp
public virtual Task HandleResourceAsync(Resource resource, ResourceHandlingContext context, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resource | Resource | The [`Resource`](../../../aspose.html.saving/resource/) which will be handled. |
| context | ResourceHandlingContext | Resource handling context. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous part of the handling.

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

## Remarks

[`Save`](../../../aspose.html.saving/resource/save/) or [`Embed`](../../../aspose.html.saving/resource/embed/) must be called before the method returns (before its first `await`), because the reference to the resource is written to the parent resource as soon as the method returns. The returned task is awaited when the document has been serialized. The default implementation calls [`HandleResource`](../handleresource/).

### See Also

* class [Resource](../../../aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Html.Saving.ResourceHandlers](../../../aspose.html.saving.resourcehandlers/)
* assembly [Aspose.HTML](../../../)
