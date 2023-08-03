---
title: GraphicContext Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Rendering.GraphicContext class. Holds current graphics control parameters. These parameters define the global framework within which the graphics operators execute
type: docs
weight: 4290
url: /net/com.aspose.html.rendering/graphiccontext/
---
## GraphicContext class

Holds current graphics control parameters. These parameters define the global framework within which the graphics operators execute.

```java
public class GraphicContext : ICloneable
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicContext](graphiccontext/)() | Initializes a new instance of the `GraphicContext` class. |

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
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Gets a [`TextInfo`](../textinfo/) object which contains information about rendered text. |
[getTransformationMatrix]
[setTransformationMatrix] Sets or gets transformation matrix. |

## Methods

| Name | Description |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Creates a new instance of a GraphicContext class with the same property values as an existing instance. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(Matrix) | Modify the current transformation matrix by multiplying the specified matrix. |

### See Also

* package [com.aspose.html.Rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
