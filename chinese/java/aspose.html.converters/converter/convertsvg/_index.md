---
title: "Converter.ConvertSVG"
second_title: "Aspose.HTML for Java API 参考"
description: "Converter 方法。将由 SVGDocument 呈现的 SVG 源进行转换。结果是由 ICreateStreamProvider 接口实现形成的输出数据"
type: docs

url: /zh/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

将由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// 使用默认配置启动转换过程
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

将通过完整文件路径呈现的 SVG 源转换为 XPS。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

将通过完整文件路径呈现的 SVG 源转换为 XPS。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

将以内联内容呈现的 SVG 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

将以内联内容呈现的 SVG 源转换为 XPS。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

将由 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 呈现的 SVG 源转换。结果是由输出文件路径形成的 docx 文件。

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 使用默认配置启动转换过程
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

将由 [`URL`](../../../com.aspose.html/url/) 呈现的 SVG 源转换。结果是由输出文件路径形成的 docx 文件。

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

将由 [`URL`](../../../com.aspose.html/url/) 呈现的 SVG 源转换。结果是由输出文件路径形成的 docx 文件。

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

将通过完整文件路径提供的 SVG 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

将通过完整文件路径提供的 SVG 源转换为 DOCX。结果是由输出文件路径生成的 docx 文件。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

将通过内联内容呈现的 SVG 源转换。结果是通过输出文件路径形成的 docx 文件。

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

将通过内联内容呈现的 SVG 源转换。结果是通过输出文件路径形成的 docx 文件。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| outputPath | String | 完整的 docx 文件路径，作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

将由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 使用默认配置启动转换过程
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

将由 [`URL`](../../../com.aspose.html/url/) 呈现的 SVG 源转换。结果是由输出文件路径形成的 docx 文件。

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

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

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

将通过完整文件路径呈现的 SVG 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

将通过完整文件路径呈现的 SVG 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

将以内联内容呈现的 SVG 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 另请参见

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

将以内联内容呈现的 SVG 源转换为 DOCX。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)，其中提供了如何使用 Converter 类的 ConvertSVG() 方法将 SVG 转换为 [DOCX](https://docs.fileformat.com/word-processing/docx/)，以及如何应用 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 DOCX

Converter 类提供多种针对 SVG 转换为 DOCX 的特定转换。要将 SVG 转换为 DOCX，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 DOCX 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)，可高质量、简便、快速地将 SVG 转换为 DOCX。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认 DocSaveOptions 对象
      var options = new DocSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

将由 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 呈现的 SVG 源转换为 PDF。结果是由输出文件路径形成的 pdf 文件。

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 使用默认配置启动转换过程
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

将由 [`URL`](../../../com.aspose.html/url/) 呈现的 SVG 源转换。结果是由输出文件路径形成的 pdf 文件。

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

将由 [`URL`](../../../com.aspose.html/url/) 呈现的 SVG 源转换。结果是由输出文件路径形成的 pdf 文件。

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

将通过完整文件路径提供的 SVG 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

将通过完整文件路径提供的 SVG 源转换为 PDF。结果是由输出文件路径生成的 pdf 文件。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

将通过内联内容呈现的 SVG 源转换为 PDF。结果是通过输出文件路径形成的 pdf 文件。

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

将通过内联内容呈现的 SVG 源转换为 PDF。结果是通过输出文件路径形成的 pdf 文件。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| outputPath | String | 完整的 pdf 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

将由 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 呈现的 SVG 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 使用默认配置启动转换过程
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

将通过完整文件路径呈现的 SVG 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

将通过完整文件路径呈现的 SVG 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

将以内联内容呈现的 SVG 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 另请参见

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

将以内联内容呈现的 SVG 源转换为 PDF。结果是由 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现形成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose 文档](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)，其中提供了如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 PDF，以及如何应用 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 PDF

Converter 类提供多种针对 SVG 转换为 PDF 的特定转换。要将 SVG 转换为 PDF，您应遵循由几个步骤组成的简单场景之一：

