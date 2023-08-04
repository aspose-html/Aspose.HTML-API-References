---
title: Converter.ConvertMHTML
second_title: Aspose.HTML for Java API Reference
description: Converter method. Convert MHTML source presented by input stream. Result is xps file formed by output file path
type: docs
weight: 40
url: /java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Convert MHTML source presented by input [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Result is xps file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input mhtml (.mht) data stream. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;  
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Convert MHTML source presented by full file path to XPS. Result is xps file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;  
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
	// Form source file path
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Form result file path
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Define default XpsSaveOptions object
	var options = new XpsSaveOptions();

	// Initiate conversion process
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Convert MHTML source presented by URL. Result is xps file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;  
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
	// Form source file path
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Form result file path
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Define default XpsSaveOptions object
	var options = new XpsSaveOptions();

	// Initiate conversion process
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Convert MHTML source presented by input [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0). Result is xps file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Conversion source mhtml (.mht) data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;  
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Convert MHTML source presented by full file path to XPS. Result is xps file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;  
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      // Form source file path
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Convert MHTML source presented by URL. Result is xps file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Full xps file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;  
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
... 
      // Form source file path
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Conversion source mhtml (.mht) data stream. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Convert MHTML source presented by full file path to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Convert MHTML source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Conversion source mhtml (.mht) data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Convert MHTML source presented by full file path to XPS. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Convert MHTML source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

MHTML to [XPS](https://docs.fileformat.com/page-description-language/xps/) conversion is often required to take advantage of XPS format for specific tasks. An XPS file represents page layout files that are based on XML Paper Specifications, created by Microsoft.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) where you find information on how to convert MHTML to XPS using ConvertHTML() methods of the [`Converter`](../) class and how to apply [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to XPS

Converter class offers few MHTML specific conversions to XPS. To convert MHTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an XPS result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) that converts MHTML to XPS with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default XpsSaveOptions object
      var options = new XpsSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Convert MHTML source presented by input stream. Result is docx file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Convert MHTML source presented by full file path to DOCX. Result is docx file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source file path. It will be combined with the current directory path to form an absolute URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Convert MHTML source presented by URL. Result is docx file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Convert MHTML source presented by input stream. Result is docx file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Convert MHTML source presented by full file path to DOCX. Result is docx file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Convert MHTML source presented by [`URL`](../../../com.aspose.html/url/). Result is docx file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Full docx file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Convert MHTML source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Convert MHTML source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Convert MHTML source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Convert MHTML source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document [`URL`](../../../com.aspose.html/url/) - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to DOCX conversion is often required to take advantage of [DOCX](https://docs.fileformat.com/word-processing/docx/) format for specific tasks. DOCX is a well-known format for Microsoft Word documents. It can contain a wide range of data, including text, tables, raster and vector graphics, video, sounds and diagrams. This format is popular because it supports complex formatting features and offers to users a variety of options to write any type of document.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) where you find information on how to convert MHTML to DOCX using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to DOCX

Converter class offers few MHTML specific conversions to DOCX. To convert MHTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as conversion source. Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer. Create a new [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an DOCX result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) that converts MHTML to DOCX with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default DocSaveOptions object
      var options = new DocSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Convert MHTML source presented by input stream. Result is pdf file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Convert MHTML source presented by full file path to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Convert MHTML source presented by URL. Result is pdf file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Convert MHTML source presented by input stream. Result is pdf file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Convert MHTML source presented by full file path to PDF. Result is pdf file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Convert MHTML source presented by URL. Result is pdf file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Full pdf file path as output conversion result. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Convert MHTML source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source file path. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Convert MHTML source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Convert MHTML source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Convert MHTML source presented by [`URL`](../../../com.aspose.html/url/). Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process. For more info see [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

MHTML to PDF conversion is often required to take advantage of [PDF](https://docs.fileformat.com/pdf/) format for specific tasks. PDF comes with many benefits that other files don’t have. For example, many programs and apps support PDF documents; PDF files are optimized for printing, and they are ideal for creating physical copies of your documents; you can configure the security settings for PDF files - disable printing, editing, using an electronic signature, etc.

Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), where you find information on how to convert MHTML to PDF using ConvertMHTML() methods of the [`Converter`](../) class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to PDF

Converter class offers few MHTML specific conversions to PDF. To convert MHTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote Url as conversion source. You can also use standard or custom specific [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object with specific or default settings. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an PDF result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) that converts MHTML to PDF with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default PdfSaveOptions object
      var options = new PdfSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Convert MHTML source presented by input stream to image. Result is image file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source. Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer. Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Convert MHTML source presented by full file path. Result is image file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Convert MHTML source presented by URL. Result is image file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Convert MHTML source presented by input stream to image. Result is image file formed by output file path.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Convert MHTML source presented by full file path. Result is image file formed by output file path.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Convert MHTML source presented by URL. Result is image file formed by output file path.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Convert MHTML source presented by full file path to image. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Convert MHTML source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Convert MHTML source presented by input stream. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | MHTML conversion input data stream. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Initiate conversion process
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Convert MHTML source presented by full file path to image. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | MHTML source full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [` interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions();

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Convert MHTML source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | MHTML source document URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object usage enables you to tune the rendering process. You can specify the [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. |

## Remarks

MHTML Converter

Files with [MHTML](https://docs.fileformat.com/web/mhtml/) extension represent a web page archive format that a number of different applications can create. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The actual specifications of the format are as detailed by [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Refer to article, where you find information on how to convert MHTML to images in different formats using ConvertMHTML() methods of the Converter class and how to apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convert MHTML to Image

Converter class offers few MHTML specific conversions to images. Supported formats are [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) and [TIFF](https://docs.fileformat.com/image/tiff/). To convert MHTML to image, you should follow one of simple scenarios consists of few steps:

Conversion source. Detect an existing local MHTML (.mht) file or remote [`Url`](../../../com.aspose.html/url/) as conversion source. You can also use standard or custom specific stream as source.Conversion result. Define result output file path or use known or custom [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object with specific or default settings. Default image format is PNG. You can add also configuration as option parameter.Use the ConvertMHTML() method of the Converter class to save MHTML as an image result with three or more parameters depend on user scenario.Online MHTML converter

Aspose.HTML offers a free online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) that converts MHTML to jpeg file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result");

      // Define default ImageSaveOptions object
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Use one of ICreateStreamProvider implementation
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiate conversion process with default configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
