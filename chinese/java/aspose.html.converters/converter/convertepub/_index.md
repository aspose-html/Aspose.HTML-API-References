---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML for Java API 参考"
description: "Converter 方法。将通过数据输入流呈现的 EPUB 源转换。结果是由输出文件路径形成的文件。"
type: docs

url: /zh/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

将通过数据输入流提供的 EPUB 源转换。结果是由输出文件路径生成的文件。

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| options | ImageSaveOptions | 新生成的图像选项包括格式、分辨率等。请参阅 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 类和 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options)。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

根据指定路径的现有 EPUB 文件定义 Url。定义结果输出文件路径。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您还需要将 ImageSaveOptions 和 Configuration 对象传递给图像转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 以流方式打开现有文件进行读取
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// 定义输出文件路径
var resultPath = Path.Combine(OutputFolder, "sample.png");

// 定义默认选项实例
var options = new ImageSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

将通过完整文件路径提供的 EPUB 源转换。结果是由输出文件路径生成的图像文件。图像格式由 ImageSaveOptions 对象指定。

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径作为输入参数。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

根据指定路径的现有 EPUB 文件定义 Url。定义结果输出文件路径。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您还需要将 ImageSaveOptions 和 Configuration 对象传递给图像转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// 定义默认的 ImageSaveOptions 对象实例
var options = new ImageSaveOptions(); 

// 启动转换过程
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

将由 URL 定义的 EPUB 源转换。结果是由输出文件路径生成的图像文件。图像格式由 ImageSaveOptions 对象指定。

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够调优渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 类。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

根据指定路径的现有 EPUB 文件定义 Url。定义结果输出文件路径。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您还需要将 ImageSaveOptions 和 Configuration 对象传递给图像转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 基于输入文件路径创建 Url
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.png");

// 定义默认选项实例
var options = new ImageSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

将通过数据输入流提供的 EPUB 源转换。结果是由输出文件路径生成的图像文件。图像格式由 ImageSaveOptions 对象指定。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

根据指定路径的现有 EPUB 文件定义 Url。定义结果输出文件路径。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您还需要将 ImageSaveOptions 和 Configuration 对象传递给图像转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 以流方式打开现有文件进行读取
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// 定义输出文件路径
var resultPath = Path.Combine(OutputFolder, "sample.png");

// 定义默认选项实例
var options = new ImageSaveOptions();

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

将通过完整文件路径提供的 EPUB 源转换。结果是由输出文件路径生成的图像文件。图像格式由 ImageSaveOptions 对象指定。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径作为输入参数。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够调优渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 类。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

根据指定路径的现有 EPUB 文件定义 Url。定义结果输出文件路径。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您还需要将 ImageSaveOptions 和 Configuration 对象传递给图像转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// 定义默认的 ImageSaveOptions 对象实例
var options = new ImageSaveOptions(); 

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

将由 URL 定义的 EPUB 源转换。结果是由输出文件路径生成的图像文件。图像格式由 ImageSaveOptions 对象指定。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够调优渲染过程。您可以指定 [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup)、[margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin)、[CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype) 等。请参阅 [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) 类。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

根据指定路径的现有 EPUB 文件定义 Url。定义结果输出文件路径。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您还需要将 ImageSaveOptions 和 Configuration 对象传递给图像转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 基于输入文件路径创建 Url
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// 定义输出文件路径
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// 定义默认选项实例
var options = new ImageSaveOptions(); 

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

将通过输入 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供的 epub 源转换为图像。结果是由实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口形成的图像文件。

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够调优渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 类。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，将用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。在示例中，我们使用 System.IO.FileStream 类的 OpenRead() 方法在指定路径的文件系统中打开并读取 EPUB 文件。使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有所需 ImageFormat 的新 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您需要将 EPUB inputStream、ImageSaveOptions 和输出流传递给 ConvertEPUB() 方法，以实现 EPUB 到图像的转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// 创建默认选项实例  
var options = new ImageSaveOptions();    

// 启动转换过程  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

