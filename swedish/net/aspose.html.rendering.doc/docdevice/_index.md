---
title: Class DocDevice
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.Doc.DocDevice klass. Representerar rendering till ett DOCXdokument.
type: docs
weight: 4170
url: /sv/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Representerar rendering till ett DOCX-dokument.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av`DocDevice` class. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initierar en ny instans av`DocDevice` klass efter utgångsström. |
| [DocDevice](docdevice/#constructor_5)(string) | Initierar en ny instans av`DocDevice` klass efter utdatafilnamn. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av`DocDevice` klass genom renderingsalternativ och strömleverantör. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initierar en ny instans av`DocDevice` klass genom att rendera alternativ och utdataström. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Initierar en ny instans av`DocDevice` klass genom att rendera alternativ och utdatafilnamn. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella sökvägen som en komplett undersökväg. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Börjar renderingen av dokumentet. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Börjar rendering av html-noden. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Börjar renderingen av den nya sidan. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Modifierar den aktuella urklippsbanan genom att skära den med den aktuella sökvägen, med hjälp av FillMode-regeln för att bestämma regionen som ska fyllas. Den här metoden avslutar aktuell väg. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Stänger den aktuella delvägen genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delvägen. Om den aktuella undersökvägen redan är stängd, gör "ClosePath" ingenting. Denna operatör avslutar den aktuella undersökvägen. Genom att lägga till ett annat segment till den aktuella sökvägen börjar en ny undersökväg, även om det nya segmentet börjar vid den slutpunkt som nås med "ClosePath"-metoden. |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier-kurva till den aktuella sökvägen. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Ritar den angivna bilden. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Avslutar renderingen av html-noden. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Avslutar renderingen av den aktuella sidan. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Fyller hela området som omges av den aktuella sökvägen. Om sökvägen består av flera frånkopplade undersökvägar, fyller den insidan av alla undersökvägar, betraktat tillsammans. Den här metoden avslutar aktuell väg. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Rensar all data till utdataström. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya nuvarande punkten är pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Börjar en ny undersökväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, och utelämnar alla anslutande linjesegment. Om den tidigare vägkonstruktionsmetoden i den aktuella sökvägen också var "MoveTo", åsidosätter den nya "MoveTo" den; ingen rest av den tidigare "MoveTo"-operationen finns kvar i sökvägen. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Skickar en kopia av hela grafikkontexten till stacken. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Stryker en linje längs den aktuella banan. Den streckade linjen följer varje rakt eller krökt segment i banan, centrerat på segmentet med sidor parallella med det. Var och en av sökvägens undervägar behandlas separat. Den här metoden avslutar aktuell väg. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Stryker och fyller strömvägen. Denna metod avslutar strömvägen. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Stryker den angivna textsträngen på den angivna platsen. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Innehåller aktuella grafikkontrollparametrar för DocDevice. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna exekverar. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* namnutrymme [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* hopsättning [Aspose.HTML](../../)


