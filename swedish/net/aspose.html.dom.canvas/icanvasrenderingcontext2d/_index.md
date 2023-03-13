---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D gränssnitt. ICanvasRenderingContext2Dgränssnittet används för att rita rektanglar text bilder och andra objekt på canvaselementet. Den tillhandahåller 2Drenderingskontexten för ritytan på ett canvaselement.
type: docs
weight: 260
url: /sv/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D-gränssnittet används för att rita rektanglar, text, bilder och andra objekt på canvaselementet. Den tillhandahåller 2D-renderingskontexten för ritytan på ett canvaselement.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | En skrivskyddad bakåtreferens till HTMLCanvasElement. Kan vara null om det inte är associerat med ett canvaselement. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Färg eller stil att använda inuti former. Standard: (svart). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Alfavärde som tillämpas på former och bilder innan de sammansätts på arbetsytan. Standard 1.0 (ogenomskinlig). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Med globalAlpha tillämpad ställer detta in hur former och bilder ritas på den befintliga bitmappen. Standard: (källa-över) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Bildutjämningsläge; om inaktiverad kommer bilder inte att jämnas ut om de skalas. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Anger suddighetseffekten. Standard 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Färg på skuggan. Standard helt transparent svart. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Horisontellt avstånd skuggan kommer att förskjutas. Standard 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Vertikalt avstånd som skuggan förskjuts. Standard 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Färg eller stil att använda för linjerna runt former. Standard: (svart). |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Lägger till en träffregion på arbetsytan. Detta låter dig göra träffdetektering enklare, låter dig dirigera händelser till DOM-element, och gör det möjligt för användare att utforska arbetsytan utan att se den. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Startar en ny sökväg genom att tömma listan med undersökvägar. Anropa den här metoden när du vill skapa en ny sökväg. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Tar bort alla träffområden från arbetsytan. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Ställer in alla pixlar i rektangeln som definieras av startpunkt (x, y) och storlek (bredd, höjd) till transparent svart, vilket raderar allt tidigare ritat innehåll. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och det område som beskrivs av sökvägen, med hjälp av regeln om slingrande nummer som inte är noll. Öppna undersökvägar måste underförstått stängas när klippområdet beräknas, utan att de faktiska undervägarna påverkas . Det nya klippområdet ersätter det nuvarande klippområdet. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och området som beskrivs av banan, med hjälp av regeln för slingrande nummer som inte är noll. Öppna undersökvägar måste vara implicit stängda vid beräkning av urklippsregionen, utan att påverka de faktiska undersökvägarna. Den nya klippningsregionen ersätter den nuvarande klippningsregionen. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och området som beskrivs av banan, med hjälp av regeln för slingrande nummer som inte är noll. Öppna undersökvägar måste vara implicit stängda vid beräkning av urklippsregionen, utan att påverka de faktiska undersökvägarna. Den nya klippningsregionen ersätter den nuvarande klippningsregionen. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Skapar ett nytt tomt ImageData-objekt med de angivna måtten. Alla pixlar i det nya objektet är transparenta svarta. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Skapar ett nytt tomt ImageData-objekt med de angivna måtten. Alla pixlar i det nya objektet är transparenta svarta. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Skapar en linjär gradient längs linjen som ges av koordinaterna som representeras av parametrarna. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Skapar ett mönster med den angivna bilden (en CanvasImageSource). Den upprepar källan i de riktningar som anges av repetitionsargumentet. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Skapar ett mönster med den angivna bilden (en CanvasImageSource). Den upprepar källan i de riktningar som anges av repetitionsargumentet. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Skapar en radiell gradient som ges av koordinaterna för de två cirklarna som representeras av parametrarna. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Om ett givet element är fokuserat, ritar denna metod en fokusring runt den aktuella banan. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Ritar den angivna bilden. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Ritar den angivna bilden. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Ritar den angivna bilden. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Ritar den angivna bilden. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Ritar den angivna bilden. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Ritar den angivna bilden. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Fyller undersökvägarna med den aktuella fyllningsstilen och standardalgoritmen CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Fyller undersökvägarna med den aktuella fyllningsstilen. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Fyller undersökvägarna med den aktuella fyllningsstilen och standardalgoritmen CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Fyller undersökvägarna med den aktuella fyllningsstilen. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Ritar en fylld rektangel vid (x, y) position vars storlek bestäms av bredd och höjd. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Ritar (fyller) en given text vid den givna (x,y) positionen. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Ritar (fyller) en given text vid den givna (x,y) positionen. |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Returnerar ett ImageData-objekt som representerar underliggande pixeldata för området på duken som betecknas av rektangeln som börjar på (sx, sy) och har en sw bredd och sh höjd. Denna metod påverkas inte av arbetsytans transformationsmatris. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Rapporterar om den angivna punkten finns i den aktuella sökvägen eller inte. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Rapporterar om den angivna punkten finns i den aktuella sökvägen eller inte. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Rapporterar om den angivna punkten finns i den aktuella sökvägen eller inte. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Rapporterar om den angivna punkten finns i den aktuella sökvägen eller inte. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Rapporterar huruvida den angivna punkten är inom området som ryms av en bana eller inte. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Rapporterar huruvida den angivna punkten är inom området som ryms av en bana eller inte. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Returnerar ett TextMetrics-objekt. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Målar data från det givna ImageData-objektet på bitmappen. Om en smutsig rektangel tillhandahålls, målas endast pixlarna från den rektangeln. Denna metod påverkas inte av arbetsytans transformationsmatris. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Målar data från det givna ImageData-objektet på bitmappen. Om en smutsig rektangel tillhandahålls, målas endast pixlarna från den rektangeln. Denna metod påverkas inte av arbetsytans transformationsmatris. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Tar bort träffområdet med det angivna ID:t från arbetsytan. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Återställer den aktuella transformationen av identitetsmatrisen. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Återställer ritstilens tillstånd till det sista elementet på 'state-stacken' som sparats av save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Lägger till en rotation till transformationsmatrisen. Vinkelargumentet representerar en rotationsvinkel medurs och uttrycks i radianer. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Sparar den aktuella ritstilen med hjälp av en stack så att du kan återställa alla ändringar du gör i den med restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Lägger till en skalningstransformation till arbetsytan med x horisontellt och med y vertikalt. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Återställer den aktuella transformationen till identitetsmatrisen och anropar sedan transform()-metoden med samma argument. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Stryker undersökvägarna med den aktuella linjestilen. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Stryker undersökvägarna med den aktuella linjestilen. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Målar en rektangel som har en startpunkt vid (x, y) och har aw-bredd och en h-höjd på duken, med den aktuella linjestilen. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Ritar (stryker) en given text vid den givna (x, y) positionen. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Ritar (stryker) en given text vid den givna (x, y) positionen. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplicerar den aktuella transformationsmatrisen med matrisen som beskrivs av dess argument. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Lägger till en översättningstransformation genom att flytta duken och dess ursprung x horisontellt och y vertikalt på rutnätet. |

### Se även

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* namnutrymme [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* hopsättning [Aspose.HTML](../../)


