---
title: Class ImageDevice
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.Image.ImageDevice klass. Representerar rendering till rasterformat jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /sv/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Representerar rendering till rasterformat: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av`ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Initierar en ny instans av`ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Initierar en ny instans av`ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av`ImageDevice` klass genom renderingsalternativ och strömleverantör. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Initierar en ny instans av`ImageDevice`klass genom att rendera alternativ och utdataström. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Initierar en ny instans av`ImageDevice` klass genom att rendera alternativ och utdatafilnamn. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Hämtar instansen Graphics. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella sökvägen som en komplett undersökväg. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Börjar renderingen av dokumentet. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Börjar rendering av elementet. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Börjar renderingen av den nya sidan. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Modifierar den aktuella urklippsbanan genom att skära den med den aktuella sökvägen, med hjälp av FillMode-regeln för att bestämma regionen som ska fyllas. Den här metoden avslutar aktuell väg. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Stänger den aktuella delvägen genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delvägen. Om den aktuella undersökvägen redan är stängd, gör "ClosePath" ingenting. Denna operatör avslutar den aktuella undersökvägen. Genom att lägga till ett annat segment till den aktuella sökvägen börjar en ny undersökväg, även om det nya segmentet börjar vid den slutpunkt som nås med "ClosePath"-metoden. |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier-kurva till den aktuella sökvägen. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Ritar den angivna bilden. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Avslutar renderingen av dokumentet. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Avslutar renderingen av elementet. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Avslutar renderingen av den aktuella sidan. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Fyller hela området som omges av den aktuella sökvägen. Om sökvägen består av flera frånkopplade undersökvägar, fyller den insidan av alla undersökvägar, betraktat tillsammans. Den här metoden avslutar aktuell väg. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Rensar all data till utdataström. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya nuvarande punkten är pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Börjar en ny undersökväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, och utelämnar alla anslutande linjesegment. Om den tidigare vägkonstruktionsmetoden i den aktuella sökvägen också var "MoveTo", åsidosätter den nya "MoveTo" den; ingen rest av den tidigare "MoveTo"-operationen finns kvar i sökvägen. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Skickar en kopia av hela grafikkontexten till stacken. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Stryker en linje längs den aktuella banan. Den streckade linjen följer varje rakt eller krökt segment i banan, centrerat på segmentet med sidor parallella med det. Var och en av sökvägens undervägar behandlas separat. Den här metoden avslutar aktuell väg. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Stryker och fyller strömvägen. Denna metod avslutar strömvägen. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Stryker den angivna textsträngen på den angivna platsen. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | Innehåller aktuella grafikkontrollparametrar för`ImageDevice` . Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna kör. |

### Se även

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* namnutrymme [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* hopsättning [Aspose.HTML](../../)


