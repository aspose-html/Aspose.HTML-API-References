---
title: "Converter.ConvertHTML"
second_title: "Aspose.HTML for Java API 参考"
description: "Converter 方法。将由 HTMLDocument 提供的 HTML 源转换。结果是由输出文件路径生成的 docx 文件"
type: docs

url: /zh/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 实例作为转换来源。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // 实例化默认配置对象
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// 定义输出文件路径
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// 定义默认 DocSaveOptions 对象
        var options = new DocSaveOptions();
         
		// 使用默认配置对象启动转换过程
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 基于输入文件路径创建 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置对象启动转换过程
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

将通过完整文件路径提供的 HTML 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

将通过完整文件路径提供的 HTML 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 表单源文件路径
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // 表单结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // 定义默认 DocSaveOptions 对象
   var options = new DocSaveOptions();

   // 使用默认配置启动转换过程
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

将通过内联内容提供的 HTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// 定义默认 DocSaveOptions 对象
   	var options = new DocSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

将通过内联内容提供的 HTML 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// 定义默认 DocSaveOptions 对象
   	var options = new DocSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// 定义内联 html 内容
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// 实例化默认配置对象
      	var configuration = new Configuration();

      	// 通过多种方式之一创建 HTML 文档
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// 定义不带扩展名的结果文件路径
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// 使用 ICreateStreamProvider 的一种实现
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// 定义默认 DocSaveOptions 对象
			var options = new DocSaveOptions();

        	// 启动转换过程
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // 表单源 URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 定义不带扩展名的结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用已知的 ICreateStreamProvider 实现
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // 表单源 URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // 定义不带扩展名的结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result");

   // 使用已知的 ICreateStreamProvider 实现
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // 定义默认 DocSaveOptions 对象
   var options = new DocSaveOptions();

   // 使用默认配置启动转换过程
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

将由完整文件路径提供的 HTML 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单源 html 文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 定义结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用默认的 ICreateStreamProvider 实现
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

将由完整文件路径提供的 HTML 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 表单源 html 文件路径
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // 定义结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result");

   // 使用默认的 ICreateStreamProvider 实现
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // 定义默认 DocSaveOptions 对象
   var options = new DocSaveOptions();

   // 使用默认配置对象启动转换过程
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

将由内联内容提供的 HTML 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // 表单 html 内联内容
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // 定义结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用已知的本地文件导向 ICreateStreamProvider 实现
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // 实例化默认的 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

将由内联内容提供的 HTML 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

DOCX 转换

DOCX 文件是 Microsoft Word 文档，通常包含文本，但也可以包含各种数据，包括表格、光栅和矢量图形、视频、音频和图表。DOCX 文件高度可编辑、易于使用且大小易于管理。由于它提供了多种选项让用户编写任何类型的文档，这种格式非常受欢迎。该文件格式是最广泛使用的之一，并可通过众多程序获得。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 DOCX 结果，参数可根据用户场景使用三或更多个。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx)，可将 HTML 高质量、快速且轻松地转换为 DOCX。只需上传、转换您的文件，即可在几秒钟内获取结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // 表单 html 内联内容
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // 定义结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result");

   // 使用已知的本地文件导向 ICreateStreamProvider 实现
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // 实例化默认的 DocSaveOptions 对象
   var options = new DocSaveOptions();

   // 使用默认配置启动转换过程
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由输出文件路径形成的 pdf 文件。

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // 表单源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 实例化默认配置对象
      var configuration = new Configuration();

      // 通过多种方式之一创建 html 文档
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// 表单结果文件路径
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // 定义默认的 PdfSaveOptions 对象
        var options = new PdfSaveOptions();

		// 实例化转换过程
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // 形成基于文件的来源 Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // 形成基于文件的来源 Url
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // 表单结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // 定义默认的 PdfSaveOptions 对象
   var options = new PdfSaveOptions();

   // 使用默认配置对象启动转换过程
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

将通过完整文件路径提供的 HTML 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 表单源文件路径
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // 表单结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // 定义默认的 PdfSaveOptions 对象
   var options = new PdfSaveOptions();

   // 启动转换过程
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

将通过完整文件路径提供的 HTML 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // 表单源文件路径
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // 表单结果文件路径
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // 定义默认的 PdfSaveOptions 对象
  var options = new PdfSaveOptions();

  // 使用默认配置启动转换过程
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

