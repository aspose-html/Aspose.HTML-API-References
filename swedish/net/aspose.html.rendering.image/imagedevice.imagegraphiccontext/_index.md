---
title: Class ImageDevice.ImageGraphicContext
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.Image.ImageDeviceImageGraphicContext klass. Innehåller aktuella grafikkontrollparametrar förImageDevice . Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna kör.
type: docs
weight: 4310
url: /sv/net/aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Innehåller aktuella grafikkontrollparametrar för[`ImageDevice`](../imagedevice/) . Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna kör.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageGraphicContext](imagegraphiccontext/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Ställer in eller får teckenavstånd. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Ställer in eller hämtar penselobjektet som används för att fylla banornas inre. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Ställer in eller hämtar True Type-teckensnittsobjektet som används för att rendera text. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Ställer in eller hämtar teckenstorlek för text. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Ställer in eller hämtar texttypsnittsstil. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Ställer in eller hämtar koden som anger formen på ändpunkterna för en öppen bana som ströks. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Ställer in eller hämtar fasförskjutningen av det aktuella linjestreckmönstret. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Ställer in eller hämtar beskrivningen av streckmönstret som ska användas när banor ströks. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Uppsättningar av får stilen för streckade linjer i en streckad bana. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Ställer in eller hämtar koden som anger formen på fogar mellan anslutna segment av en streckad bana. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Ställer in eller hämtar tjockleken på banorna som ska sträckas. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Ställer in eller hämtar den maximala längden på geringslinjer för streckade banor. Den här parametern begränsar längden på "spikar" som produceras när linjesegment förenas i skarpa vinklar. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Ställer in eller hämtar penselobjektet som används för streckade banor. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Får en[`TextInfo`](../../aspose.html.rendering/textinfo/) objekt som innehåller information om renderad text. |
| override [TransformationMatrix](../../aspose.html.rendering.image/imagegraphiccontext/transformationmatrix/) { get; set; } | Ställer in eller hämtar transformationsmatris. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.html.rendering.image/imagegraphiccontext/clone/)() | Skapar en ny instans av en GdiGraphicContext-klass med samma egenskapsvärden som en befintlig instans. |
| override [Transform](../../aspose.html.rendering.image/imagegraphiccontext/transform/)(Matrix) | Ändra den aktuella transformationsmatrisen genom att multiplicera den angivna matrisen. |

### Se även

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* namnutrymme [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* hopsättning [Aspose.HTML](../../)