将通过文件路径提供的 EPUB 源转换为图像。结果是由实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口形成的图像文件。

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | ImageSaveOptions | 新生成的图像选项包括格式、分辨率等。请参阅 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 类和 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options)。 |
| provider | ICreateStreamProvider | 该接口的实现，将用于获取输出流。有关提供程序的更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。在示例中，我们使用 System.IO.FileStream 类的 OpenRead() 方法在指定路径的文件系统中打开并读取 EPUB 文件。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。创建一个带有所需 ImageFormat 的新 ImageSaveOptions 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您需要将 EPUB inputStream、ImageSaveOptions 和输出流传递给 ConvertEPUB() 方法，以实现 EPUB 到图像的转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

通过两行代码将 EPUB 转换为 JPG

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// 打开现有的 EPUB 文件进行读取。
import var stream = File.OpenRead(DataDir + "input.epub");

// 调用 ConvertEPUB 方法将 EPUB 代码转换为 JPG 图像      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### 另请参阅

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

将通过 URL 提供的 epub 源转换为图像。结果是由实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口生成的图像文件。

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够调优渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) 类。 |
| provider | ICreateStreamProvider | 该接口的实现，将用于获取输出流。有关提供程序的更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。在示例中，我们使用 System.IO.FileStream 类的 OpenRead() 方法在指定路径的文件系统中打开并读取 EPUB 文件。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。创建一个带有所需 ImageFormat 的新 ImageSaveOptions 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您需要将 EPUB inputStream、ImageSaveOptions 和输出流传递给 ConvertEPUB() 方法，以实现 EPUB 到图像的转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// 创建默认选项实例  
var options = new ImageSaveOptions();

// 启动转换过程  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

将通过输入 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供的 epub 源转换为图像。结果是由实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口形成的图像文件。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| 提供者 | ICreateStreamProvider | 该接口的实现，用于获取输出流。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。在示例中，我们使用 System.IO.FileStream 类的 OpenRead() 方法在指定路径的文件系统中打开并读取 EPUB 文件。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。创建一个带有所需 ImageFormat 的新 ImageSaveOptions 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您需要将 EPUB inputStream、ImageSaveOptions 和输出流传递给 ConvertEPUB() 方法，以实现 EPUB 到图像的转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// 创建默认选项实例  
var options = new ImageSaveOptions();    


// 使用默认配置启动转换过程  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

将通过文件路径提供的 epub 源转换为图像。结果是由实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口生成的图像文件。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 由文件路径定义的 EPUB 源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | 该接口的实现，用于获取输出流。请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) 中的 ICreateStreamProvider 实现示例。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。在示例中，我们使用 System.IO.FileStream 类的 OpenRead() 方法在指定路径的文件系统中打开并读取 EPUB 文件。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。创建一个带有所需 ImageFormat 的新 ImageSaveOptions 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您需要将 EPUB inputStream、ImageSaveOptions 和输出流传递给 ConvertEPUB() 方法，以实现 EPUB 到图像的转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// 定义默认的 ImageSaveOptions 对象实例
var options = new ImageSaveOptions(); 

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

将通过 URL 提供的 epub 源转换为图像。结果是由实现 [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) 接口生成的图像文件。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | ImageSaveOptions 对象的使用使您能够微调渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)，等等。 |
| provider | ICreateStreamProvider | 该接口的实现，用于获取输出流。请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) 中的 ICreateStreamProvider 实现示例。 |

## 备注

如何将 EPUB 转换为图像

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（IDPF）创建，现在被许多电子阅读器和软件应用程序支持。

将 EPUB 文件转换为 PNG 格式在需要将文件嵌入 PowerPoint 演示文稿或通过电子邮件发送时非常有用。请将它们转换为图像格式并按需使用！您可以使用额外的转换参数来获得所需的结果。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了支持的 EPUB 转换场景列表及使用 Converter 类执行这些场景的信息，Converter 类将所有底层转换操作集中在一个类中，使其舒适且易于使用。在 EPUB 转换器指南中，您会找到以下文章：

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

将 EPUB 转换为图像

要将 EPUB 转换为图像文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。在示例中，我们使用 System.IO.FileStream 类的 OpenRead() 方法在指定路径的文件系统中打开并读取 EPUB 文件。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。创建一个带有所需 ImageFormat 的新 ImageSaveOptions 对象。默认情况下，Format 属性为 PNG。使用 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为图像。您需要将 EPUB inputStream、ImageSaveOptions 和输出流传递给 ConvertEPUB() 方法，以实现 EPUB 到图像的转换。在线 EPUB 转换器

