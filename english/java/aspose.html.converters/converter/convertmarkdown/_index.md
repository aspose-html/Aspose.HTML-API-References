---
title: Converter.ConvertMarkdown
second_title: Aspose.HTML for Java API Reference
description: Converter method. Convert MD markdown source presented by input stream to html. Result is HTMLDocument which can be saved through output file path
type: docs
weight: 30
url: /net/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Convert MD (markdown) source presented by input stream to html. Result is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved through output file path.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MD (Markdown) conversion input data stream. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Open source file as stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiate conversion process
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Save conversion result
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Convert MD (markdown) source presented by input stream to html. Result is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved through output file path.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MD (Markdown) conversion input data stream. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Open source file as stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiate conversion process with default configuration
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Save conversion result
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Convert MD (markdown) source presented by input stream to html. Result is html file formed by output file path.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MD (Markdown) conversion input data stream. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Open source file as stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiate conversion process
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### See Also

* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Convert MD (markdown) source presented by input stream to html. Result is html file formed by output file path.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MD (Markdown) conversion input data stream. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Open source file as stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiate conversion process with default configuration
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Convert MD (markdown) source presented by full file path to html. Result is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved through output file path.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MD (Markdown) source full file path. |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiate conversion process
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Save conversion result as local file
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Convert MD (markdown) source presented by full file path to html. Result is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved through output file path.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MD (Markdown) source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiate conversion process with default configuration
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Save conversion result as local file
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Convert MD (markdown) source presented by full file path to html. Result is html file formed by output file path.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | Path to source Markdown file. It will be combined with the current directory path to form an absolute URL. |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiate conversion process
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### See Also

* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Convert MD (markdown) source presented by full file path to html. Result is html file formed by output file path.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | Path to source Markdown file. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Markdown Converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversion steps

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MD file or create input data stream as conversion source.Conversion result. You can obtain directly [`HTMLDocument`](../../../com.aspose.html/htmldocument/) or define result output file path depend of method signature.Use the ConvertMarkdown() method of the Converter class to save MD as an html result. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Online MD converter

You may also be interested in a free online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) that converts MD to HTML with high quality, easy and fast. Just upload, convert your files and get results in a few seconds! Also you can check other online MD converters: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) and find appropriate [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiate conversion process with default configuration
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)
