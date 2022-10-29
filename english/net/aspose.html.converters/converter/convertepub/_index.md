---
title: ConvertEPUB
second_title: Aspose.HTML for .NET API Reference
description: Convert EPUB source presented by file path to image. Result is image file formed by implementation of ICreateStreamProvideraspose.html.io/icreatestreamprovider/ interface.
type: docs
weight: 10
url: /net/aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(string, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Convert EPUB source presented by file path to image. Result is image file formed by implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface.

```csharp
public static void ConvertEPUB(string sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| options | ImageSaveOptions | New formed image options as format, resolution and etc. See [`ImageSaveOptions `](../../../aspose.html.saving/imagesaveoptions/)class and [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. More info about providers see in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Open an existing EPUB file. In the example, we use the OpenRead() method of System.IO.FileStream class to open and read an EPUB file from the file system at the specified path.Use known or custom ICreateStreamProvider interface implementation as output data buffer.Create a new ImageSaveOptions object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need to pass the EPUB inputStream, ImageSaveOptions, and output stream to the ConvertEPUB() method for EPUB to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

EPUB to JPG by two lines of code

```csharp
using System.IO;
using Aspose.Html.Converters;
using Aspose.Html.Rendering.Image;
using Aspose.Html.Saving;
...
// Open an existing EPUB file for reading.
using var stream = File.OpenRead(DataDir + "input.epub");

// Invoke the ConvertEPUB method to convert the EPUB code to JPG image      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### See Also

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Convert epub source presented by URL to image. Result is image file formed by implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface.

```csharp
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [`ImageSaveOptions `](../../../aspose.html.saving/imagesaveoptions/)class. |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. More info about providers see in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Open an existing EPUB file. In the example, we use the OpenRead() method of System.IO.FileStream class to open and read an EPUB file from the file system at the specified path.Use known or custom ICreateStreamProvider interface implementation as output data buffer.Create a new ImageSaveOptions object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need to pass the EPUB inputStream, ImageSaveOptions, and output stream to the ConvertEPUB() method for EPUB to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Create default options instance  
var options = new ImageSaveOptions();

// Initiate conversion process  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### See Also

* class [Url](../../../aspose.html/url/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Convert epub source presented by input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) to image. Result is image file formed by implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Open an existing EPUB file. In the example, we use the OpenRead() method of System.IO.FileStream class to open and read an EPUB file from the file system at the specified path.Use known or custom ICreateStreamProvider interface implementation as output data buffer.Create a new ImageSaveOptions object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need to pass the EPUB inputStream, ImageSaveOptions, and output stream to the ConvertEPUB() method for EPUB to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Create default options instance  
var options = new ImageSaveOptions();    


// Initiate conversion process with default configuration  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Convert epub source presented by file path to image. Result is image file formed by implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source defined by file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. See ICreateStreamProvider implementation sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Open an existing EPUB file. In the example, we use the OpenRead() method of System.IO.FileStream class to open and read an EPUB file from the file system at the specified path.Use known or custom ICreateStreamProvider interface implementation as output data buffer.Create a new ImageSaveOptions object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need to pass the EPUB inputStream, ImageSaveOptions, and output stream to the ConvertEPUB() method for EPUB to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters; 
...
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Define default ImageSaveOptions object instance
var options = new ImageSaveOptions(); 

// Initiate conversion process with default configuration object
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Convert epub source presented by URL to image. Result is image file formed by implementation of [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) interface.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. See ICreateStreamProvider implementation sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Open an existing EPUB file. In the example, we use the OpenRead() method of System.IO.FileStream class to open and read an EPUB file from the file system at the specified path.Use known or custom ICreateStreamProvider interface implementation as output data buffer.Create a new ImageSaveOptions object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need to pass the EPUB inputStream, ImageSaveOptions, and output stream to the ConvertEPUB() method for EPUB to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;
...
// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Create default options instance  
var options = new ImageSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, string) {#convertepub_31}

Convert epub source presented by input stream to xps. Result is xps file defined by full path.

```csharp
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. See Stream specification in [official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. |
| outputPath | String | Full .xps file path as output conversion result. |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;
using System.Drawing;
using Aspose.Html.Drawing;
...
  // Open an existing EPUB file for reading
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Prepare a path to save the converted file 
  string savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Create an instance of XpsSaveOptions. Set up the page-size and change the background color to LightGray 
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new Aspose.Html.Drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Call the ConvertEPUB method to convert EPUB to XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### See Also

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, XpsSaveOptions, string) {#convertepub_47}

Convert epub source presented by input EPUB file path to xps. Result is xps file defined by full path.

```csharp
public static void ConvertEPUB(string sourcePath, XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media type`](../../../aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full .xps file path as output conversion result. |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, [`XpsSaveOptions`](../../../aspose.html.saving/xpssaveoptions/), and output data buffer in any form to initiate conversion process.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.Saving;
using Aspose.Html.Converters;
...
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, string) {#convertepub_15}

Convert epub source presented by URL to xps file defined by full path. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```csharp
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media type`](../../../aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full .xps file path as output conversion result. |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process.

Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;
...
// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### See Also

* class [Url](../../../aspose.html/url/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, string) {#convertepub_23}

Convert epub source presented by input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) to xps. Result is xps file defined by full path.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media type`](../../../aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full .xps file path as output conversion result. |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;
...

// Open an existing EPUB file for reading
using var stream = File.OpenRead(DataDir + "input.epub");

// Prepare a path for converted file saving 
string savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Initialize XpsSaveOptions 
var options = new XpsSaveOptions();
   
// Call the ConvertEPUB method to convert EPUB to XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, XpsSaveOptions, string) {#convertepub_39}

Convert epub source presented by input EPUB file path to xps. Result is xps file defined by full path.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    XpsSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | Conversion options. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. |
| outputPath | String | Full .xps file path as output conversion result. |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.Saving;
using Aspose.Html.Converters;
...
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, XpsSaveOptions, string) {#convertepub_7}

Convert epub source presented by URL to xps file defined by full path. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | Conversion options. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. |
| outputPath | String | Full .xps file path as output conversion result. |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.Saving;
using Aspose.Html.Converters;
...
// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Convert epub source presented by input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) to xps. Result is xps output data defined by known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. See ICreateStreamProvider implementation sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html;
using System.Linq;
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...
 // Create an instance of MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Open an existing EPUB file for reading
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Prepare a path to save the converted file 
 string savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Convert EPUB to XPS by using the MemoryStreamProvider class
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Get access to the memory stream that contains the result data
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Flush the result data to the output file
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### See Also

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Convert epub source presented by input EPUB file path to xps. Result is xps output data defined by known or custom [`ICreateStreamProvider `](../../../aspose.html.io/icreatestreamprovider/)interface implementation.

```csharp
public static void ConvertEPUB(string sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| options | XpsSaveOptions | Conversion options. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. |
| provider | ICreateStreamProvider | Implementation of the interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;

// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Convert epub source presented by URL to xps file defined by full path. Result is xps output data defined by known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of the [`interface`](../../../aspose.html.io/icreatestreamprovider/), which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;

// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Convert epub source presented by input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) to xps. Result is xps output data defined by known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;

// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Convert epub source presented by input EPUB file path to xps. Result is xps output data defined by known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;

// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Convert epub source presented by URL to xps file defined by full path. Result is xps output data defined by known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | XpsSaveOptions | Conversion options. [`XpsSaveOptions `](../../../aspose.html.saving/xpssaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

### Remarks

How to convert EPUB to XPS

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter XPS specific guide, you find the following article:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convert EPUB to XPS

To convert EPUB to XPS file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path.Create a new XpsSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of XpsSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an xps file. You need to pass the EPUB source date, XpsSaveOptions, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to XPS converter

Aspose.HTML offers a free online [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to XPS file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters;

// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Create default options instance  
var options = new XpsSaveOptions();

// Initiate conversion process with default configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [XpsSaveOptions](../../../aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, DocSaveOptions, string) {#convertepub_25}

Convert EPUB source file presented by full path to DOCX. Result is docx file defined by full path.

```csharp
public static void ConvertEPUB(Stream stream, DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Conversion source presented by input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Conversion options. [`DocSaveOptions `](../../../aspose.html.saving/docsaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Full .docx file path as output conversion result. |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Create default options instance  
var options = new DocSaveOptions();   

// Initiate conversion process
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, DocSaveOptions, string) {#convertepub_41}

Convert EPUB source presented by full file path to DOCX. Result is docx file formed by output file path.

```csharp
public static void ConvertEPUB(string sourcePath, DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path as input parameter. |
| options | DocSaveOptions | Conversion options. [`DocSaveOptions `](../../../aspose.html.saving/docsaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Full .docx file path as output conversion result. |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Define default options instance
var options = new DocSaveOptions();

// Raise conversion process
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, string) {#convertepub_9}

Convert EPUB source presented by URL. Result is docx file formed by output file path.

```csharp
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`resolutions`](../../../aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Full .docx file path as output conversion result. |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Define default options instance
var options = new DocSaveOptions();

// Raise conversion process
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, string) {#convertepub_17}

Convert EPUB source presented by data input stream. Result is docx file formed by output file path.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | Conversion options. [`DocSaveOptions `](../../../aspose.html.saving/docsaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Full .docx file path as output conversion result. |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Create default options instance  
var options = new DocSaveOptions();   

// Initiate conversion process with default configuration 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, DocSaveOptions, string) {#convertepub_33}

Convert EPUB source presented by full file path to DOCX. Result is docx file formed by output file path.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    DocSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | Conversion options. [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Full .docx file path as output conversion result. |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Define default options instance
var options = new DocSaveOptions();

// Raise conversion process with default configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, DocSaveOptions, string) {#convertepub_1}

Convert EPUB source presented by URL. Result is docx file formed by output file path.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`resolutions`](../../../aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Full .docx file path as output conversion result. |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form conversion result file path
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Create default options instance  
var options = new DocSaveOptions();

// Initiate conversion process with default configuration  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Convert EPUB source as input stream to DOCX. Result is docx file formed by ICreateStreamProvider implementation.

```csharp
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| options | DocSaveOptions | Conversion options. [`DocSaveOptions `](../../../aspose.html.saving/docsaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Create default options instance  
var options = new DocSaveOptions();   

// Initiate conversion process
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Convert EPUB source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) implementation.

```csharp
public static void ConvertEPUB(string sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| options | DocSaveOptions | Conversion options. [`DocSaveOptions `](../../../aspose.html.saving/docsaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Create default options instance  
var options = new DocSaveOptions ();   

// Initiate conversion process  
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Convert EPUB source presented by URL. Result is output data formed by ICreateStreamProvider interface implementation.

```csharp
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) usage enables you to tune the rendering process; you can specify the page size, margins, resolutions, CSS, etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new DocSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Form source Url by input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Create default options instance  
var options = new DocSaveOptions ();   

// Initiate conversion process
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Convert EPUB source presented by data input stream. Result is output data formed by ICreateStreamProvider interface implementation.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`resolutions`](../../../aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Create default options instance  
var options = new DocSaveOptions();   

// Initiate conversion process with default configuration 
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Convert EPUB source presented by full file path to DOCX. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | Conversion options. [`DocSaveOptions `](../../../aspose.html.saving/docsaveoptions/)object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Create default options instance  
var options = new DocSaveOptions ();   

// Initiate conversion process  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Convert EPUB source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`resolutions`](../../../aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

### Remarks

How to convert EPUB to DOCX

DOCX is a well-known format for Microsoft Word documents. This format is popular because it supports a wide range of formatting features and offers users a variety of options to write any type of document. DOCX files can be opened with Word 2007 and lateral versions but not with the earlier versions of MS Word, which support DOC file extensions. EPUB to DOCX conversion is often required to take advantage of DOCX format for specific user tasks.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter DOCX specific guide, you find the following article:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to DOCX

To convert EPUB to DOCX file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new [`DocSaveOptions`](../../../aspose.html.saving/docsaveoptions/) object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of DocSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an docx file. You need to pass the EPUB source date as file path or input stream as well as Url, DocSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to DOCX converter

Aspose.HTML offers a free online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter that converts EPUB to DOCX file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Create default options instance  
var options = new DocSaveOptions();   

// Initiate conversion process with default configuration 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [DocSaveOptions](../../../aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, string) {#convertepub_29}

Convert EPUB source presented by data input stream. Result is pdf file formed by output file path.

```csharp
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | EPUB source file path as input parameter. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Full .pdf file path as output conversion result. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Form result file path  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Create default options instance  
var options = new PdfSaveOptions();   

// Initiate conversion process  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, PdfSaveOptions, string) {#convertepub_45}

Convert EPUB source presented by full file path to PDF. Result is pdf file formed by output file path.

```csharp
public static void ConvertEPUB(string sourcePath, PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Full .pdf file path as output conversion result. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Define default options instance
var options = new PdfSaveOptions();

// Raise conversion process
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, string) {#convertepub_13}

Convert EPUB source presented by URL. Result is pdf file formed by output file path.

```csharp
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`file permissions`](../../../aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Full .pdf file path as output conversion result. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters; 

// Create Url based on input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Define default options instance
var options = new Aspose.Html.Saving.PdfSaveOptions();

// Raise conversion process
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, string) {#convertepub_21}

Convert EPUB source presented by data input stream. Result is pdf file formed by output file path.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Full .pdf file path as output conversion result. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Form result file path  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Create default options instance  
var options = new PdfSaveOptions();   

// Initiate conversion process with default configuration 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, PdfSaveOptions, string) {#convertepub_37}

Convert EPUB source presented by data input stream. Result is pdf file formed by output file path.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    PdfSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Full .pdf file path as output conversion result. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;
using Aspose.Html.Saving;  
using Aspose.Html.Converters; 
...
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Define default options instance
var options = new PdfSaveOptions();

// Raise conversion process with default configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, string) {#convertepub_5}

Convert EPUB source presented by URL. Result is pdf file formed by output file path.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`file permissions`](../../../aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Full .pdf file path as output conversion result. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Define default options instance
var options = new PdfSaveOptions();

// Raise conversion process with default configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Convert EPUB source presented by data input stream. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Known (see [`FileCreateStreamProvider`](../../../aspose.html.io/filecreatestreamprovider/)) or custom [`ICreateStreamP﻿rovider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation. |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Create default options instance  
var options = new PdfSaveOptions ();   

// Initiate conversion process  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Convert EPUB source presented by full file path to PDF. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(string sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Create default options instance  
var options = new PdfSaveOptions();   

// Initiate conversion process  
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Convert EPUB source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`file permissions`](../../../aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Define default options instance
var options = new PdfSaveOptions();

// Initiate conversion process
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Convert EPUB source presented by data input stream. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | Conversion options. [`PdfSaveOption`](../../../aspose.html.saving/pdfsaveoptions/) object usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The [`Aspose.Html.Converters`](../) namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Create default options instance  
var options = new PdfSaveOptions ();   

// Initiate conversion process with default configuration object  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Convert EPUB source presented by full file path to PDF. Result is output data formed by ICreateStreamProvider interface implementation.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | Conversion options. [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) object usage enables you to tune the rendering process; you can specify the page size, margins, CSS, etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Create default options instance  
var options = new PdfSaveOptions();   

// Initiate conversion process with default configuration object 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Convert EPUB source presented by URL. Result is output data formed by [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) usage enables you to tune the rendering process; you can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`file permissions`](../../../aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementation of [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

### Remarks

How to convert EPUB to PDF

EPUB is an e-book file format that provides a standard digital publication format. It is created by International Digital Publishing Forum ([IDPF](http://idpf.org/)), and now it is supported by many e-readers and software applications. EPUB to PDF conversion is often required to take advantage of PDF format. PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, metadata, etc. PDF files can be opened in Adobe Acrobat Reader/Writer and most modern browsers like Chrome, Safari, Firefox. They are optimized for printing, and they are ideal for creating physical copies of your documents; you can also configure the security settings for PDF.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a [`Converter`](../) class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter PDF specific guide, you find the following article:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) parameters.

Convert EPUB to PDF

To convert EPUB to PDF file format, you should follow a few steps:

Open an existing EPUB file. For an example, we can define source file path as first parameter of ConvertEPUB method. As an alternative we can use input stream or Url object instance.Use known or custom ICreateStreamProvider interface implementation as output data buffer. We can use more simple alternative as result output file path also.Create a new PdfSaveOptions object with numbers of preffered parameters like page size, margins, CSS and etc. It is possible to use default instance of PdfSaveOptions class.Use the ConvertEPUB() method of static Converter class to save EPUB as an pdf file. You need to pass the EPUB source date as file path or input stream as well as Url, PdfSaveOptions instance, and output data buffer in any form to initiate conversion process. You can use configuration which represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application.Online EPUB to PDF converter

Aspose.HTML offers a free online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter that converts EPUB to PDF file with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters; 
...
// Create Url based on input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Define default options instance
var options = new PdfSaveOptions();

// Initiate conversion process with default configuration object
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [PdfSaveOptions](../../../aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, ImageSaveOptions, string) {#convertepub_27}

Convert EPUB source presented by data input stream. Result is file formed by output file path.

```csharp
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| options | ImageSaveOptions | New formed image options as format, resolution and etc. See [`ImageSaveOptions `](../../../aspose.html.saving/imagesaveoptions/)class and [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Define Url based on existing EPUB file at the specified path.Define result output file path.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need also pass ImageSaveOptions and Configuration object to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
...
// Open existing file for reading as stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Define output file path
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Define default options instance
var options = new ImageSaveOptions();

// Initiate conversion process
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, ImageSaveOptions, string) {#convertepub_43}

Convert EPUB source presented by full file path. Result is image file formed by output file path. Image format is specified by ImageSaveOptions object.

```csharp
public static void ConvertEPUB(string sourcePath, ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path as input parameter. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Define Url based on existing EPUB file at the specified path.Define result output file path.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need also pass ImageSaveOptions and Configuration object to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters; 
...
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Define default ImageSaveOptions object instance
var options = new ImageSaveOptions(); 

// Initiate conversion process
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### See Also

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, string) {#convertepub_11}

Convert EPUB source defined by URL. Result is image file formed by output file path. Image format is specified by ImageSaveOptions object.

```csharp
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [`ImageSaveOptions `](../../../aspose.html.saving/imagesaveoptions/)class. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Define Url based on existing EPUB file at the specified path.Define result output file path.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need also pass ImageSaveOptions and Configuration object to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
...
// Create Url based on input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Define default options instance
var options = new ImageSaveOptions();

// Initiate conversion process
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### See Also

* class [Url](../../../aspose.html/url/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, string) {#convertepub_19}

Convert EPUB source presented by data input stream. Result is image file formed by output file path. Image format is specified by ImageSaveOptions object.

```csharp
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Define Url based on existing EPUB file at the specified path.Define result output file path.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need also pass ImageSaveOptions and Configuration object to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
...
// Open existing file for reading as stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Define output file path
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Define default options instance
var options = new ImageSaveOptions();

// Initiate conversion process with default configuration object
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(string, Configuration, ImageSaveOptions, string) {#convertepub_35}

Convert EPUB source presented by full file path. Result is image file formed by output file path. Image format is specified by ImageSaveOptions object.

```csharp
public static void ConvertEPUB(string sourcePath, Configuration configuration, 
    ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | EPUB source file path as input parameter. |
| configuration | Configuration | The environment configuration. Represents the [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [`ImageSaveOptions `](../../../aspose.html.saving/imagesaveoptions/)class. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Define Url based on existing EPUB file at the specified path.Define result output file path.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need also pass ImageSaveOptions and Configuration object to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters; 
...
// Form source file path
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Form output result file path
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Define default ImageSaveOptions object instance
var options = new ImageSaveOptions(); 

// Initiate conversion process with default configuration object
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../aspose.html/configuration/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, ImageSaveOptions, string) {#convertepub_3}

Convert EPUB source defined by URL. Result is image file formed by output file path. Image format is specified by ImageSaveOptions object.

```csharp
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | EPUB source URL - provides an object representation of a universal identifier (URL). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), etc. See [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)class. |
| outputPath | String | Full image file path as output conversion result. |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Define Url based on existing EPUB file at the specified path.Define result output file path.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need also pass ImageSaveOptions and Configuration object to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO;  
using Aspose.Html.Saving;  
using Aspose.Html.Converters;  
...
// Create Url based on input file path
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Define output file path
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Define default options instance
var options = new ImageSaveOptions(); 

// Initiate conversion process with default configuration object
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../aspose.html/url/)
* class [Configuration](../../../aspose.html/configuration/)
* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Convert epub source presented by input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) to image. Result is image file formed by implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface.

```csharp
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Input stream as conversion source. |
| options | ImageSaveOptions | ImageSaveOptions object usage enables you to tune the rendering process. You can specify the [`page size`](../../../aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../aspose.html.drawing/page/margin/), [`CSS media-type`](../../../aspose.html.rendering/mediatype/), etc. See [`ImageSaveOptions `](../../../aspose.html.saving/imagesaveoptions/)class. |
| provider | ICreateStreamProvider | Implementation of [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface, which will be used to get an output stream. See advanced sample in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

### Remarks

How to convert EPUB to Image

EPUB is an e-book file format that provides a standard digital publication format. It was created by International Digital Publishing Forum (IDPF), and now it is supported by many e-readers and software applications.

Converting EPUB files to the PNG format can be helpful if you need to include files in a PowerPoint presentation or send them by email. Please convert them to the image format and use them as you want! You can use additional conversion parameters for the desired result obtaining.

The main highlight of Aspose.HTML is the conversion feature. EPUB is an open XML-based format for digital books and publications, which can be view and read on smartphones, tablets and computers. The Aspose.Html.Converters namespace implements easy access to conversion methods. It provides a wide range of [EPUB](https://docs.fileformat.com/ebook/epub/) conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), and [GIF](https://docs.fileformat.com/image/gif/).

This section provides information on the list of supported EPUB conversion scenarios and how to perform them using a Converter class that groups all low-level conversion operations in a single class to make them comfy and easy to use. In the EPUB Converter guide, you find the following articles:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convert EPUB to Image

To convert EPUB to Image file format, you should follow a few steps:

Open an existing EPUB file. In the example, we use the OpenRead() method of System.IO.FileStream class to open and read an EPUB file from the file system at the specified path.Use known or custom [`ICreateStreamProvider`](../../../aspose.html.io/icreatestreamprovider/) interface implementation as output data buffer.Create a new [`ImageSaveOptions`](../../../aspose.html.saving/imagesaveoptions/) object with required ImageFormat. By default, the Format property is PNG.Use the ConvertEPUB() method of the Converter class to save EPUB as an image. You need to pass the EPUB inputStream, ImageSaveOptions, and output stream to the ConvertEPUB() method for EPUB to Image conversion.Online EPUB converters

Aspose.HTML offers a free online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter that converts EPUB to PNG image with high quality, easy and fast. Just upload, convert your files and get results in a few seconds!

You may also be interested in specific image format conversion

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Source code

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

```csharp
using System.IO; 
using Aspose.Html.IO; 
using Aspose.Html.Saving; 
using Aspose.Html.Converters; 
...  
// Open existing file for reading as stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Refer to ICreateStreamProvider interface implementation  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Create default options instance  
var options = new ImageSaveOptions();    

// Initiate conversion process  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### See Also

* class [ImageSaveOptions](../../../aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* namespace [Aspose.Html.Converters](../../converter/)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