Aspose.HTML 提供免费的在线 [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) 转换器，可将 EPUB 转换为高质量、简便且快速的 PNG 图像。只需上传、转换文件，即可在几秒钟内获得结果！

您可能也对特定图像格式的转换感兴趣

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// 创建默认选项实例  
var options = new ImageSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

将通过输入流提供的 epub 源转换为 xps。结果是由完整路径定义的 xps 文件。

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 将输入流作为转换源。请参阅 [官方来源](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 中的 Stream 规范。 |
| options | XpsSaveOptions | 转换选项。使用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象可以微调渲染过程；您可以指定页面大小、边距、CSS 等。 |
| outputPath | String | 完整的 .xps 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开一个现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 XpsSaveOptions 对象，并设置诸如页面大小、边距、CSS 等首选参数。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传入 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。在线 EPUB 到 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // 打开一个现有的 EPUB 文件进行读取
  using var stream = File.OpenRead(DataDir + "input.epub");

  // 准备一个路径以保存转换后的文件 
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // 创建 XpsSaveOptions 的实例。设置页面大小并将背景颜色更改为 LightGray 
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // 调用 ConvertEPUB 方法将 EPUB 转换为 XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

将通过输入 EPUB 文件路径提供的 epub 源转换为 xps。结果是由完整路径定义的 xps 文件。

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | XpsSaveOptions | 转换选项。使用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象可以微调渲染过程；您可以指定 [`页面大小`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`边距`](../../../com.aspose.html.drawing/page/margin/)、[`CSS 媒体类型`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的 .xps 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开一个现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 XpsSaveOptions 对象，并设置诸如页面大小、边距、CSS 等首选参数。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传入 EPUB 源数据、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和输出数据缓冲区，以启动转换过程。在线 EPUB 到 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

将通过 URL 提供的 epub 源转换为由完整路径定义的 xps 文件。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/)。

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | XpsSaveOptions | 转换选项。使用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象可以微调渲染过程；您可以指定 [`页面大小`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`边距`](../../../com.aspose.html.drawing/page/margin/)、[`CSS 媒体类型`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的 .xps 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。

在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

将通过输入 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供的 epub 源转换为 xps。结果是由完整路径定义的 xps 文件。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 转换选项。使用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象可以微调渲染过程；您可以指定 [`页面大小`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`边距`](../../../com.aspose.html.drawing/page/margin/)、[`CSS 媒体类型`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的 .xps 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// 打开一个现有的 EPUB 文件进行读取
import var stream = File.OpenRead(DataDir + "input.epub");

// 为转换后的文件保存准备路径
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// 初始化 XpsSaveOptions
var options = new XpsSaveOptions();
   
// 调用 ConvertEPUB 方法将 EPUB 转换为 XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

将通过输入 EPUB 文件路径提供的 epub 源转换为 xps。结果是由完整路径定义的 xps 文件。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | XpsSaveOptions | 转换选项。 [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) 对象的使用使您能够调优渲染过程；您可以指定页面大小、边距、CSS 等。 |
| outputPath | String | 完整的 .xps 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

将通过 URL 提供的 epub 源转换为由完整路径定义的 xps 文件。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/)。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | XpsSaveOptions | 转换选项。 [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) 对象的使用使您能够调优渲染过程；您可以指定页面大小、边距、CSS 等。 |
| outputPath | String | 完整的 .xps 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

将以输入 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供的 epub 源转换为 xps。结果是由已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现定义的 xps 输出数据。

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| options | XpsSaveOptions | 转换选项。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调优渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 接口的实现将用于获取输出流。请参阅在 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) 中的 ICreateStreamProvider 实现示例。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // 创建 MemoryStreamProvider 实例
 using var streamProvider = new MemoryStreamProvider();

 // 打开一个现有的 EPUB 文件进行读取
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // 准备一个路径以保存转换后的文件 
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // 使用 MemoryStreamProvider 类将 EPUB 转换为 XPS
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // 获取包含结果数据的内存流的访问权限
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // 将结果数据刷新到输出文件
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

将以输入 EPUB 文件路径提供的 epub 源转换为 xps。结果是由已知或自定义的 [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现定义的 xps 输出数据。

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | XpsSaveOptions | 转换选项。 [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) 对象的使用使您能够调优渲染过程；您可以指定页面大小、边距、CSS 等。 |
| provider | ICreateStreamProvider | 接口的实现将用于获取输出流。请参阅在 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开一个现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 XpsSaveOptions 对象，并设置诸如页面大小、边距、CSS 等首选参数。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传入 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。在线 EPUB 到 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

将以 URL 提供的 epub 源转换为由完整路径定义的 xps 文件。结果是由已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现定义的 xps 输出数据。

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | XpsSaveOptions | 转换选项。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调优渲染过程；您可以指定页面大小、边距、CSS 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现将用于获取输出流。请参阅在 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

将以输入 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供的 epub 源转换为 xps。结果是由已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现定义的 xps 输出数据。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 转换选项。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调优渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，该实现将用于获取输出流。请参阅在 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

将以输入 EPUB 文件路径提供的 epub 源转换为 xps。结果是由已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现定义的 xps 输出数据。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 转换选项。使用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象可以微调渲染过程；您可以指定页面大小、边距、CSS 等。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，该实现将用于获取输出流。请参阅在 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

将以 URL 提供的 epub 源转换为由完整路径定义的 xps 文件。结果是由已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现定义的 xps 输出数据。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | 转换选项。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调优渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，该实现将用于获取输出流。请参阅在 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 XPS

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些场景的信息，该类将所有低层次的转换操作集中在一个类中，使其舒适且易于使用。在 EPUB Converter XPS 专用指南中，您会找到以下文章：

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

将 EPUB 转换为 XPS

要将 EPUB 转换为 XPS 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 `ICreateStreamProvider` 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出为文件路径。创建一个带有首选参数（如页面大小、边距、CSS 等）的 XpsSaveOptions 对象。也可以使用 XpsSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 xps 文件。您需要以任意形式传递 EPUB 源数据、XpsSaveOptions 和输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的配置，该对象用于为应用程序设置环境设置。在线 EPUB 转 XPS 转换器

Aspose.HTML 提供免费的在线 [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可高质量、快速且简便地将 EPUB 转换为 XPS 文件。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// 创建默认选项实例  
var options = new XpsSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

将通过完整路径提供的 EPUB 源文件转换为 DOCX。结果是由完整路径定义的 docx 文件。

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 转换源由输入的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) 提供。 |
| options | DocSaveOptions | 转换选项。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| outputPath | String | 完整的 .docx 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// 创建默认选项实例  
var options = new DocSaveOptions();   

// 启动转换过程
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

将通过完整文件路径提供的 EPUB 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径作为输入参数。 |
| options | DocSaveOptions | 转换选项。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| outputPath | String | 完整的 .docx 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// 定义默认选项实例
var options = new DocSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

将通过 URL 提供的 EPUB 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| outputPath | String | 完整的 .docx 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// 定义默认选项实例
var options = new DocSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

将通过数据输入流提供的 EPUB 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | 转换选项。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| outputPath | String | 完整的 .docx 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// 创建默认选项实例  
var options = new DocSaveOptions();   

// 使用默认配置启动转换过程
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

将通过完整文件路径提供的 EPUB 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | 转换选项。[DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)对象的使用使您能够调节渲染过程；您可以指定页面大小、边距、CSS 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| outputPath | String | 完整的 .docx 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// 定义默认选项实例
var options = new DocSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

将通过 URL 提供的 EPUB 源转换。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| outputPath | String | 完整的 .docx 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 表单转换结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// 创建默认选项实例  
var options = new DocSaveOptions();

// 使用默认配置启动转换过程  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

将 EPUB 源作为输入流转换为 DOCX。结果是由 ICreateStreamProvider 实现生成的 docx 文件。

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| options | DocSaveOptions | 转换选项。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// 创建默认选项实例  
var options = new DocSaveOptions();   

// 启动转换过程
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

将以完整文件路径呈现的 EPUB 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 实现形成的输出数据。

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | DocSaveOptions | 转换选项。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// 创建默认选项实例  
var options = new DocSaveOptions ();   

// 启动转换过程  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

将通过 URL 提供的 EPUB 源转换。结果是由 ICreateStreamProvider 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 的使用使您能够调节渲染过程；您可以指定页面大小、边距、分辨率、CSS 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 DocSaveOptions 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 通过输入文件路径形成源 URL
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// 创建默认选项实例  
var options = new DocSaveOptions ();   

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

将通过数据输入流提供的 EPUB 源转换。结果是由 ICreateStreamProvider 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// 创建默认选项实例  
var options = new DocSaveOptions();   

// 使用默认配置启动转换过程
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

将以完整文件路径呈现的 EPUB 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | 转换选项。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// 创建默认选项实例  
var options = new DocSaveOptions ();   

// 启动转换过程  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

将以 URL 呈现的 EPUB 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options)。 |
| provider | ICreateStreamProvider | 实现 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口，用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 DOCX

DOCX 是一种广为人知的 Microsoft Word 文档格式。该格式因支持广泛的排版功能并为用户提供多种编写各种文档的选项而受到欢迎。DOCX 文件可在 Word 2007 及其后续版本中打开，但不能在早期的 MS Word 版本（仅支持 DOC 文件扩展名）中打开。EPUB 转换为 DOCX 通常是为了在特定用户任务中利用 DOCX 格式的优势。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供了受支持的 EPUB 转换场景列表及其使用 [`Converter`](../) 类执行的方法，该类将所有低层次的转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB Converter DOCX 专用指南中，您可以找到以下文章：

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 DOCX

要将 EPUB 转换为 DOCX 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。也可以使用更简单的方式，即将结果输出为文件路径。创建一个新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象，并设置一系列首选参数，如页面大小、边距、CSS 等。也可以使用 DocSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 docx 文件。您需要将 EPUB 源数据以文件路径或输入流的形式传入，同时提供 Url、DocSaveOptions 实例以及以任意形式的输出数据缓冲区，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration 来设置应用程序的环境设置。在线 EPUB 转 DOCX 转换器

Aspose.HTML 提供免费的在线 [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) 转换器，可将 EPUB 高质量、轻松且快速地转换为 DOCX 文件。只需上传，转换您的文件，几秒钟即可获得结果！

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// 创建默认选项实例  
var options = new DocSaveOptions();   

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

将通过数据输入流提供的 EPUB 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | EPUB 源文件路径作为输入参数。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| outputPath | String | 完整的 .pdf 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 表单结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// 创建默认选项实例  
var options = new PdfSaveOptions();   

// 启动转换过程  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

将通过完整文件路径提供的 EPUB 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| outputPath | String | 完整的 .pdf 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// 定义默认选项实例
var options = new PdfSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参阅

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

将通过 URL 提供的 EPUB 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 的使用使您能够微调渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| outputPath | String | 完整的 .pdf 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// 基于输入文件路径创建 Url
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// 定义默认选项实例
var options = new com.aspose.html.saving.PdfSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

将通过数据输入流提供的 EPUB 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| outputPath | String | 完整的 .pdf 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 表单结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// 创建默认选项实例  
var options = new PdfSaveOptions();   

// 使用默认配置启动转换过程
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

将通过数据输入流提供的 EPUB 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| outputPath | String | 完整的 .pdf 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// 表单源文件路径
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// 定义默认选项实例
var options = new PdfSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

将通过 URL 提供的 EPUB 源转换。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 的使用使您能够微调渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| outputPath | String | 完整的 .pdf 文件路径作为输出转换结果。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 形成输出结果文件路径
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// 定义默认选项实例
var options = new PdfSaveOptions();

// 使用默认配置启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

将通过数据输入流提供的 EPUB 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// 创建默认选项实例  
var options = new PdfSaveOptions ();   

// 启动转换过程  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

将通过完整文件路径提供的 EPUB 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口的实现，将用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// 创建默认选项实例  
var options = new PdfSaveOptions();   

// 启动转换过程  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

将以 URL 呈现的 EPUB 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 的使用使您能够微调渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | ICreateStreamProvider 接口的实现（[ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)），将用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// 定义默认选项实例
var options = new PdfSaveOptions();

// 启动转换过程
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

将通过数据输入流提供的 EPUB 源进行转换。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 输入流作为转换来源。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | 转换选项。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)对象的使用使您能够调节渲染过程；您可以指定[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), 等等。参见 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口的实现，将用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字图书和出版物，可在智能手机、平板电脑和电脑上查看和阅读。[`com.aspose.html.converters`](../) 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/) 和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 以流方式打开现有文件进行读取  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// 创建默认选项实例  
var options = new PdfSaveOptions ();   

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

