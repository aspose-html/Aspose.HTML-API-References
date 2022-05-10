---
title: PdfDevice.PdfGraphicContext
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 4520
url: /net/aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Holds current graphics control parameters for the PdfDevice. These parameters define the global framework within which the graphics operators execute.

```csharp
public class PdfGraphicContext : GraphicContext
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfGraphicContext](pdfgraphiccontext)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [FillBrush](fillbrush) { get; set; } | Sets or gets the brush object that is used to fill the interiors of paths. |
| override [LineCap](linecap) { get; set; } | Sets or gets the code specifying the shape of the endpoints for any open path that is stroked. |
| override [LineJoin](linejoin) { get; set; } | Sets or gets the code specifying the shape of joints between connected segments of a stroked path. |
| override [LineWidth](linewidth) { get; set; } | Sets or gets the thickness of paths to be stroked. |
| override [MiterLimit](miterlimit) { get; set; } | Sets or gets the maximum length of mitered line joins for stroked paths. This parameter limits the length of "spikes" produced when line segments join at sharp angles. |
| override [StrokeBrush](strokebrush) { get; set; } | Sets or gets the brush object that is used for stroked paths. |
| override [TransformationMatrix](transformationmatrix) { get; set; } | Sets or gets transformation matrix. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](clone)() | Creates a new instance of a class with the same property values as an existing instance. |
| override [Transform](transform)(Matrix) | Modify the current transformation matrix by multiplying the specified matrix. |

### See Also

* class [GraphicContext](../../aspose.html.rendering/graphiccontext)
* class [PdfDevice](../pdfdevice)
* namespace [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->