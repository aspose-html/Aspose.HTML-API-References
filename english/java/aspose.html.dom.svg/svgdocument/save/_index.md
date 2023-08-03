---
title: SVGDocument.Save
second_title: Aspose.HTML for Java API Reference
description: SVGDocument method. Saves the document to local file specified by url. All resources used in this document will be saved in to adjacent folder whose name will be constructed as output_file_name  _files
type: docs
weight: 90
url: /net/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```java
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

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```java
public void Save(String path)
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
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

Saves the document content and resources to the output storage.

```java
public void Save(IOutputStorage outputStorage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStorage | IOutputStorage | The output storage [`IOutputStorage`](../../../com.aspose.html.io/ioutputstorage/). |

### See Also

* interface [IOutputStorage](../../../com.aspose.html.io/ioutputstorage/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```java
public void Save(String path, SVGSaveFormat saveFormat)
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

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

Saves the document content and resources to the output storage.

```java
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStorage | IOutputStorage | The output storage [`IOutputStorage`](../../../com.aspose.html.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | Format in which document is saved. |

### See Also

* interface [IOutputStorage](../../../com.aspose.html.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```java
public void Save(String path, SVGSaveOptions saveOptions)
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

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

Saves the document content and resources to the output storage.

```java
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStorage | IOutputStorage | The output storage [`IOutputStorage`](../../../com.aspose.html.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | SVG save options. |

### See Also

* interface [IOutputStorage](../../../com.aspose.html.io/ioutputstorage/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```java
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

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files".

```java
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

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.Dom.Svg](../../svgdocument/)
* package [Aspose.HTML](../../../)
