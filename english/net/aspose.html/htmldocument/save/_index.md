---
title: HTMLDocument.Save
second_title: Aspose.HTML for .NET API Reference
description: HTMLDocument Save method. Saves the document to local file specified by url. All resources used in this document will be saved in to adjacent folder whose name will be constructed as output_file_name  _files
type: docs
weight: 130
url: /net/aspose.html/htmldocument/save/
---
## Save(*[Url](../../url/)*) {#save_5}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [Url](../../url/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)*) {#save}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string*) {#save_10}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)*) {#save_11}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveFormat | HTMLSaveFormat | Format in which document is saved. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../url/), [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)*) {#save_6}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveFormat | HTMLSaveFormat | Format in which document is saved. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)*) {#save_1}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Format in which document is saved. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)*) {#save_12}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | HTMLSaveOptions | HTML save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../url/), [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)*) {#save_7}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | HTMLSaveOptions | HTML save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)*) {#save_2}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | HTML save options. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)*) {#save_13}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | MarkdownSaveOptions | Markdown save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../url/), [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)*) {#save_8}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | MarkdownSaveOptions | Markdown save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)*) {#save_3}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Markdown save options. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)*) {#save_14}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | MHTMLSaveOptions | MHTML save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../url/), [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)*) {#save_9}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | MHTMLSaveOptions | MHTML save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

## Remarks

Save HTML

Most of the tasks, you need to perform, require saving a document. Once you load the existing file or create an HTML document from scratch, you can save your changes using one of HTMLDocument.Save() methods. The methods allow saving HTML to a local file specified by path, URL, or output storage. Refer to the [documentation](https://docs.aspose.com/html/net/save-html-document/) to learn more about saving.

### See Also

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)*) {#save_4}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | MHTML save options. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)