将通过内联内容提供的 HTML 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// 定义默认的 PdfSaveOptions 对象
   	var options = new PdfSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

将通过内联内容提供的 HTML 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// 定义默认的 PdfSaveOptions 对象
  	var options = new PdfSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 定义内联 html 内容
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// 实例化默认配置对象
   	var configuration = new Configuration();

   	// 通过多种方式之一创建 HTML 文档
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// 定义不带扩展名的结果文件路径
		var resultPath = Path.Combine(OutputFolder, "result");

		// 使用 ICreateStreamProvider 的一种实现
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// 定义默认的 PdfSaveOptions 对象
		var options = new PdfSaveOptions();

		// 启动转换过程
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 基于输入文件路径创建 Url
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // 表单结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result");

   // 使用 ICreateStreamProvider 的一种实现
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // 定义默认的 PdfSaveOptions 对象
   var options = new PdfSaveOptions();

   // 启动转换过程
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 基于输入文件路径创建 Url
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // 表单结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result ");

   // 使用 ICreateStreamProvider 的一种实现
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // 定义默认的 PdfSaveOptions 对象
   var options = new PdfSaveOptions();

   // 使用默认配置启动转换过程
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

将通过完整文件路径提供的 HTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 创建源文件路径
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // 表单结果文件路径
   var resultPath = Path.Combine(OutputFolder, "result");

   // 使用 ICreateStreamProvider 的一种实现
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // 定义默认的 PdfSaveOptions 对象
   var options = new PdfSaveOptions();

   // 启动转换过程
   Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

将通过完整文件路径提供的 HTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // 创建源文件路径
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // 表单结果文件路径
  var resultPath = Path.Combine(OutputFolder, "result");

  // 使用 ICreateStreamProvider 的一种实现
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // 定义默认的 PdfSaveOptions 对象
  var options = new PdfSaveOptions();

  // 使用默认配置启动转换过程
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

将通过内联内容提供的 HTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 使用 ICreateStreamProvider 的一种实现
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 定义默认的 PdfSaveOptions 对象
  	var options = new PdfSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

将通过内联内容提供的 HTML 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调优渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

PDF 转换

Portable Document Format (PDF) 是一种在 1990 年代由 Adobe 创建的文档类型。该文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考资料。PDF 文件是一组字节，可根据 PDF 规范定义的语法规则分组成标记（tokens）。一个或多个标记组合形成更高级的语法实体，主要是对象，这些对象是构建 PDF 文档的基本数据值。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

其他流行的格式转换

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 PDF 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf)，可高质量、简便且快速地将 HTML 转换为 PDF。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 使用 ICreateStreamProvider 的一种实现
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 定义默认的 PdfSaveOptions 对象
 	var options = new PdfSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由输出文件路径形成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 形成 HTML 文档
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// 通过多种方式之一创建 HTML 文档
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// 定义默认的 MHTMLSaveOptions 对象
 		var options = new MHTMLSaveOptions();

		// 表单结果文件路径
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// 启动转换过程
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// 定义默认的 MHTMLSaveOptions 对象
	var options = new MHTMLSaveOptions();

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// 启动转换过程
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// 定义默认的 MHTMLSaveOptions 对象
	var options = new MHTMLSaveOptions();

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

将通过完整文件路径提供的 HTML 源转换为 MHTML。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// 定义默认的 MHTMLSaveOptions 对象
	var options = new MHTMLSaveOptions();

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// 启动转换过程
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

将通过完整文件路径提供的 HTML 源转换为 MHTML。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// 定义默认的 MHTMLSaveOptions 对象
	var options = new MHTMLSaveOptions();

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

将通过内联内容提供的 HTML 源转换为 MHTML。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或以任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，参数可为三项或更多，取决于用户场景。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 定义默认的保存选项对象
  	var options = new MHTMLSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

将通过内联内容提供的 HTML 源转换为 MHTML。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象的使用使您能够调优渲染过程。更多信息请参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions)。 |
| outputPath | String | 完整的 mhtml（.mht）文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

