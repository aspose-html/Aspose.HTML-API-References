---
title: Save
second_title: Aspose.HTML for .NET API 参考
description: 将文档保存到由 url 指定的本地文件本文档中使用的所有资源将保存在 到相邻文件夹其名称将构造为output_file_name  _files
type: docs
weight: 90
url: /zh/net/aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../../aspose.html/url)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string) {#save_6}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |
| saveFormat | SVGSaveFormat | 保存文档的格式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |
| saveFormat | SVGSaveFormat | 保存文档的格式。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveFormat | SVGSaveFormat | 保存文档的格式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../../aspose.html/url)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../../aspose.html/url)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgdocument)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
