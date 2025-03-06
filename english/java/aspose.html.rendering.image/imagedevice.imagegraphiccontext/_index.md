---
title: ImageDevice.ImageGraphicContext Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.image.ImageDeviceImageGraphicContext class. Holds current graphics control parameters for the ImageDevice. These parameters define the global framework within which the graphics operators execute
type: docs

url: /java/com.aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Holds current graphics control parameters for the [`ImageDevice`](../imagedevice/). These parameters define the global framework within which the graphics operators execute.

```java
public class ImageGraphicContext : GraphicContext
```

## Constructors

| Name | Description |
| --- | --- |
| [imageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Sets or gets character spacing. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Sets or gets the brush object that is used to fill the interiors of paths. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Sets or gets the true type font object that is used for rendering text. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Sets or gets text font size. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Sets or gets text font style. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Sets or gets the code specifying the shape of the endpoints for any open path that is stroked. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Sets or gets the phase offset of the current line dash pattern. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Sets or gets the description of the dash pattern to be used when paths are stroked. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Sets or gets the code specifying the shape of joints between connected segments of a stroked path. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Sets or gets the thickness of paths to be stroked. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Sets or gets the maximum length of mitered line joins for stroked paths. This parameter limits the length of "spikes" produced when line segments join at sharp angles. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Sets or gets the brush object that is used for stroked paths. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Gets a [`TextInfo`](../../com.aspose.html.rendering/textinfo/) object which contains information about rendered text. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Sets or gets transformation matrix. |

## Methods

| Name | Description |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Creates a new instance of a GraphicContext class with the same property values as an existing instance. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Modify the current transformation matrix by multiplying the specified matrix. |

### See Also

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