MHTML 转换

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有自定义或默认设置的新的 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 MHTML 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml)，可高质量、简便且快速地将 HTML 转换为 MHTML。只需上传，转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 定义默认的保存选项对象
 	var options = new MHTMLSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由输出文件路径生成的 markdown（.md）文件。

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// 表单源文件路径
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// 表单结果文件路径
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// 定义保存选项对象实例
			var options = new MarkdownSaveOptions();

			// 启动转换过程
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 markdown（.md）文件。

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// 表单结果文件路径
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 定义保存选项对象实例
	var options = new MarkdownSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 markdown（.md）文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// 表单结果文件路径
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 定义保存选项对象实例
	var options = new MarkdownSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

将通过完整文件路径提供的 HTML 源转换为 Markdown。结果是由输出文件路径生成的 markdown（.md）文件。

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// 表单结果文件路径
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 定义保存选项对象实例
	var options = new MarkdownSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

将通过完整文件路径提供的 HTML 源转换为 Markdown。结果是由输出文件路径生成的 markdown（.md）文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// 表单结果文件路径
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 定义保存选项对象实例
	var options = new MarkdownSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

将通过内联内容提供的 HTML 源转换为 Markdown。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 定义默认的保存选项对象
  	var options = new MarkdownSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

将通过内联内容提供的 HTML 源转换为 Markdown。结果是由输出文件路径生成的 mhtml（.mht）文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions)。 |
| outputPath | String | 完整的 md 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

Markdown 转换

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

其他流行的格式转换

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 Markdown 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) 服务，可将 HTML 高质量、简便、快速地转换为 MD。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 定义默认的保存选项对象
 	var options = new MarkdownSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// 表单源文件路径
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// 表单结果文件路径
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// 通过多种方式之一创建 HTML 文档
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// 定义保存选项对象实例
        	var options = new XpsSaveOptions();

        	// 启动转换过程
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// 表单结果文件路径
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// 表单结果文件路径
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

将通过完整文件路径提供的 HTML 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// 表单结果文件路径
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

将通过完整文件路径提供的 HTML 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// 表单结果文件路径
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

将通过内联内容提供的 HTML 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 定义默认的保存选项对象
  	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

将通过内联内容提供的 HTML 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 定义默认的保存选项对象
 	var options = new XpsSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// 表单结果文件路径
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// 通过多种方式之一创建 HTML 文档
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// 定义保存选项对象实例
    	var options = new XpsSaveOptions();

		// 使用已知的 ICreateStreamProvider 实现之一
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// 启动转换过程
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源文档 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// 表单结果文件路径
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 使用 ICreateStreamProvider 的一种实现
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// 表单结果文件路径
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 使用 ICreateStreamProvider 的一种实现
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

将通过完整文件路径提供的 HTML 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现生成的输出数据。

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// 表单结果文件路径
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 使用 ICreateStreamProvider 的一种实现
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

将通过完整文件路径提供的 HTML 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现生成的输出数据。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// 表单结果文件路径
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 使用 ICreateStreamProvider 的一种实现
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 定义保存选项对象实例
	var options = new XpsSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

将以内联内容呈现的 HTML 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps) 转换器，可高质量、轻松且快速地将 HTML 转换为 XPS。只需上传、转换文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 使用 ICreateStreamProvider 的一种实现
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 定义默认的保存选项对象
  	var options = new XpsSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

将以内联内容呈现的 HTML 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为 XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

XPS 转换

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

将 HTML 转换为 XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 HTML 文件或远程 Url 作为转换来源。您甚至可以将内联 html 内容定义为转换来源，或通过任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个新的 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象，使用自定义或默认设置。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertHTML() 方法将 HTML 保存为 XPS 结果，根据用户场景可使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) 服务，可将 HTML 高质量、简便、快速地转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

尝试使用其他流行的格式转换

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

您可能也对特定的图像格式转换感兴趣

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 使用 ICreateStreamProvider 的一种实现
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 定义默认的保存选项对象
 	var options = new XpsSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 呈现的 HTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "source.html");

// 表单结果文件路径
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 启动转换过程
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// 表单结果文件路径
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 启动转换过程
	Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

将通过 URL 提供的 HTML 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// 表单结果文件路径
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

将通过完整文件路径提供的 HTML 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| options | ImageSaveOptions | 欲了解更多关于 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 类的信息，请阅读 [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/) 文章。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// 表单结果文件路径
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// 定义保存选项对象实例。默认情况下，PNG 为图像格式。
	var options = new ImageSaveOptions();

	// 启动转换过程
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

