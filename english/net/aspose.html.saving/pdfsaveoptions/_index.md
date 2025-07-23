---
title: PdfSaveOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.PdfSaveOptions class. Specific options data class
type: docs
weight: 4880
url: /net/aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Specific options data class.

```csharp
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Gets a [`CssOptions`](../../aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [DocumentInfo](../../aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) { get; } | Contains information about the output PDF document. |
| [Encryption](../../aspose.html.rendering.pdf/pdfrenderingoptions/encryption/) { get; set; } | Gets or sets a encryption details. If not set, then no encryption will be performed. |
| [FormFieldBehaviour](../../aspose.html.rendering.pdf/pdfrenderingoptions/formfieldbehaviour/) { get; set; } | Specifies the behavior of form fields in the output PDF document. |
| virtual [HorizontalResolution](../../aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [IsTaggedPdf](../../aspose.html.rendering.pdf/pdfrenderingoptions/istaggedpdf/) { get; set; } | Creates a tag structure if `true`. |
| [JpegQuality](../../aspose.html.rendering.pdf/pdfrenderingoptions/jpegquality/) { get; set; } | Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Gets a page setup object is used for configuration output page-set. |
| virtual [VerticalResolution](../../aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

### See Also

* class [PdfRenderingOptions](../../aspose.html.rendering.pdf/pdfrenderingoptions/)
* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
