---
title: ICanvasRenderingContext2D.Clip
second_title: Aspose.HTML för .NET API Referens
description: ICanvasRenderingContext2D metod. Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och det område som beskrivs av sökvägen med hjälp av regeln om slingrande nummer som inte är noll. Öppna undersökvägar måste underförstått stängas när klippområdet beräknas utan att de faktiska undervägarna påverkas . Det nya klippområdet ersätter det nuvarande klippområdet.
type: docs
weight: 150
url: /sv/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och det område som beskrivs av sökvägen, med hjälp av regeln om slingrande nummer som inte är noll. Öppna undersökvägar måste underförstått stängas när klippområdet beräknas, utan att de faktiska undervägarna påverkas . Det nya klippområdet ersätter det nuvarande klippområdet.

```csharp
public void Clip()
```

### Se även

* interface [ICanvasRenderingContext2D](../)
* namnutrymme [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* hopsättning [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och området som beskrivs av banan, med hjälp av regeln för slingrande nummer som inte är noll. Öppna undersökvägar måste vara implicit stängda vid beräkning av urklippsregionen, utan att påverka de faktiska undersökvägarna. Den nya klippningsregionen ersätter den nuvarande klippningsregionen.

```csharp
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillRule | CanvasFillRule | Algoritmen för att avgöra om en punkt är inuti en bana eller utanför en bana |

### Se även

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* namnutrymme [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* hopsättning [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Skapar ett nytt urklippsområde genom att beräkna skärningspunkten mellan det aktuella klippområdet och området som beskrivs av banan, med hjälp av regeln för slingrande nummer som inte är noll. Öppna undersökvägar måste vara implicit stängda vid beräkning av urklippsregionen, utan att påverka de faktiska undersökvägarna. Den nya klippningsregionen ersätter den nuvarande klippningsregionen.

```csharp
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | Path2D | En Path2D-väg till klipp. |
| fillRule | CanvasFillRule | Algoritmen för att avgöra om en punkt är inuti en bana eller utanför en bana. |

### Se även

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* namnutrymme [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* hopsättning [Aspose.HTML](../../../)


