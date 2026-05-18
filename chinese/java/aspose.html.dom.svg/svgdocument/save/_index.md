---
title: "SVGDocument.Save"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGDocument 方法。将文档保存到由 url 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为 output_file_name _files"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

将文档保存到 `url` 指定的本地文件。此文档使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(Url url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

将文档保存到 `path` 指定的本地文件。此文档使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(String path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 输出文件的本地路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

将文档保存到 `path` 指定的本地文件。此文档使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 输出文件的本地路径。 |
| saveFormat | SVGSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveFormat | SVGSaveFormat | 文档保存的格式。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

将文档保存到 `path` 指定的本地文件。此文档使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 输出文件的本地路径。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

将文档保存到 `url` 指定的本地文件。此文档使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveFormat | SVGSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

将文档保存到 `url` 指定的本地文件。此文档使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
