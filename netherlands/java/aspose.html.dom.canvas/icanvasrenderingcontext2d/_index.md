---
title: "ICanvasRenderingContext2D-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D-interface. De ICanvasRenderingContext2D-interface wordt gebruikt om rechthoeken, tekst, afbeeldingen en andere objecten op het canvas‑element te tekenen. Het biedt de 2D‑renderingscontext voor het tekenoppervlak van een canvas‑element."
type: docs

url: /nl/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

De **ICanvasRenderingContext2D**-interface wordt gebruikt voor het tekenen van rechthoeken, tekst, afbeeldingen en andere objecten op het canvas-element. Het biedt de 2D-rendercontext voor het tekenoppervlak van een canvas-element.

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
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Start een nieuw pad door de lijst met sub‑paden te legen. Roep deze methode aan wanneer je een nieuw pad wilt maken. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Verwijdert alle hit‑regio's van het canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Stelt alle pixels in de rechthoek, gedefinieerd door het startpunt (x, y) en de afmetingen (breedte, hoogte), in op transparante zwart, waardoor alle eerder getekende inhoud wordt gewist. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Creëert een nieuw knipgebied door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Creëert een nieuw knipgebied door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Creëert een nieuw knipgebied door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Creëert een nieuw, leeg ImageData‑object met de opgegeven afmetingen. Alle pixels in het nieuwe object zijn transparante zwart. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Creëert een nieuw, leeg ImageData‑object met de opgegeven afmetingen. Alle pixels in het nieuwe object zijn transparante zwart. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Creëert een lineaire gradiënt langs de lijn die wordt gegeven door de coördinaten die door de parameters worden weergegeven. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Creëert een patroon met behulp van de opgegeven afbeelding (een CanvasImageSource). Het herhaalt de bron in de richtingen die door het herhalingsargument worden opgegeven. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Creëert een patroon met behulp van de opgegeven afbeelding (een CanvasImageSource). Het herhaalt de bron in de richtingen die door het herhalingsargument worden opgegeven. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Creëert een radiale gradiënt die wordt gegeven door de coördinaten van de twee cirkels die door de parameters worden weergegeven. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Als een gegeven element de focus heeft, tekent deze methode een focusring rond het huidige pad. |
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
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Retourneert een ImageData-object dat de onderliggende pixelgegevens vertegenwoordigt voor het gebied van het canvas dat wordt aangeduid door de rechthoek die begint bij (sx, sy) en een breedte sw en hoogte sh heeft. Deze methode wordt niet beïnvloed door de canvas-transformatiematrix. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Geeft aan of het opgegeven punt zich binnen het huidige pad bevindt of niet. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Geeft aan of het opgegeven punt zich binnen het huidige pad bevindt of niet. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Geeft aan of het opgegeven punt zich binnen het huidige pad bevindt of niet. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Geeft aan of het opgegeven punt zich binnen het huidige pad bevindt of niet. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Geeft aan of het opgegeven punt zich binnen het gebied bevindt dat wordt omsloten door de omtrek van een pad of niet. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Geeft aan of het opgegeven punt zich binnen het gebied bevindt dat wordt omsloten door de omtrek van een pad of niet. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Retourneert een TextMetrics-object. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels van die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de canvas-transformatiematrix. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels van die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de canvas-transformatiematrix. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Verwijdert de hit-regio met de opgegeven id van het canvas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Reset de huidige transformatie met de identiteitsmatrix. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Herstelt de tekenstijlstatus naar het laatste element op de 'state stack' die is opgeslagen door save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Voegt een rotatie toe aan de transformatiematrix. Het hoekargument vertegenwoordigt een klokwijzerige rotatiehoek en wordt uitgedrukt in radialen. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Slaat de huidige tekenstijlstatus op met behulp van een stack zodat je elke wijziging die je maakt kunt terugdraaien met restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Voegt een schaalsverandering toe aan de canvas-eenheden, horizontaal met x en verticaal met y. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Reset de huidige transformatie naar de identiteitsmatrix en roept vervolgens de transform()-methode aan met dezelfde argumenten. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Tekent de omtrek van de subpaden met de huidige lijnstijl. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Tekent de omtrek van de subpaden met de huidige lijnstijl. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Schildert een rechthoek met een startpunt op (x, y) en een breedte w en een hoogte h op het canvas, met gebruik van de huidige lijnstijl. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Tekent (omtrekt) een opgegeven tekst op de opgegeven (x, y) positie. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Tekent (omtrekt) een opgegeven tekst op de opgegeven (x, y) positie. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Vermenigvuldigt de huidige transformatiematrix met de matrix die wordt beschreven door zijn argumenten. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Voegt een translatie toe door het canvas en zijn oorsprong horizontaal met x en verticaal met y over het raster te verplaatsen. |

### Zie ook

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
