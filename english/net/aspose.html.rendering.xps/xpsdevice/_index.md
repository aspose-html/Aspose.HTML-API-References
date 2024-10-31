---
title: XpsDevice Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Xps.XpsDevice class. Represents rendering to a xps document
type: docs
weight: 4760
url: /net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Represents rendering to a xps document.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initializes a new instance of the `XpsDevice` class. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initializes a new instance of the `XpsDevice` class. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Initializes a new instance of the `XpsDevice` class. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initializes a new instance of the `XpsDevice` class by rendering options and stream provider. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initializes a new instance of the `XpsDevice` class by rendering options and output stream. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Initializes a new instance of the `XpsDevice` class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) |  |
| virtual [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| virtual [Clip](../../aspose.html.rendering/device-2/clip/)(FillRule) |  |
| virtual [ClosePath](../../aspose.html.rendering/device-2/closepath/)() |  |
| virtual [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| virtual [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| virtual [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) |  |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() |  |
| virtual [Fill](../../aspose.html.rendering/device-2/fill/)(FillRule) |  |
| virtual [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) |  |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() |  |
| virtual [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) |  |
| virtual [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) |  |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| virtual [Stroke](../../aspose.html.rendering/device-2/stroke/)() |  |
| virtual [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| virtual [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) |  |

## Other Members

| Name | Description |
| --- | --- |
| class [XpsGraphicContext](../../aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Holds current graphics control parameters for the XpsDevice. These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* namespace [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps/)
* assembly [Aspose.HTML](../../)
