---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLDocument 方法。将文档保存到由 url 指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为 output_file_name_files。"
type: docs

url: /zh/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

将文档保存到由 url 指定的本地文件。此文档使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为 output_file_name + "_files"。

```java
public void Save(Url url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 本地 [`URL`](../../url/) 到输出文件。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(Url) 方法

需要指定完整的 Url 路径——'outputFilePath'，用于 HTML 文档保存。`Url(url)` 构造函数使用指定的 url 创建一个 [`Url`](../../url/) 类的实例。然后应将该实例传递给 Save(Url) 方法。文档将保存到由 url 指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为 output_file_name + \"_files\"。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
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
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

将文档保存到由路径指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + \"_files\"。

```java
public void Save(String path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 本地文件系统路径到输出文件。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(String) 方法接受本地文件系统路径作为参数，用于指定输出文件，并将 HTML 文档保存到该路径指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### 另请参阅

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

将文档保存到由路径指定的本地文件。此文档使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为 output_file_name + "_files"。

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 本地文件路径到输出文件。 |
| saveFormat | HTMLSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(String, HTMLSaveFormat) 方法

Save(String, HTMLSaveFormat) 方法接受本地文件系统路径（输出文件）和 saveFormat 作为参数。[`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) 枚举指定文档保存的格式，可为 HTML、MHTML 和 MD 格式。该方法将 HTML 文档以指定格式保存到路径指定的本地文件中。文档中使用的所有资源将保存到相邻的文件夹中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary=\"boundary\";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang=\"en\" xmlns:xml=\"http://www.w3.org/XML/1998/package\"&gt;&lt;head&gt;

&lt;meta charset=\"UTF-8\"&gt;

&lt;link rel=\"stylesheet\" href=\"main.css\"&gt;

&lt;title&gt;标题&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id=\"uniqueIdentifier\"&gt;带有 ID 的容器 - 标识符&lt;/div&gt;

&lt;div class=\"custom-class\"&gt;通过 css 类自定义的容器&lt;/div&gt;

&lt;div&gt;

&lt;p class=\"pStyle\"&gt;第一段，由 pStyle 类样式化&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;第二段，由 pStyle 类样式化&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;第三段，由 pStyle 类样式化&lt;/p&gt;

&lt;span class=\"pStyle\"&gt;由 pStyle 样式化的 span&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns=\"http://www.w3.org/1998/Math/MathML\"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id=\"smart class\"&gt;

&lt;p id="p1" class="ddd kkk"&gt;使用类名 =ddd kkk= 样式的段落&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;使用类名 =ddd fff= 样式的段落&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;使用类名 =kkk fff= 样式的段落&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;来自 DIV 元素的问候&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

内容类型: text/css;

内容位置: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### 另请参阅

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

将文档保存到由 url 指定的本地文件。此文档使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为 output_file_name + "_files"。

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveFormat | HTMLSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(Url, HTMLSaveFormat) 方法

需要为 HTML 文档保存指定完整的 Url 路径 - 'outputFilePath'。Url(url) 构造函数会创建一个具有指定 url 的 [`Url`](../../url/) 类实例。[`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) 枚举指定文档保存的格式，可为 HTML、MHTML 和 MD 格式。然后应将参数传递给 Save(url, saveFormat) 方法。文档将以指定格式保存到由 url 指定的本地文件中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### 另请参阅

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveFormat | HTMLSaveFormat | 文档保存的格式。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

将文档保存到由路径指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + \"_files\"。

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 输出文件的本地路径。 |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 对象用于资源处理过程管理。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(String, HTMLSaveOptions) 方法

Save(String, HTMLSaveOptions) 方法接受以下参数：输出文件的本地文件系统路径、[HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) 类的实例，并将带资源的 HTML 文档保存到由路径指定的本地文件。HTMLSaveOptions() 构造函数会创建一个具有 [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 属性的保存选项实例，这些属性用于配置资源处理。文档中使用的所有资源都将保存到相邻的文件夹中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// 定义选项类实例
	var options = new HTMLSaveOptions();
	// 页面处理限制
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

将文档保存到由 url 指定的本地文件。此文档使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 本地 [`URL`](../../url/) 到输出文件。 |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 对象用于资源处理过程管理。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(Url, HTMLSaveOptions) 方法

需要为 HTML 文档保存指定完整的 Url 路径。Url(url) 构造函数会创建一个具有指定 url 的 [`Url`](../../url/) 类实例。HTMLSaveOptions() 构造函数会创建一个具有 ResourceHandlingOptions 属性的 [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 类实例，这些属性用于配置资源处理。Save(url, saveOptions) 方法接受参数并将带资源的 HTML 文档保存到由 url 指定的本地文件中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// 定义选项类实例
	var options = new HTMLSaveOptions();
	// 页面处理限制
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | HTMLSaveOptions | HTML 保存选项。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

将文档保存到由路径指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + \"_files\"。

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 输出文件的本地路径。 |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。更多信息请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(String, MarkdownSaveOptions) 方法

需要为文档保存指定输出文件的本地文件系统路径。MarkdownSaveOptions() 构造函数会创建一个具有一组属性的 [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 类实例。例如，您可以设置 markdown 格式样式，使用预定义的兼容 GitLab Flavored Markdown 的选项，并配置资源处理。Save(path, saveOptions) 方法接受输出文件的本地文件系统路径和选项实例作为参数，并将 HTML 作为 Markdown 文档连同资源保存到由路径指定的本地文件中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// 定义选项类实例
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

将文档保存到由 url 指定的本地文件。此文档使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 本地 [`URL`](../../url/) 到输出文件。 |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。更多信息请参阅 [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(Url, MarkdownSaveOptions) 方法

需要为文档保存指定完整的 Url 路径。Url(url) 构造函数会创建一个具有指定 url 的 [`Url`](../../url/) 类实例。MarkdownSaveOptions() 构造函数会创建一个具有一组属性的 [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 类实例。例如，您可以设置 Markdown 格式样式，使用预定义的兼容 GitLab Flavored Markdown 的选项，并配置资源处理。Save(url, saveOptions) 方法接受 url 和保存选项实例作为参数，并将带资源的文档保存到由 url 指定的本地文件中。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// 定义选项类实例
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | MarkdownSaveOptions | Markdown 保存选项。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

将文档保存到由路径指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + \"_files\"。

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 输出文件的本地路径。 |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调节渲染过程。更多信息请参阅 [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(String, MHTMLSaveOptions) 方法

需要指定本地文件系统路径作为文档保存的输出文件。MHTMLSaveOptions() 构造函数会初始化一个 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 类的实例，该实例具有用于资源处理配置的 ResourceHandlingOptions 属性。Save(path, saveOptions) 方法接受本地文件系统路径和保存选项实例作为参数，并将 HTML 保存为 MHTML 文档到路径指定的本地文件。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// 定义选项类实例
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

将文档保存到由 url 指定的本地文件。此文档使用的所有资源将保存到相邻的文件夹中，文件夹名称将构建为：output_file_name + "_files"。

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 输出文件的本地 URL。 |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调节渲染过程。更多信息请参阅 [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

## 备注

保存 HTML

大多数需要执行的任务都需要保存文档。加载现有文件或从头创建 HTML 文档后，您可以使用 HTMLDocument.Save() 方法之一保存更改。这些方法允许将 HTML 保存到由路径、URL 或输出存储指定的本地文件。请参阅[文档](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)了解更多关于保存的信息。

Save(Url, MHTMLSaveOptions) 方法

需要指定完整的 Url 路径来保存文档。Url(url) 构造函数会使用指定的 url 创建一个 [`Url`](../../url/) 类的实例。MHTMLSaveOptions() 构造函数会初始化一个 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 类的实例，该实例具有用于资源处理配置的 ResourceHandlingOptions 属性。Save(url, saveOptions) 方法接受 url 和选项作为参数，并将 HTML 保存为 MHTML 文档到 url 指定的本地文件。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// 定义选项类实例
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### 另请参阅

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

使用 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存选项。 |

### 另请参阅

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
