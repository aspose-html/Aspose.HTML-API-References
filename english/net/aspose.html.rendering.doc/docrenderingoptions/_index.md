---
title: DocRenderingOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Doc.DocRenderingOptions class. Represents the rendering options for DocDevice
type: docs
weight: 4390
url: /net/aspose.html.rendering.doc/docrenderingoptions/
---
## DocRenderingOptions class

Represents the rendering options for [`DocDevice`](../docdevice/).

```csharp
public class DocRenderingOptions : RenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DocRenderingOptions](docrenderingoptions/#constructor)() | Initializes a new instance of the `DocRenderingOptions` class. |
| [DocRenderingOptions](docrenderingoptions/#constructor_1)(FontEmbeddingRule) | Initializes a new instance of the `DocRenderingOptions` class with the specified font embedding rule. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Gets a [`CssOptions`](../../aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [DocumentFormat](../../aspose.html.rendering.doc/docrenderingoptions/documentformat/) { get; set; } | Gets or sets the file format of the output document. The default value is DOCX. |
| [FontEmbeddingRule](../../aspose.html.rendering.doc/docrenderingoptions/fontembeddingrule/) { get; set; } | Gets or sets the font embedding rule. The default value is None. |
| virtual [HorizontalResolution](../../aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Gets a page setup object is used for configuration output page-set. |
| virtual [VerticalResolution](../../aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

### See Also

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* namespace [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* assembly [Aspose.HTML](../../)