转换来源。检测本地已有的 SVG 文件或远程 [`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 对象。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 PDF 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)，可高质量、简便、快速地将 SVG 转换为 PDF。只需上传、转换文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 PdfSaveOptions 对象
      var options = new PdfSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

将由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的 SVG 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 使用默认配置启动转换过程
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源转换。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

将通过完整文件路径提供的 SVG 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

将通过完整文件路径提供的 SVG 源转换为图像。结果是由输出文件路径生成的图像文件。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

将通过内联内容呈现的 SVG 源转换为图像。结果是通过输出文件路径形成的图像文件。

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

将通过内联内容呈现的 SVG 源转换为图像。结果是通过输出文件路径形成的图像文件。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| outputPath | String | 完整的图像文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

将由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 启动转换过程
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源进行转换。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现形成的输出数据。

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

将通过完整文件路径呈现的 SVG 源转换为图像。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现生成的输出数据。

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

将通过完整文件路径呈现的 SVG 源转换为图像。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现生成的输出数据。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

将通过内联内容呈现的 SVG 源转换为图像。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现生成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | 已知（参见 [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)）或自定义的 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 另请参见

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

将通过内联内容呈现的 SVG 源转换为图像。结果是由[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现生成的输出数据。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | ImageSaveOptions | 使用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象可调节渲染过程。您可以指定 [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 等。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) 的实现，将用于获取输出流。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

请参阅[文章](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)，其中您可以找到使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 JPG 的信息，以及如何应用 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数。其他流行图像格式的相关文章有：[SVG 转 PNG 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG 转 BMP 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG 转 GIF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 和 [SVG 转 TIFF 转换](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

将 SVG 转换为图像

Converter 类提供多种针对 SVG 的图像转换，支持流行格式。要将 SVG 转换为图像，您应遵循以下简单场景之一，包含几个步骤：

转换来源。检测本地已有的 SVG 文件或远程[`Url`](../../../com.aspose.html/url/) 作为转换来源。您也可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 定义为转换来源，甚至使用由字符串提供的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 接口实现作为输出数据缓冲区。创建一个带有特定或默认设置的新的[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 对象。请注意，默认的图像格式是 PNG。您还可以将[`configuration`](../../../com.aspose.html/configuration/) 作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为图像结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线[SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg)，可高质量、简便、快速地将 SVG 转换为 JPG。只需上传、转换文件，即可在几秒钟内获取结果！

其他流行的不同格式图像转换器可在此找到：[SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) 和 [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 使用 ICreateStreamProvider 的一种实现
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 定义默认的 ImageSaveOptions 对象
      var options = new ImageSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

将由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的 SVG 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | SVGDocument | 由[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)呈现的转换源。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 将 SVG 文档形成转换源
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// 使用默认配置启动转换过程
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

将由[`URL`](../../../com.aspose.html/url/)呈现的 SVG 源转换。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | SVG 源文档 [`URL`](../../../com.aspose.html/url/) - 提供通用标识符（URL）的对象表示。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

将通过完整文件路径提供的 SVG 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

将通过完整文件路径提供的 SVG 源转换为 XPS。结果是由输出文件路径生成的 xps 文件。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | SVG 源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

将通过内联内容呈现的 SVG 源转换为 XPS。结果是通过输出文件路径形成的 xps 文件。

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 启动转换过程
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

将通过内联内容呈现的 SVG 源转换为 XPS。结果是通过输出文件路径形成的 xps 文件。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 字符串作为内联 SVG 内容。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 对象的使用使您能够调节渲染过程。欲了解更多信息，请参阅 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)。 |
| outputPath | String | 完整的 xps 文件路径作为输出转换结果。 |

## 备注

SVG 转换器

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)，其中您可以找到关于如何使用 [`Converter`](../) 类的 ConvertSVG() 方法将 SVG 转换为 XPS，以及如何应用 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 和 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 参数的信息。

将 SVG 转换为 XPS

Converter 类提供多种针对 SVG 转换为 XPS 的特定转换。要将 SVG 转换为 XPS，您应遵循由几个步骤组成的简单场景之一：

转换源。检测现有的本地 SVG 文件或远程[`Url`](../../../com.aspose.html/url/)作为转换源。您还可以将[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)定义为转换源，甚至使用由字符串源呈现的内联 SVG 内容。转换结果。定义结果输出文件路径，或使用已知或自定义的[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)接口实现作为输出数据缓冲区。创建一个具有特定或默认设置的新的[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)对象。您还可以将[`configuration`](../../../com.aspose.html/configuration/)作为选项参数添加。使用 Converter 类的 ConvertSVG() 方法将 SVG 保存为 XPS 结果，参数根据用户场景可为三项或更多。在线 SVG 转换器

Aspose.HTML 提供免费的在线 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)，可高质量、简便且快速地将 SVG 转换为 XPS。只需上传、转换您的文件，即可在几秒钟内获得结果！

源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 表单内联 SVG 内容
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 定义默认的 XpsSaveOptions 对象
      var options = new XpsSaveOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 另请参见

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
