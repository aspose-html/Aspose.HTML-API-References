---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D koppel. De ICanvasRenderingContext2Dinterface wordt gebruikt voor het tekenen van rechthoeken tekst afbeeldingen en andere objecten op het canvaselement. Het biedt de 2Drenderingcontext voor het tekenoppervlak van een canvaselement.
type: docs
weight: 260
url: /nl/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

De ICanvasRenderingContext2D-interface wordt gebruikt voor het tekenen van rechthoeken, tekst, afbeeldingen en andere objecten op het canvaselement. Het biedt de 2D-renderingcontext voor het tekenoppervlak van een canvaselement.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Een alleen-lezen terugverwijzing naar het HTMLCanvasElement. Kan null zijn als het niet is gekoppeld aan een canvaselement. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Kleur of stijl om binnenvormen te gebruiken. Standaard: (zwart). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Alfawaarde die wordt toegepast op vormen en afbeeldingen voordat ze op het canvas worden samengesteld. Standaard 1.0 (ondoorzichtig). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Met globalAlpha toegepast stelt dit in hoe vormen en afbeeldingen op de bestaande bitmap worden getekend. Standaard: (bron-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Beeldafvlakkingsmodus; indien uitgeschakeld, worden afbeeldingen niet gladgestreken als ze worden geschaald. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Specificeert het vervagingseffect. Standaard 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Kleur van de schaduw. Standaard volledig transparant zwart. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Horizontale afstand waarop de schaduw wordt verschoven. Standaard 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Verticale afstand waarop de schaduw wordt verschoven. Standaard 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Kleur of stijl om te gebruiken voor de lijnen rond vormen. Standaard: (zwart). |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Voegt een treffergebied toe aan het canvas. Hiermee kunt u trefferdetectie eenvoudiger maken, gebeurtenissen naar DOM-elementen routeren, en gebruikers het canvas laten verkennen zonder het te zien. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Start een nieuw pad door de lijst met subpaden leeg te maken. Roep deze methode aan als u een nieuw pad wilt maken. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Verwijdert alle hitgebieden van het canvas. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Stelt alle pixels in de rechthoek gedefinieerd door startpunt (x, y) en grootte (breedte, hoogte) in op transparant zwart, waarbij eerder getekende inhoud wordt gewist. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Creëert een nieuw clipping-gebied door het snijpunt van het huidige clipping-gebied en het door het pad beschreven gebied te berekenen, gebruikmakend van de kronkelingsgetalregel die niet gelijk is aan nul. Open subpaden moeten impliciet worden gesloten bij het berekenen van het clipping-gebied, zonder de werkelijke subpaden te beïnvloeden . Het nieuwe clipping-gebied vervangt het huidige clipping-gebied. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Creëert een nieuw clipping-gebied door het snijpunt van het huidige clipping-gebied en het door het pad beschreven gebied te berekenen, gebruikmakend van de kronkelingsgetalregel die niet gelijk is aan nul. Open subpaden moeten impliciet worden gesloten bij het berekenen van het clipping-gebied, zonder dat dit invloed heeft op de daadwerkelijke subpaden. Het nieuwe clipping-gebied vervangt het huidige clipping-gebied. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Creëert een nieuw clipping-gebied door het snijpunt van het huidige clipping-gebied en het door het pad beschreven gebied te berekenen, gebruikmakend van de kronkelingsgetalregel die niet gelijk is aan nul. Open subpaden moeten impliciet worden gesloten bij het berekenen van het clipping-gebied, zonder dat dit invloed heeft op de daadwerkelijke subpaden. Het nieuwe clipping-gebied vervangt het huidige clipping-gebied. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Maakt een nieuw, leeg ImageData-object met de opgegeven afmetingen. Alle pixels in het nieuwe object zijn transparant zwart. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Maakt een nieuw, leeg ImageData-object met de opgegeven afmetingen. Alle pixels in het nieuwe object zijn transparant zwart. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Creëert een lineaire gradiënt langs de lijn gegeven door de coördinaten vertegenwoordigd door de parameters. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Maakt een patroon met behulp van de opgegeven afbeelding (een CanvasImageSource). Het herhaalt de bron in de richtingen gespecificeerd door het herhalingsargument. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Maakt een patroon met behulp van de opgegeven afbeelding (een CanvasImageSource). Het herhaalt de bron in de richtingen gespecificeerd door het herhalingsargument. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Creëert een radiale gradiënt gegeven door de coördinaten van de twee cirkels voorgesteld door de parameters. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Als een bepaald element is gefocust, tekent deze methode een focusring rond het huidige pad. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Tekent de opgegeven afbeelding. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Tekent de opgegeven afbeelding. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Vult de subpaden met de huidige vulstijl en het standaardalgoritme CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Vult de subpaden met de huidige vulstijl. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Vult de subpaden met de huidige vulstijl en het standaardalgoritme CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Vult de subpaden met de huidige vulstijl. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Tekent een gevulde rechthoek op (x, y) positie waarvan de grootte wordt bepaald door breedte en hoogte. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Tekent (vult) een gegeven tekst op de gegeven (x,y) positie. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Tekent (vult) een gegeven tekst op de gegeven (x,y) positie. |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Retourneert een ImageData-object dat de onderliggende pixelgegevens vertegenwoordigt voor het gebied van het canvas dat wordt aangegeven door de rechthoek die begint bij (sx, sy) en een sw-breedte en sh-hoogte heeft. Deze methode wordt niet beïnvloed door de canvas-transformatiematrix. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Rapporteert of het opgegeven punt zich al dan niet in het huidige pad bevindt. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Rapporteert of het opgegeven punt zich al dan niet in het huidige pad bevindt. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Rapporteert of het opgegeven punt zich al dan niet in het huidige pad bevindt. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Rapporteert of het opgegeven punt zich al dan niet in het huidige pad bevindt. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Rapporteert of het gespecificeerde punt al dan niet binnen het gebied ligt dat wordt omsloten door het strelen van een pad. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Rapporteert of het gespecificeerde punt al dan niet binnen het gebied ligt dat wordt omsloten door het strelen van een pad. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Retourneert een TextMetrics-object. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als er een vuile rechthoek wordt geleverd, worden alleen de pixels van die rechthoek geverfd. Deze methode wordt niet beïnvloed door de canvastransformatiematrix. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als er een vuile rechthoek wordt geleverd, worden alleen de pixels van die rechthoek geverfd. Deze methode wordt niet beïnvloed door de canvastransformatiematrix. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Verwijdert het hitgebied met de opgegeven id van het canvas. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Reset de huidige transformatie door de identiteitsmatrix. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Herstelt de status van de tekenstijl naar het laatste element op de 'state stack' dat is opgeslagen door save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Voegt een rotatie toe aan de transformatiematrix. Het hoekargument vertegenwoordigt een rechtsom draaiende hoek en wordt uitgedrukt in radialen. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Slaat de huidige status van de tekenstijl op met behulp van een stapel, zodat u elke wijziging die u erin aanbrengt, kunt terugdraaien met restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Voegt een schaaltransformatie toe aan de canvaseenheden met x horizontaal en met y verticaal. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Herstelt de huidige transformatie naar de identiteitsmatrix en roept vervolgens de methode transform() aan met dezelfde argumenten. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Lijnt de subpaden uit met de huidige streekstijl. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Lijnt de subpaden uit met de huidige streekstijl. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Schildert een rechthoek met een startpunt op (x, y) en een aw-breedte en een h-hoogte op het canvas, met de huidige lijnstijl. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Tekent (streken) een gegeven tekst op de gegeven (x, y) positie. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Tekent (streken) een gegeven tekst op de gegeven (x, y) positie. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Vermenigvuldigt de huidige transformatiematrix met de matrix beschreven door zijn argumenten. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Voegt een vertaaltransformatie toe door het canvas en zijn oorsprong x horizontaal en y verticaal op het raster te verplaatsen. |

### Zie ook

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* naamruimte [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* montage [Aspose.HTML](../../)


