---
title: Save
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 90
url: /net/aspose.html.dom.svg/svgdocument/save/
---
## SVGDocument.Save method (1 of 9)

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

### See Also

* class [Url](../../../aspose.html/url)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (2 of 9)

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

### See Also

* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (3 of 9)

Saves the document content and resources to the output storage.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStorage | IOutputStorage | The output storage [`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |

### See Also

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (4 of 9)

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

### See Also

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (5 of 9)

Saves the document content and resources to the output storage.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStorage | IOutputStorage | The output storage [`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveFormat | SVGSaveFormat | Format in which document is saved. |

### See Also

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (6 of 9)

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Local path to output file. |
| saveOptions | SVGSaveOptions | SVG save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `path` is not a valid local file path. |

### See Also

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (7 of 9)

Saves the document content and resources to the output storage.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStorage | IOutputStorage | The output storage [`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | SVGSaveOptions | SVG save options. |

### See Also

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (8 of 9)

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
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

### See Also

* class [Url](../../../aspose.html/url)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

---

## SVGDocument.Save method (9 of 9)

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Local URL to output file. |
| saveOptions | SVGSaveOptions | SVG save options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Raised if the specified `url` is not a valid local file URL. |

### See Also

* class [Url](../../../aspose.html/url)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* namespace [Aspose.Html.Dom.Svg](../../svgdocument)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
