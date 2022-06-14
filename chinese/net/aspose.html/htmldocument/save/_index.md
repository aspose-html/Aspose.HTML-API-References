---
title: Save
second_title: Aspose.HTML for .NET API 参考
description: 将文档保存到由 url 指定的本地文件本文档中使用的所有资源将保存在 到相邻文件夹其名称将构造为output_file_name  _files
type: docs
weight: 130
url: /zh/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

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

* class [Url](../../url)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
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
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

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

* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |
| saveFormat | HTMLSaveFormat | 保存文档的格式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveFormat | HTMLSaveFormat | 保存文档的格式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../url)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |
| saveFormat | HTMLSaveFormat | 保存文档的格式。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |
| saveOptions | HTMLSaveOptions | HTML 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveOptions | HTMLSaveOptions | HTML 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../url)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |
| saveOptions | HTMLSaveOptions | HTML 保存选项。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |
| saveOptions | MarkdownSaveOptions | Markdown 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveOptions | MarkdownSaveOptions | Markdown 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../url)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |
| saveOptions | MarkdownSaveOptions | Markdown 保存选项。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

将文档保存到由` 路径` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出文件的本地路径。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` 路径` 不是有效的本地文件路径，则引发. |

### 也可以看看

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

将文档保存到由` url` 指定的本地文件。本文档中使用的所有资源将保存在 到相邻文件夹，其名称将构造为:output_file_name + "_files"。

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定的` url` 不是有效的本地文件 URL，则引发. |

### 也可以看看

* class [Url](../../url)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

将文档内容和资源保存到输出存储。

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 输出存储[`IOutputStorage`](../../../aspose.html.io/ioutputstorage)。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存选项。 |

### 也可以看看

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* 命名空间 [Aspose.Html](../../htmldocument)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
