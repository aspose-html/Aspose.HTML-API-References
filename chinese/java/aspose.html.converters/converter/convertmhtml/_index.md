---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML for Java API 参考"
description: "Converter 方法。将通过输入流呈现的 MHTML 源转换。结果是由输出文件路径生成的 XPS 文件"
type: docs

url: /zh/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

将通过输入 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供的 MHTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入 mhtml（.mht）数据流。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

将通过完整文件路径提供的 MHTML 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 定义默认的 XpsSaveOptions 对象
	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 定义默认的 XpsSaveOptions 对象
	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

将通过输入 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 提供的 MHTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 转换源 mhtml（.mht）数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

将通过完整文件路径提供的 MHTML 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 转换源 mhtml（.mht）数据流。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

将通过完整文件路径提供的 MHTML 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

将通过 [`URL`](../../../com.aspose.html/url/) 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io; 
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 转换源 mhtml（.mht）数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

将通过完整文件路径提供的 MHTML 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

将通过 URL 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 使用[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象可以调节渲染过程。欲了解更多信息，请参阅[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

MHTML 转换为 [XPS](https://docs.fileformat.com/page-description-language/xps/) 通常是为了在特定任务中利用 XPS 格式的优势。XPS 文件是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。

请参阅[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertHTML() 方法将 MHTML 转换为 XPS 的信息，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为 XPS

Converter 类提供少量针对 MHTML 的 XPS 转换。要将 MHTML 转换为 XPS，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 MHTML（.mht）文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的特定流作为转换来源。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用特定或默认设置。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 MHTML 转换器

Aspose.HTML 提供免费的在线[MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)，可高质量、简便且快速地将 MHTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

将通过输入流提供的 MHTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

将通过完整文件路径提供的 MHTML 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

将通过输入流提供的 MHTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

将通过完整文件路径提供的 MHTML 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

将通过 [`URL`](../../../com.aspose.html/url/) 提供的 MHTML 源进行转换。结果是由输出文件路径形成的 docx 文件。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

将通过完整文件路径提供的 MHTML 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

将通过 URL 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

将通过完整文件路径提供的 MHTML 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

将通过 [`URL`](../../../com.aspose.html/url/) 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 DOCX 通常是为了在特定任务中利用 [DOCX](https://docs.fileformat.com/word-processing/docx/) 格式的优势。DOCX 是 Microsoft Word 文档的知名格式。它可以包含各种数据，包括文本、表格、光栅和矢量图形、视频、音频和图表。该格式之所以受欢迎，是因为它支持复杂的格式化功能，并为用户提供了编写任何类型文档的多种选项。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 DOCX，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 DOCX

Converter 类提供了一些针对 MHTML 转换为 DOCX 的特定转换。要将 MHTML 转换为 DOCX，您应遵循以下几个步骤的简单场景之一：

转换源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换源。您也可以使用标准或自定义的特定流作为转换源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 DOCX 结果，参数为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)，可高质量、快速、简便地将 MHTML 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

将通过输入流提供的 MHTML 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

将通过完整文件路径提供的 MHTML 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

将通过输入流提供的 MHTML 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

将通过完整文件路径提供的 MHTML 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

将完整文件路径呈现的 MHTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

将通过 URL 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

将完整文件路径呈现的 MHTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

将通过 [`URL`](../../../com.aspose.html/url/) 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。有关更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

MHTML 转换为 PDF 通常是为了在特定任务中利用 [PDF](https://docs.fileformat.com/pdf/) 格式的优势。PDF 具有许多其他文件所不具备的好处。例如，许多程序和应用程序支持 PDF 文档；PDF 文件针对打印进行了优化，且非常适合创建文档的纸质副本；您还可以配置 PDF 文件的安全设置——禁用打印、编辑、使用电子签名等。

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)，其中您可以找到有关如何使用 [`Converter`](../) 类的 ConvertMHTML() 方法将 MHTML 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 MHTML 转换为 PDF

Converter 类提供少量针对 MHTML 的 PDF 转换。要将 MHTML 转换为 PDF，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 Url 作为转换来源。您也可以使用标准或自定义的 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用特定或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)，可高质量、轻松且快速地将 MHTML 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

将通过输入流提供的 MHTML 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

将通过完整文件路径提供的 MHTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

将通过输入流提供的 MHTML 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

将通过完整文件路径提供的 MHTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

将通过 URL 提供的 MHTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

将完整文件路径呈现的 MHTML 源转换为图像。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

将通过 URL 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

将通过输入流提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MHTML 转换输入数据流。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 启动转换过程
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

将完整文件路径呈现的 MHTML 源转换为图像。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MHTML 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | 实现 [` interface`](../../../com.aspose.html.io/icreatestreamprovider/)，该实现将用于获取输出流。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

将通过 URL 提供的 MHTML 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 源文档 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

MHTML 转换器

带有 [MHTML](https://docs.fileformat.com/web/mhtml/) 扩展名的文件表示一种网页存档格式，许多不同的应用程序都可以创建。该格式被称为存档格式，因为它将网页的 HTML 代码及相关资源保存到单个文件中。这些资源包括网页链接的所有内容，如图像、applet、动画、音频文件等。MHTML 文件可以在多种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。该格式的实际规范详见 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)。

请参阅文章，您将在其中找到使用 Converter 类的 ConvertMHTML() 方法将 MHTML 转换为不同格式图像的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。

将 MHTML 转换为图像

Converter 类提供少量针对 MHTML 的图像转换。支持的格式有 [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) 和 [TIFF](https://docs.fileformat.com/image/tiff/)。要将 MHTML 转换为图像，您应遵循一个由几步组成的简单场景：

转换来源。检测本地已有的 MHTML（.mht）文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以使用标准或自定义的流作为来源。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象，使用特定或默认设置。默认图像格式为 PNG。您还可以将 configuration 作为选项参数添加。使用 Converter 类的 ConvertMHTML() 方法将 MHTML 保存为图像结果，参数可为三项或更多，取决于用户场景。在线 MHTML 转换器

Aspose.HTML 提供免费的在线 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)，可高质量、轻松且快速地将 MHTML 转换为 JPEG 文件。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