将通过完整文件路径提供的 HTML 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 欲了解更多关于 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 类的信息，请阅读 [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/) 文章。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// 表单结果文件路径
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// 定义保存选项对象实例。默认情况下，PNG 为图像格式。
	var options = new ImageSaveOptions();

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

将通过内联内容提供的 HTML 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | ImageSaveOptions | 新生成的图像选项包括格式、分辨率等。请参阅 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 类和 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// 定义默认的保存选项对象
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

将通过内联内容提供的 HTML 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 新生成的图像选项包括格式、分辨率等。请参阅 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 类和 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// 定义默认的保存选项对象
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

将由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | HTMLDocument | 由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的转换源。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result");

	// 通过多种方式之一创建 HTML 文档
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// 定义保存选项对象实例
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// 使用 ICreateStreamProvider 的一种实现
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// 启动转换过程
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源 URL - 提供通用标识符 (URL) 的对象表示。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// 表单结果文件路径
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用 ICreateStreamProvider 的一种实现
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 启动转换过程
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

将由 URL 提供的 HTML 源转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | HTML 源 URL - 提供通用标识符 (URL) 的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 该接口的实现将用于获取输出流。有关提供程序的更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 基于输入文件路径创建 Url
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// 表单结果文件路径
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用 ICreateStreamProvider 的一种实现
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

将通过完整文件路径呈现的 HTML 源转换为图像。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | Html 完整文件源路径。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 该接口的实现将用于获取输出流。有关提供程序的更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// 表单结果文件路径
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用已知的 ICreateStreamProvider 实现之一
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 启动转换过程
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

将通过完整文件路径呈现的 HTML 源转换为图像。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 该接口的实现将用于获取输出流。有关提供程序的更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单源文件路径
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// 表单结果文件路径
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 定义保存选项对象实例
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用已知的 ICreateStreamProvider 实现之一
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

将以内联内容呈现的 HTML 源转换为图像。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// 定义默认的保存选项对象
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用已知的 ICreateStreamProvider 实现之一
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 启动转换过程
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

将以内联内容呈现的 HTML 源转换为图像。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 html 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration `](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 实现 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，将用于获取输出流。有关提供程序的更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)。 |

## 备注

如何将 HTML 转换为图像

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML 的主要亮点是转换功能。出于各种原因需要在格式之间进行转换：为了使用熟悉、便捷的格式，或利用不同格式完成特定任务。com.aspose.html.converters 包实现了对转换方法的简易访问。它提供了广泛的 HTML 转换到流行格式，如 [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), 和 [MD](https://docs.fileformat.com/word-processing/md/)。

本文提供了受支持的 HTML 转换列表及使用 [`Converter`](../) 类执行这些转换的信息。该类将所有低层次的转换操作集中在一个类中，使其使用舒适且简便。在 HTML Converter 指南中，您会找到以下文章：

图像转换

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

其他流行的格式转换

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

将 HTML 转换为图像

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

转换来源。检测本地已有的 HTML 文件或远程 URL 作为转换来源。您甚至可以将内联 HTML 内容定义为转换来源，或以任何方式创建 HTML 文档（HTMLDocument）。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。使用 Converter 类的 ConvertHTML() 方法，将 HTML 保存为图像，可根据用户场景使用三个或更多参数。在线 HTML 转换器

Aspose.HTML 提供免费的在线 [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) ，可高质量、轻松且快速地将 HTML 转换为图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定的图像格式转换感兴趣

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 表单内联 html 内容		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// 表单结果文件路径
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// 定义默认的保存选项对象
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 使用已知的 ICreateStreamProvider 实现之一
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 使用默认配置启动转换过程
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | HTMLDocument | 转换来源。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 文档 URL。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 文档 URL。 |
| 配置 | 配置 | 环境配置。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | HTML 文件源路径。它将与当前目录路径组合形成绝对 URL。 |
| 配置 | 配置 | 环境配置。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 内联字符串 HTML 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

将 html 文档转换为文本。结果是 TXT 文件。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 内联字符串 HTML 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| 配置 | 配置 | 环境配置。 |
| options | TextSaveOptions | 转换选项。 |
| outputPath | String | 输出文件路径。 |

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
