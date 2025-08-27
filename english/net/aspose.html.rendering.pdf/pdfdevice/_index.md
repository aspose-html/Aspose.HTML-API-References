---
title: PdfDevice Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Pdf.PdfDevice class. Represents rendering to a pdf document
type: docs
weight: 4660
url: /net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Represents rendering to a pdf document.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(*[ICreateStreamProvider](../../aspose.html.io/icreatestreamprovider/)*) | Initializes a new instance of the `PdfDevice` class. |
| [PdfDevice](pdfdevice/#constructor_4)(*Stream*) | Initializes a new instance of the `PdfDevice` class. |
| [PdfDevice](pdfdevice/#constructor_5)(*string*) | Initializes a new instance of the `PdfDevice` class. |
| [PdfDevice](pdfdevice/#constructor_1)(*[PdfRenderingOptions](../pdfrenderingoptions/), [ICreateStreamProvider](../../aspose.html.io/icreatestreamprovider/)*) | Initializes a new instance of the `PdfDevice` class by rendering options and stream provider. |
| [PdfDevice](pdfdevice/#constructor_2)(*[PdfRenderingOptions](../pdfrenderingoptions/), Stream*) | Initializes a new instance of the `PdfDevice` class by rendering options and output stream. |
| [PdfDevice](pdfdevice/#constructor_3)(*[PdfRenderingOptions](../pdfrenderingoptions/), string*) | Initializes a new instance of the `PdfDevice` class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |
| virtual [Configuration](../../aspose.html.rendering/device-2/configuration/) { get; } |  |
| [OutputStream](../../aspose.html.rendering/device-2/outputstream/) { get; } |  |
| [StreamProvider](../../aspose.html.rendering/device-2/streamprovider/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddRect](../../aspose.html.rendering/device-2/addrect/)(*RectangleF*) |  |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(*[Document](../../aspose.html.dom/document/)*) |  |
| virtual [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(*[Element](../../aspose.html.dom/element/), RectangleF*) |  |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(*SizeF*) |  |
| virtual [Clip](../../aspose.html.rendering/device-2/clip/)(*[FillRule](../../aspose.html.rendering/fillrule/)*) |  |
| virtual [ClosePath](../../aspose.html.rendering/device-2/closepath/)() |  |
| virtual [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) |  |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| virtual [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.html.drawing/webimageformat/), RectangleF*) |  |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| virtual [EndElement](../../aspose.html.rendering/device-2/endelement/)(*[Element](../../aspose.html.dom/element/)*) |  |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() |  |
| virtual [Fill](../../aspose.html.rendering/device-2/fill/)(*[FillRule](../../aspose.html.rendering/fillrule/)*) |  |
| virtual [FillText](../../aspose.html.rendering/device-2/filltext/)(*string, PointF*) |  |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() |  |
| virtual [LineTo](../../aspose.html.rendering/device-2/lineto/)(*PointF*) |  |
| virtual [MoveTo](../../aspose.html.rendering/device-2/moveto/)(*PointF*) |  |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| virtual [Stroke](../../aspose.html.rendering/device-2/stroke/)() |  |
| virtual [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.html.rendering/fillrule/)*) |  |
| virtual [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(*string, PointF*) |  |

## Other Members

| Name | Description |
| --- | --- |
| class [PdfGraphicContext](../../aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Holds current graphics control parameters for the PdfDevice. These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* namespace [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* assembly [Aspose.HTML](../../)
