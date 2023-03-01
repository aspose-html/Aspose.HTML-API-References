---
title: Class PdfDevice
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.Pdf.PdfDevice klass. Representerar rendering till ett pdfdokument.
type: docs
weight: 4440
url: /sv/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Representerar rendering till ett pdf-dokument.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Initierar en ny instans av`PdfDevice` class. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Initierar en ny instans av`PdfDevice` class. |
| [PdfDevice](pdfdevice/#constructor_5)(string) | Initierar en ny instans av`PdfDevice` class. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Initierar en ny instans av`PdfDevice` klass genom renderingsalternativ och strömleverantör. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Initierar en ny instans av`PdfDevice`klass genom att rendera alternativ och utdataström. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, string) | Initierar en ny instans av`PdfDevice` klass genom att rendera alternativ och utdatafilnamn. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect/)(RectangleF) | Lägger till en rektangel till den aktuella sökvägen som en komplett undersökväg. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument/)(Document) | Börjar renderingen av dokumentet. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement/)(Element, RectangleF) | Börjar rendering av elementet. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage/)(SizeF) | Börjar renderingen av den nya sidan. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip/)(FillMode) | Modifierar den aktuella urklippsbanan genom att skära den med den aktuella sökvägen, med hjälp av FillMode-regeln för att bestämma regionen som ska fyllas. Den här metoden avslutar aktuell väg. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath/)() | Stänger den aktuella delvägen genom att lägga till ett rakt linjesegment från den aktuella punkten till startpunkten för delvägen. Om den aktuella undersökvägen redan är stängd, gör "ClosePath" ingenting. Denna operatör avslutar den aktuella undersökvägen. Genom att lägga till ett annat segment till den aktuella sökvägen börjar en ny undersökväg, även om det nya segmentet börjar vid den slutpunkt som nås med "ClosePath"-metoden. |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto/)(PointF, PointF, PointF) | Lägger till en kubisk Bézier-kurva till den aktuella sökvägen. Kurvan sträcker sig från den aktuella punkten till punkten pt2, med pt1 och pt2 som Bézier-kontrollpunkter. Den nya aktuella punkten är pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage/)(byte[], ImageType, RectangleF) | Ritar den angivna bilden. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument/)() | Avslutar renderingen av dokumentet. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement/)(Element) | Avslutar renderingen av elementet. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage/)() | Avslutar renderingen av den aktuella sidan. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill/)(FillMode) | Fyller hela området som omges av den aktuella sökvägen. Om sökvägen består av flera frånkopplade undersökvägar, fyller den insidan av alla undersökvägar, betraktat tillsammans. Den här metoden avslutar aktuell väg. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext/)(string, PointF) | Fyller den angivna textsträngen på den angivna platsen. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush/)() | Rensar all data till utdataström. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto/)(PointF) | Lägger till ett rakt linjesegment från den aktuella punkten till punkten (pt). Den nya nuvarande punkten är pt. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto/)(PointF) | Börjar en ny undersökväg genom att flytta den aktuella punkten till koordinaterna för parametern pt, och utelämnar alla anslutande linjesegment. Om den tidigare vägkonstruktionsmetoden i den aktuella sökvägen också var "MoveTo", åsidosätter den nya "MoveTo" den; ingen rest av den tidigare "MoveTo"-operationen finns kvar i sökvägen. |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext/)() | Återställer hela grafikkontexten till dess tidigare värde genom att poppa den från stacken. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext/)() | Skickar en kopia av hela grafikkontexten till stacken. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke/)() | Stryker en linje längs den aktuella banan. Den streckade linjen följer varje rakt eller krökt segment i banan, centrerat på segmentet med sidor parallella med det. Var och en av sökvägens undervägar behandlas separat. Den här metoden avslutar aktuell väg. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill/)(FillMode) | Stryker och fyller strömvägen. Denna metod avslutar strömvägen. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext/)(string, PointF) | Stryker den angivna textsträngen på den angivna platsen. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext/) | Innehåller aktuella grafikkontrollparametrar för PdfDevice. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna exekverar. |

### Se även

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* namnutrymme [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* hopsättning [Aspose.HTML](../../)


