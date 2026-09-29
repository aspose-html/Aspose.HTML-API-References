---
title: FileSystemResourceHandler.HandleResourceAsync
second_title: Aspose.HTML for .NET API Reference
description: FileSystemResourceHandler HandleResourceAsync method. This method is responsible for handling the resource asynchronously when the document is saved with a SaveAsync method. The resource is serialized to memory and written to the file system asynchronously as soon as it has been serialized the main document is written once the whole document has been serialized
type: docs
weight: 30
url: /net/aspose.html.saving.resourcehandlers/filesystemresourcehandler/handleresourceasync/
---
## FileSystemResourceHandler.HandleResourceAsync method

This method is responsible for handling the resource asynchronously when the document is saved with a `SaveAsync` method. The resource is serialized to memory and written to the file system asynchronously as soon as it has been serialized; the main document is written once the whole document has been serialized.

```csharp
public override Task HandleResourceAsync(Resource resource, ResourceHandlingContext context, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resource | Resource | The [`Resource`](../../../aspose.html.saving/resource/) which will be handled. |
| context | ResourceHandlingContext | Resource handling context. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A completed task: the files are queued with the save, which writes them and awaits them before it completes.

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

### See Also

* class [Resource](../../../aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.html.saving/resourcehandlingcontext/)
* class [FileSystemResourceHandler](../)
* namespace [Aspose.Html.Saving.ResourceHandlers](../../../aspose.html.saving.resourcehandlers/)
* assembly [Aspose.HTML](../../../)
