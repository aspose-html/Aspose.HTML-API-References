---
title: "ICanvasRenderingContext2D Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D interface. De ICanvasRenderingContext2D interface wordt gebruikt voor het tekenen van rechthoeken, tekst, afbeeldingen en andere objecten op het canvas‑element. Het biedt de 2D‑rendercontext voor het tekenoppervlak van een canvas‑element"
type: docs

url: /nl/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

De ICanvasRenderingContext2D-interface wordt gebruikt om rechthoeken, tekst, afbeeldingen en andere objecten op het canvas-element te tekenen. Het biedt de 2D-renderingcontext voor het tekenoppervlak van een canvas-element.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Een alleen‑lezen terugverwijzing naar het HTMLCanvasElement. Kan null zijn als het niet is gekoppeld aan een canvas‑element. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Start een nieuw pad door de lijst met sub‑paden te legen. Roep deze methode aan wanneer u een nieuw pad wilt maken. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Verwijdert alle hit‑regio's van het canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Stelt alle pixels in de rechthoek, gedefinieerd door startpunt (x, y) en grootte (breedte, hoogte), in op transparante zwart, waardoor eerder getekende inhoud wordt gewist. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Maakt een nieuw knipgebied aan door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Maakt een nieuw knipgebied aan door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Maakt een nieuw knipgebied aan door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Maakt een nieuw, leeg ImageData‑object met de opgegeven afmetingen. Alle pixels in het nieuwe object zijn transparante zwart. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Maakt een nieuw, leeg ImageData‑object met de opgegeven afmetingen. Alle pixels in het nieuwe object zijn transparante zwart. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Maakt een lineaire gradient langs de lijn die wordt opgegeven door de coördinaten die door de parameters worden vertegenwoordigd. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Maakt een patroon met de opgegeven afbeelding (een CanvasImageSource). Het herhaalt de bron in de richtingen die door het herhalingsargument worden opgegeven. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Maakt een patroon met de opgegeven afbeelding (een CanvasImageSource). Het herhaalt de bron in de richtingen die door het herhalingsargument worden opgegeven. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Maakt een radiale gradient op basis van de coördinaten van de twee cirkels die door de parameters worden vertegenwoordigd. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Als een gegeven element gefocust is, tekent deze methode een focusring rond het huidige pad. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Tekent de opgegeven afbeelding. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Tekent de opgegeven afbeelding. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Tekent de opgegeven afbeelding. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Vult de subpaden met de huidige vulstijl en het standaardalgoritme CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Vult de subpaden met de huidige vulstijl. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Vult de subpaden met de huidige vulstijl en het standaardalgoritme CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Vult de subpaden met de huidige vulstijl. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Tekent een gevulde rechthoek op positie (x, y) waarvan de grootte wordt bepaald door breedte en hoogte. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Tekent (vult) een opgegeven tekst op de opgegeven (x,y) positie. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Tekent (vult) een opgegeven tekst op de opgegeven (x,y) positie. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Retourneert een ImageData-object dat de onderliggende pixelgegevens vertegenwoordigt voor het gebied van het canvas dat wordt aangeduid door de rechthoek die begint bij (sx, sy) en een breedte sw en hoogte sh heeft. Deze methode wordt niet beïnvloed door de transformatie-matrix van het canvas. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Rapporteert of het opgegeven punt al dan niet in het huidige pad zit. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Rapporteert of het opgegeven punt al dan niet in het huidige pad zit. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Rapporteert of het opgegeven punt al dan niet in het huidige pad zit. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Rapporteert of het opgegeven punt al dan niet in het huidige pad zit. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Rapporteert of het opgegeven punt al dan niet binnen het gebied ligt dat wordt gevormd door het stroken van een pad. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Rapporteert of het opgegeven punt al dan niet binnen het gebied ligt dat wordt gevormd door het stroken van een pad. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Retourneert een TextMetrics-object. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels van die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de transformatie-matrix van het canvas. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels van die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de transformatie-matrix van het canvas. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Verwijdert de hit-regio met de opgegeven id van het canvas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Stelt de huidige transformatie opnieuw in op de identiteitsmatrix. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Herstelt de tekenstijlstatus naar het laatste element op de 'state stack' dat is opgeslagen door save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Voegt een rotatie toe aan de transformatie-matrix. Het hoekargument vertegenwoordigt een klokwijzerige rotatiehoek en wordt uitgedrukt in radialen. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Slaat de huidige tekenstijlstatus op met behulp van een stack zodat je eventuele wijzigingen kunt terugdraaien met restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Voegt een schaaltransformatie toe aan de canvas-eenheden, horizontaal met x en verticaal met y. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Stelt de huidige transformatie opnieuw in op de identiteitsmatrix en roept vervolgens de transform()-methode aan met dezelfde argumenten. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Strookt de subpaden met de huidige stroke style. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Strookt de subpaden met de huidige stroke style. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Schildert een rechthoek met een startpunt op (x, y) en een breedte w en hoogte h op het canvas, met gebruik van de huidige stroke style. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Tekent (strookt) een opgegeven tekst op de opgegeven (x, y) positie. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Tekent (strookt) een opgegeven tekst op de opgegeven (x, y) positie. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Vermenigvuldigt de huidige transformatie-matrix met de matrix die wordt beschreven door zijn argumenten. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Voegt een translatie-transformatie toe door het canvas en zijn oorsprong x horizontaal en y verticaal op het raster te verplaatsen. |

### Zie ook

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
