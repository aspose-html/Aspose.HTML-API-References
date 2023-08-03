---
title: Converter.ConvertSVG
second_title: Aspose.HTML for Java API Reference
description: Converter method. Convert SVG source presented by SVGDocument. Result is docx file formed by output file path
type: docs
weight: 50
url: /net/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Result is docx file formed by output file path.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process with default configuration
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is docx file formed by output file path.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source. Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer. Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is docx file formed by output file path.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Convert SVG source presented by full file path to DOCX. Result is docx file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Convert SVG source presented by full file path to DOCX. Result is docx file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Convert SVG source presented by inline content. Result is docx file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Convert SVG source presented by inline content. Result is docx file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process with default configuration
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is docx file formed by output file path.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Convert SVG source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Convert SVG source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Convert SVG source presented by inline content to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Convert SVG source presented by inline content to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process with default configuration
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is pdf file formed by output file path.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is pdf file formed by output file path.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Convert SVG source presented by full file path to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Convert SVG source presented by full file path to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Convert SVG source presented by inline content to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Convert SVG source presented by inline content to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process with default configuration
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Convert SVG source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Convert SVG source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Convert SVG source presented by inline content to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Convert SVG source presented by inline content to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Result is image file formed by output file path.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process with default configuration
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is image file formed by output file path.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is image file formed by output file path.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Convert SVG source presented by full file path to image. Result is image file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Convert SVG source presented by full file path to image. Result is image file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Convert SVG source presented by inline content to image. Result is image file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Convert SVG source presented by inline content to image. Result is image file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Convert SVG source presented by full file path to image. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Convert SVG source presented by full file path to image. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Convert SVG source presented by inline content to image. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Convert SVG source presented by inline content to image. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO; 
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Result is xps file formed by output file path.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Initiate conversion process with default configuration
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is xps file formed by output file path.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path     
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is xps file formed by output file path.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Create Url based on input file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Convert SVG source presented by full file path to XPS. Result is xps file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Convert SVG source presented by full file path to XPS. Result is xps file formed by output file path.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Convert SVG source presented by inline content to XPS. Result is xps file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Convert SVG source presented by inline content to XPS. Result is xps file formed by output file path.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      // Form inline svg content
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Convert SVG source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Form SVG document as conversion source
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Initiate conversion process with default configuration
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Convert SVG source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Convert SVG source presented by full file path to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Convert SVG source presented by full file path to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Convert SVG source presented by inline content to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Convert SVG source presented by inline content to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also define [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) as conversion source or even use inline SVG content presented by String source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)
