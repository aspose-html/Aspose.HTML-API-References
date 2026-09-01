---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML för Java API-referens"
description: "ICanvasRenderingContext2D-metod. Skapar en ny klippningsregion genom att beräkna skärningspunkten mellan den aktuella klippningsregionen och området som beskrivs av vägen med hjälp av regeln för icke‑noll varvningsnummer. Öppna delvägar måste implicit stängas när klippningsregionen beräknas utan att påverka de faktiska delvägarna. Den nya klippningsregionen ersätter den aktuella klippningsregionen."
type: docs

url: /sv/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Skapar ett nytt beskärningsområde genom att beräkna skärningspunkten mellan det aktuella beskärningsområdet och det område som beskrivs av banan, med hjälp av regeln för icke‑noll varvningsnummer. Öppna underbanor måste implicit stängas vid beräkning av beskärningsområdet, utan att påverka de faktiska underbanorna. Det nya beskärningsområdet ersätter det aktuella beskärningsområdet.

```java
public void Clip()
```

### Se även

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Skapar ett nytt beskärningsområde genom att beräkna skärningspunkten mellan det aktuella beskärningsområdet och det område som beskrivs av banan, med hjälp av regeln för icke‑noll varvningsnummer. Öppna underbanor måste implicit stängas vid beräkning av beskärningsområdet, utan att påverka de faktiska underbanorna. Det nya beskärningsområdet ersätter det aktuella beskärningsområdet.

```java
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillRule | CanvasFillRule | Algoritmen för att avgöra om en punkt är innanför eller utanför en väg. |

### Se även

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Skapar ett nytt beskärningsområde genom att beräkna skärningspunkten mellan det aktuella beskärningsområdet och det område som beskrivs av banan, med hjälp av regeln för icke‑noll varvningsnummer. Öppna underbanor måste implicit stängas vid beräkning av beskärningsområdet, utan att påverka de faktiska underbanorna. Det nya beskärningsområdet ersätter det aktuella beskärningsområdet.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | Path2D | En Path2D‑väg att klippa. |
| fillRule | CanvasFillRule | Algoritmen för att avgöra om en punkt är innanför eller utanför en bana. |

### Se även

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