将通过完整文件路径提供的 EPUB 源转换为 PDF。结果是由 ICreateStreamProvider 接口实现形成的输出数据。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | EPUB 源文件路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | PdfSaveOptions | 转换选项。使用 [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) 对象可以微调渲染过程；您可以指定页面大小、边距、CSS 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | ICreateStreamProvider 接口的实现（[ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)），将用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// 创建默认选项实例  
var options = new PdfSaveOptions();   

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

将以 URL 呈现的 EPUB 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceUrl | Url | EPUB 源 URL - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 的使用使您能够微调渲染过程；您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | ICreateStreamProvider 接口的实现（[ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)），将用于获取输出流。请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) 中的高级示例。 |

## 备注

如何将 EPUB 转换为 PDF

EPUB 是一种电子书文件格式，提供标准的数字出版格式。它由国际数字出版论坛（[IDPF](http://idpf.org/)）创建，现在被许多电子阅读器和软件应用程序支持。EPUB 转换为 PDF 通常是为了利用 PDF 格式的优势。PDF 文件格式具备完整的能力来包含文本、图像、超链接、表单字段、富媒体、元数据等信息。PDF 文件可以在 Adobe Acrobat Reader/Writer 以及大多数现代浏览器（如 Chrome、Safari、Firefox）中打开。它们针对打印进行了优化，是创建文档纸质副本的理想选择；您还可以为 PDF 配置安全设置。

Aspose.HTML 的主要亮点是转换功能。EPUB 是一种基于 XML 的开放格式，用于数字书籍和出版物，可在智能手机、平板电脑和电脑上查看和阅读。com.aspose.html.converters 包实现了对转换方法的便捷访问。它提供了广泛的 [EPUB](https://docs.fileformat.com/ebook/epub/) 转换，支持流行格式，如 [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、和 [GIF](https://docs.fileformat.com/image/gif/)。

本节提供有关受支持的 EPUB 转换场景列表以及如何使用 [`Converter`](../) 类执行这些转换的信息，该类将所有低层转换操作集中在一个类中，使其使用起来舒适且简便。在 EPUB 转换器 PDF 专门指南中，您会找到以下文章：

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

将 EPUB 转换为 PDF

要将 EPUB 转换为 PDF 文件格式，您应遵循以下几个步骤：

打开现有的 EPUB 文件。例如，我们可以将源文件路径定义为 ConvertEPUB 方法的第一个参数。也可以使用输入流或 Url 对象实例作为替代。使用已知或自定义的 ICreateStreamProvider 接口实现作为输出数据缓冲区。我们也可以使用更简单的方式，即将结果输出文件路径作为替代。创建一个新的 PdfSaveOptions 对象，并设置首选参数，如页面大小、边距、CSS 等。也可以使用 PdfSaveOptions 类的默认实例。使用静态 Converter 类的 ConvertEPUB() 方法将 EPUB 保存为 pdf 文件。您需要将 EPUB 源数据以文件路径或输入流的形式，以及 Url、PdfSaveOptions 实例和任意形式的输出数据缓冲区一起传递，以启动转换过程。您可以使用表示 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象的 configuration，该对象用于为应用程序设置环境设置。在线 EPUB 到 PDF 转换器

Aspose.HTML 提供免费的在线 [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) 转换器，可将 EPUB 高质量、轻松且快速地转换为 PDF 文件。只需上传、转换您的文件，几秒钟即可获取结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// 基于输入文件路径创建 Url
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 参考 ICreateStreamProvider 接口实现  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// 定义默认选项实例
var options = new PdfSaveOptions();

// 使用默认配置对象启动转换过程
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
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
