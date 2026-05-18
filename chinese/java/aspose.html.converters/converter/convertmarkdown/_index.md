---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML for Java API 参考"
description: "Converter 方法。将通过输入流提供的 MD markdown 源转换为 html。结果是 HTMLDocument，可通过输出文件路径保存。"
type: docs

url: /zh/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

将通过输入流提供的 MD（markdown）源转换为 html。结果是 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可通过输出文件路径保存。

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MD（Markdown）转换输入数据流。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // 以流方式打开源文件
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 启动转换过程
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // 保存转换结果
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

将通过输入流提供的 MD（markdown）源转换为 html。结果是 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可通过输出文件路径保存。

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MD（Markdown）转换输入数据流。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 以流方式打开源文件
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 使用默认配置启动转换过程
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // 保存转换结果
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

将通过输入流提供的 MD（markdown）源转换为 html。结果是由输出文件路径生成的 html 文件。

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MD（Markdown）转换输入数据流。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 以流方式打开源文件
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 启动转换过程
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

将通过输入流提供的 MD（markdown）源转换为 html。结果是由输出文件路径生成的 html 文件。

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | MD（Markdown）转换输入数据流。 |
| baseUri | String | 文档的基础 URI。它将与当前目录路径组合以形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 以流方式打开源文件
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 使用默认配置启动转换过程
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

将通过完整文件路径提供的 MD（markdown）源转换为 html。结果是 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可通过输出文件路径保存。

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MD（Markdown）源完整文件路径。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 启动转换过程
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // 将转换结果保存为本地文件
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

将通过完整文件路径提供的 MD（markdown）源转换为 html。结果是 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可通过输出文件路径保存。

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | MD（Markdown）源完整文件路径。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 使用默认配置启动转换过程
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // 将转换结果保存为本地文件
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

将通过完整文件路径提供的 MD（markdown）源转换为 html。结果是由输出文件路径生成的 html 文件。

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 源 Markdown 文件的路径。它将与当前目录路径组合形成绝对 URL。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 启动转换过程
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 另请参阅

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

将通过完整文件路径提供的 MD（markdown）源转换为 html。结果是由输出文件路径生成的 html 文件。

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 源 Markdown 文件的路径。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

Markdown 转换器

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

转换步骤

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

转换来源。检测现有的本地 MD 文件或创建输入数据流作为转换来源。转换结果。您可以直接获取 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 或根据方法签名定义结果输出文件路径。使用 Converter 类的 ConvertMarkdown() 方法将 MD 保存为 html 结果。您还可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。在线 MD 转换器

您可能也会对免费的在线 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) 感兴趣，它能够高质量、简便、快速地将 MD 转换为 HTML。只需上传、转换文件，即可在几秒钟内获得结果！您还可以查看其他在线 MD 转换器：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps)，并找到合适的 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 使用默认配置启动转换过程
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
