---
title: "ICanvasRenderingContext2D gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D gränssnitt. ICanvasRenderingContext2D-gränssnittet används för att rita rektanglar, text, bilder och andra objekt på canvas‑elementet. Det tillhandahåller 2D‑renderingskontexten för ritytan på ett canvas‑element."
type: docs

url: /sv/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D‑gränssnittet används för att rita rektanglar, text, bilder och andra objekt på canvas‑elementet. Det tillhandahåller det tvådimensionella renderingskontextet för ritytan på ett canvas‑element.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) En skrivskyddad bakåtreferens till HTMLCanvasElement. Kan vara null om den inte är associerad med ett canvas‑element. |
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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Startar en ny bana genom att tömma listan med underbanor. Anropa den här metoden när du vill skapa en ny bana. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Tar bort alla träffregioner från canvasen. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Ställer in alla pixlar i rektangeln som definieras av startpunkten (x, y) och storleken (bredd, höjd) till transparent svart, vilket raderar tidigare ritat innehåll. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Skapar en ny beskärningsregion genom att beräkna skärningspunkten mellan den aktuella beskärningsregionen och området som beskrivs av banan, med hjälp av regeln för icke‑noll winding‑nummer. Öppna underbanor måste implicit stängas vid beräkning av beskärningsregionen, utan att påverka de faktiska underbanorna. Den nya beskärningsregionen ersätter den aktuella beskärningsregionen. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Skapar en ny beskärningsregion genom att beräkna skärningspunkten mellan den aktuella beskärningsregionen och området som beskrivs av banan, med hjälp av regeln för icke‑noll winding‑nummer. Öppna underbanor måste implicit stängas vid beräkning av beskärningsregionen, utan att påverka de faktiska underbanorna. Den nya beskärningsregionen ersätter den aktuella beskärningsregionen. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Skapar en ny beskärningsregion genom att beräkna skärningspunkten mellan den aktuella beskärningsregionen och området som beskrivs av banan, med hjälp av regeln för icke‑noll winding‑nummer. Öppna underbanor måste implicit stängas vid beräkning av beskärningsregionen, utan att påverka de faktiska underbanorna. Den nya beskärningsregionen ersätter den aktuella beskärningsregionen. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Skapar ett nytt, tomt ImageData‑objekt med de angivna dimensionerna. Alla pixlar i det nya objektet är transparent svarta. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Skapar ett nytt, tomt ImageData‑objekt med de angivna dimensionerna. Alla pixlar i det nya objektet är transparent svarta. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Skapar ett linjärt gradient längs den linje som ges av koordinaterna som representeras av parametrarna. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Skapar ett mönster med den angivna bilden (en CanvasImageSource). Det upprepar källan i de riktningar som anges av repetitionsargumentet. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Skapar ett mönster med den angivna bilden (en CanvasImageSource). Det upprepar källan i de riktningar som anges av repetitionsargumentet. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Skapar ett radiellt gradient givet av koordinaterna för de två cirklarna som representeras av parametrarna. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Om ett givet element är fokuserat, ritar den här metoden en fokusring runt den aktuella vägen. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Ritar den angivna bilden. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Ritar den angivna bilden. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Ritar den angivna bilden. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Ritar den angivna bilden. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Ritar den angivna bilden. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Ritar den angivna bilden. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Fyller delvägarna med den aktuella fyllningsstilen och standardalgoritmen CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Fyller delvägarna med den aktuella fyllningsstilen. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Fyller delvägarna med den aktuella fyllningsstilen och standardalgoritmen CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Fyller delvägarna med den aktuella fyllningsstilen. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Ritar en fylld rektangel vid positionen (x, y) vars storlek bestäms av bredd och höjd. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Ritar (fyller) en given text vid den angivna (x,y)-positionen. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Ritar (fyller) en given text vid den angivna (x,y)-positionen. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Returnerar ett ImageData-objekt som representerar den underliggande pixeldata för det område på canvas som anges av rektangeln som börjar vid (sx, sy) och har en bredd sw och en höjd sh. Denna metod påverkas inte av canvasens transformationsmatris. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Rapporterar om den angivna punkten finns i den aktuella vägen eller inte. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Rapporterar om den angivna punkten finns i den aktuella vägen eller inte. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Rapporterar om den angivna punkten finns i den aktuella vägen eller inte. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Rapporterar om den angivna punkten finns i den aktuella vägen eller inte. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Rapporterar om den angivna punkten ligger inom området som omfattas av konturdragning av en väg eller inte. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Rapporterar om den angivna punkten ligger inom området som omfattas av konturdragning av en väg eller inte. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Returnerar ett TextMetrics-objekt. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Målar data från det angivna ImageData-objektet på bitmapen. Om en smutsig rektangel anges målas endast pixlarna från den rektangeln. Denna metod påverkas inte av canvasens transformationsmatris. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Målar data från det angivna ImageData-objektet på bitmapen. Om en smutsig rektangel anges målas endast pixlarna från den rektangeln. Denna metod påverkas inte av canvasens transformationsmatris. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Tar bort träffregionen med det angivna id:t från canvas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Återställer den aktuella transformen med identitetsmatrisen. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Återställer ritstilens tillstånd till det sista elementet på 'tillståndsstacken' som sparats av save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Lägger till en rotation i transformationsmatrisen. Vinkelargumentet representerar en medurs rotationsvinkel och uttrycks i radianer. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Sparar det aktuella ritstilens tillstånd med en stack så att du kan återgå från alla ändringar du gör med restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Lägger till en skalningstransformering av canvasenheten horisontellt med x och vertikalt med y. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Återställer den aktuella transformen till identitetsmatrisen och anropar sedan transform()-metoden med samma argument. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Ritar konturer på delvägarna med den aktuella konturstilen. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Ritar konturer på delvägarna med den aktuella konturstilen. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Målar en rektangel som har en startpunkt vid (x, y) och har en bredd w och en höjd h på canvasen, med den aktuella konturstilen. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Ritar (konturerar) en given text vid den angivna (x, y)-positionen. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Ritar (konturerar) en given text vid den angivna (x, y)-positionen. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplicerar den aktuella transformationsmatrisen med matrisen som beskrivs av dess argument. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Lägger till en translatio­ns‑transformering genom att flytta canvasen och dess ursprung x horisontellt och y vertikalt på rutnätet. |

### Se även

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
