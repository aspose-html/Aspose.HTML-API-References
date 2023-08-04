---
title: PdfDevice.PdfGraphicContext Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Rendering.Pdf.PdfDevicePdfGraphicContext class. Holds current graphics control parameters for the PdfDevice. These parameters define the global framework within which the graphics operators execute
type: docs
weight: 4480
url: /java/com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Holds current graphics control parameters for the PdfDevice. These parameters define the global framework within which the graphics operators execute.

```java
public class PdfGraphicContext : GraphicContext
```

## Constructors

| Name | Description |
| --- | --- |
| [pdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
[getCharacterSpacing]
[setCharacterSpacing] Sets or gets character spacing. |
[getFillBrush]
[setFillBrush] Sets or gets the brush object that is used to fill the interiors of paths. |
[getFont]
[setFont] Sets or gets the true type font object that is used for rendering text. |
[getFontSize]
[setFontSize] Sets or gets text font size. |
[getFontStyle]
[setFontStyle] Sets or gets text font style. |
[getLineCap]
[setLineCap] Sets or gets the code specifying the shape of the endpoints for any open path that is stroked. |
[getLineDashOffset]
[setLineDashOffset] Sets or gets the phase offset of the current line dash pattern. |
[getLineDashPattern]
[setLineDashPattern] Sets or gets the description of the dash pattern to be used when paths are stroked. |
[getLineDashStyle]
[setLineDashStyle] Sets of gets the style of dashed lines of a stroked path. |
[getLineJoin]
[setLineJoin] Sets or gets the code specifying the shape of joints between connected segments of a stroked path. |
[getLineWidth]
[setLineWidth] Sets or gets the thickness of paths to be stroked. |
[getMiterLimit]
[setMiterLimit] Sets or gets the maximum length of mitered line joins for stroked paths. This parameter limits the length of "spikes" produced when line segments join at sharp angles. |
[getStrokeBrush]
[setStrokeBrush] Sets or gets the brush object that is used for stroked paths. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Gets a [`TextInfo`](../../com.aspose.html.rendering/textinfo/) object which contains information about rendered text. |
[getTransformationMatrix]
[setTransformationMatrix] Sets or gets transformation matrix. |

## Methods

| Name | Description |
| --- | --- |
| [clone](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/clone)() | Creates a new instance of a class with the same property values as an existing instance. |
| [transform](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/transform)(Matrix) | Modify the current transformation matrix by multiplying the specified matrix. |

### See Also

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* package [com.aspose.html.Rendering.Pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
