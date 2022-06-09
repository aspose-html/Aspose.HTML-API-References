---
title: ConvertSVG
second_title: Aspose.HTML for .NET API Reference
description: Convert SVG source presented by SVGDocumentaspose.html.dom.svg/svgdocument. Result is docx file formed by output file path.
type: docs
weight: 50
url: /net/aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, DocSaveOptions, string) {#convertsvg_1}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, string) {#convertsvg_17}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(Url url, DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source. Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer. Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, string) {#convertsvg_9}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, DocSaveOptions, string) {#convertsvg_33}

Convert SVG source presented by full file path to DOCX. Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, DocSaveOptions, string) {#convertsvg_25}

Convert SVG source presented by full file path to DOCX. Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, DocSaveOptions, string) {#convertsvg_49}

Convert SVG source presented by inline content. Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, DocSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, DocSaveOptions, string) {#convertsvg_41}

Convert SVG source presented by inline content. Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Full docx file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is docx file formed by output file path.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Convert SVG source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Convert SVG source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Convert SVG source presented by inline content to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Convert SVG source presented by inline content to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) where you find information on how to convert SVG to [DOCX](https://docs.fileformat.com/word-processing/docx/) using ConvertSVG() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to DOCX

Converter class offers multiple SVG specific conversions to DOCX. To convert SVG to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an DOCX result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) that converts SVG to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, string) {#convertsvg_5}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) to PDF. Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, string) {#convertsvg_21}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(Url url, PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, string) {#convertsvg_13}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, PdfSaveOptions, string) {#convertsvg_37}

Convert SVG source presented by full file path to PDF. Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, PdfSaveOptions, string) {#convertsvg_29}

Convert SVG source presented by full file path to PDF. Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, PdfSaveOptions, string) {#convertsvg_53}

Convert SVG source presented by inline content to PDF. Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, PdfSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, PdfSaveOptions, string) {#convertsvg_45}

Convert SVG source presented by inline content to PDF. Result is pdf file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Convert SVG source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Convert SVG source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Convert SVG source presented by inline content to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Convert SVG source presented by inline content to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) where you find information on how to convert SVG to PDF using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to PDF

Converter class offers multiple SVG specific conversions to PDF. To convert SVG to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an PDF result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) that converts SVG to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, string) {#convertsvg_3}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). Result is image file formed by output file path.

```csharp
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, string) {#convertsvg_19}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is image file formed by output file path.

```csharp
public static void ConvertSVG(Url url, ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, string) {#convertsvg_11}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is image file formed by output file path.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, ImageSaveOptions, string) {#convertsvg_35}

Convert SVG source presented by full file path to image. Result is image file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, ImageSaveOptions, string) {#convertsvg_27}

Convert SVG source presented by full file path to image. Result is image file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, ImageSaveOptions, string) {#convertsvg_51}

Convert SVG source presented by inline content to image. Result is image file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, ImageSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, ImageSaveOptions, string) {#convertsvg_43}

Convert SVG source presented by inline content to image. Result is image file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Convert SVG source presented by full file path to image. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Convert SVG source presented by full file path to image. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Convert SVG source presented by inline content to image. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Convert SVG source presented by inline content to image. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup), [`margins`](../../../aspose.html.drawing/page/margin), [`CSS media-type`](../../../aspose.html.rendering/mediatype), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) where you find information on how to convert SVG to JPG using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters. Other popular image formats related articles: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) and [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convert SVG to Image

Converter class offers multiple SVG specific conversions to image in popular formats. To convert SVG to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions) object with specific or default settings. Notice that default image format is PNG. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an image result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) that converts SVG to JPG with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Other popular image converters for different formats can be founded here: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) and [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, string) {#convertsvg_7}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, string) {#convertsvg_23}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(Url url, XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, string) {#convertsvg_15}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, XpsSaveOptions, string) {#convertsvg_39}

Convert SVG source presented by full file path to XPS. Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, XpsSaveOptions, string) {#convertsvg_31}

Convert SVG source presented by full file path to XPS. Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, XpsSaveOptions, string) {#convertsvg_55}

Convert SVG source presented by inline content to XPS. Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, XpsSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, XpsSaveOptions, string) {#convertsvg_47}

Convert SVG source presented by inline content to XPS. Result is xps file formed by output file path.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Convert SVG source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Conversion source presented by [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Convert SVG source presented by [`URL`](../../../aspose.html/url). Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | SVG source document [`URL`](../../../aspose.html/url) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Url](../../../aspose.html/url)
* class [Configuration](../../../aspose.html/configuration)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Convert SVG source presented by full file path to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Convert SVG source presented by full file path to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | SVG source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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

* class [Configuration](../../../aspose.html/configuration)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Convert SVG source presented by inline content to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider), which will be used to get an output stream. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

---

## ConvertSVG(string, string, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Convert SVG source presented by inline content to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation.

```csharp
public static void ConvertSVG(string content, string baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | String as inline svg content. |
| baseUri | String | The base URI of the document. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider) interface implementation. |

### Remarks

SVG Converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) where you find information on how to convert SVG to XPS using ConvertSVG() methods of the [`Converter`](../../converter) class and how to apply [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) parameters.

Convert SVG to XPS

Converter class offers multiple SVG specific conversions to XPS. To convert SVG to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local SVG file or remote [`Url`](../../../aspose.html/url) as conversion source. You can also define [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument) as conversion source or even use inline SVG content presented by string source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions) object with specific or default settings. You can add also [`configuration`](../../../aspose.html/configuration) as option parameter.Use the ConvertSVG() method of the Converter class to save SVG as an XPS result with three or more parameters depend on user scenario.Online SVG converter

Aspose.HTML offers a free online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) that converts SVG to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
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
      Converter.ConvertSVG(content, string.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider)
* class [Converter](../../converter)
* namespace [Aspose.Html.Converters](../../converter)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
