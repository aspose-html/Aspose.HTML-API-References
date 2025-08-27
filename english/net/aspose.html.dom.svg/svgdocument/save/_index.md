---
title: SVGDocument.Save
second_title: Aspose.HTML for .NET API Reference
description: SVGDocument Save method. Saves the document to local file specified by url. All resources used in this document will be saved in to adjacent folder whose name will be constructed as output_file_name  _files. If the specified url ends with .svgz the document will be saved as a compressed SVGZ file
type: docs
weight: 90
url: /net/aspose.html.dom.svg/svgdocument/save/
---
## Save(*[Url](../../../aspose.html/url/)*) {#save_4}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". If the specified `url` ends with ".svgz", the document will be saved as a compressed SVGZ file.

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

### See Also

* class [Url](../../../aspose.html/url/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string*) {#save_8}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". If the specified `url` ends with ".svgz", the document will be saved as a compressed SVGZ file.

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

### See Also

* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
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
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)*) {#save_9}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveFormat | SVGSaveFormat | Format in which document is saved. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |
| ArgumentOutOfRangeException | Thrown when the specified *saveFormat* value is not recognised by the current implementation. |

### See Also

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)*) {#save_1}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Format in which document is saved. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the specified *saveFormat* value is not recognised by the current implementation. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)*) {#save_10}

Saves the document as an `.svg` file to the local path specified by *path*. Any external resources are written to a sibling folder named `{output_file_name}_files`.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Absolute or relative path of the target `.svg` file. |
| saveOptions | SVGSaveOptions | Options that control plain-SVG serialization. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown if *path* is not a valid local file path. |

### See Also

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)*) {#save_2}

Saves the document content and resources using the [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | SVG save options. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../../aspose.html/url/), [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)*) {#save_5}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveFormat | SVGSaveFormat | Format in which document is saved. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *url* does not represent a valid local file location (e.g., it is null, relative, or points to a non-file scheme). |
| ArgumentOutOfRangeException | Thrown when the supplied *saveFormat* value is not recognised by the current implementation. |

### See Also

* class [Url](../../../aspose.html/url/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../../aspose.html/url/), [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)*) {#save_6}

Saves the document as an `.svg` file to *url*. All external resources are placed in a sibling folder named `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local path of the target `.svg` file. |
| saveOptions | SVGSaveOptions | Options that control plain-SVG serialization. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown if *url* is not a valid local file path. |

### See Also

* class [Url](../../../aspose.html/url/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[Url](../../../aspose.html/url/), [SVGZSaveOptions](../../../aspose.html.dom.svg.saving/svgzsaveoptions/)*) {#save_7}

Saves the document as a compressed `.svgz` file to *url*. All external resources are placed in a sibling folder named `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local path of the target `.svgz` file. |
| saveOptions | SVGZSaveOptions | Options that control SVGZ serialization. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown if *url* is not a valid local file path. |

### See Also

* class [Url](../../../aspose.html/url/)
* class [SVGZSaveOptions](../../../aspose.html.dom.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*[ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.html.dom.svg.saving/svgzsaveoptions/)*) {#save_3}

Saves the document content and associated resources using the specified [`ResourceHandler`](../../../aspose.html.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | The resource handler to manage document resources, such as file system or memory-based storage. |
| saveOptions | SVGZSaveOptions | Options that specify additional saving parameters, such as vectorization preferences. |

### See Also

* class [ResourceHandler](../../../aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.html.dom.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.html.dom.svg.saving/svgzsaveoptions/)*) {#save_11}

Saves the document as a compressed `.svgz` file to the local path specified by *path*. Any external resources are written to a sibling folder named `{output_file_name}_files`.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Absolute or relative path of the target `.svgz` file. |
| saveOptions | SVGZSaveOptions | Options that control SVGZ serialization. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown if *path* is not a valid local file path. |

### See Also

* class [SVGZSaveOptions](../../../aspose.html.dom.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Html.Dom.Svg](../../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../../)
