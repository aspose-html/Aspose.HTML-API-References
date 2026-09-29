---
title: HTMLDocument.SaveAsync
second_title: Aspose.HTML for .NET API Reference
description: HTMLDocument SaveAsync method. Asynchronously saves the document to local file specified by path. All resources used in this document will be saved in to adjacent folder whose name will be constructed as output_file_name  _files
type: docs
weight: 140
url: /net/aspose.html/htmldocument/saveasync/
---
## SaveAsync(*string, [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/), CancellationToken*) {#saveasync_6}

Asynchronously saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public Task SaveAsync(string path, HTMLSaveOptions saveOptions, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | HTMLSaveOptions | HTML save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*[Url](../../url/), [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/), CancellationToken*) {#saveasync_3}

Asynchronously saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public Task SaveAsync(Url url, HTMLSaveOptions saveOptions, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | HTMLSaveOptions | HTML save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/), CancellationToken*) {#saveasync}

Asynchronously saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public Task SaveAsync(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). Its [`HandleResourceAsync`](../../../aspose.html.saving.resourcehandlers/resourcehandler/handleresourceasync/) method is used. |
| saveOptions | HTMLSaveOptions | HTML save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*string, [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/), CancellationToken*) {#saveasync_7}

Asynchronously saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public Task SaveAsync(string path, MarkdownSaveOptions saveOptions, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | MarkdownSaveOptions | Markdown save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*[Url](../../url/), [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/), CancellationToken*) {#saveasync_4}

Asynchronously saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public Task SaveAsync(Url url, MarkdownSaveOptions saveOptions, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | MarkdownSaveOptions | Markdown save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/), CancellationToken*) {#saveasync_1}

Asynchronously saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public Task SaveAsync(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). Its [`HandleResourceAsync`](../../../aspose.html.saving.resourcehandlers/resourcehandler/handleresourceasync/) method is used. |
| saveOptions | MarkdownSaveOptions | Markdown save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*string, [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/), CancellationToken*) {#saveasync_8}

Asynchronously saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public Task SaveAsync(string path, MHTMLSaveOptions saveOptions, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | MHTMLSaveOptions | MHTML save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*[Url](../../url/), [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/), CancellationToken*) {#saveasync_5}

Asynchronously saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public Task SaveAsync(Url url, MHTMLSaveOptions saveOptions, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | MHTMLSaveOptions | MHTML save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## SaveAsync(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/), CancellationToken*) {#saveasync_2}

Asynchronously saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public Task SaveAsync(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). Its [`HandleResourceAsync`](../../../aspose.html.saving.resourcehandlers/resourcehandler/handleresourceasync/) method is used. |
| saveOptions | MHTMLSaveOptions | MHTML save options. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A task that represents the asynchronous operation.

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

## Remarks

The method returns at once: the document is serialized on the thread pool and the output is written asynchronously. Resources that were not loaded with the document are downloaded during serialization, one after another unless [`MaxConcurrentRequests`](../../../aspose.html.saving/resourcehandlingoptions/maxconcurrentrequests/) is greater than 1.

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)
