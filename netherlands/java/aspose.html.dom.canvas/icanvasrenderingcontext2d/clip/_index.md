---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICanvasRenderingContext2D methode. Maakt een nieuwe knipregio door de intersectie te berekenen van de huidige knipregio en het gebied dat wordt beschreven door het pad, met behulp van de non-zero winding number-regel. Open subpaden moeten impliciet worden gesloten bij het berekenen van de knipregio zonder de daadwerkelijke subpaden te beïnvloeden. De nieuwe knipregio vervangt de huidige knipregio."
type: docs

url: /nl/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Creëert een nieuw knipgebied door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied.

```java
public void Clip()
```

### Zie ook

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Creëert een nieuw knipgebied door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied.

```java
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillRule | CanvasFillRule | Het algoritme om te bepalen of een punt zich binnen of buiten een pad bevindt |

### Zie ook

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Creëert een nieuw knipgebied door de intersectie te berekenen tussen het huidige knipgebied en het gebied dat door het pad wordt beschreven, met behulp van de non‑zero winding‑number‑regel. Open sub‑paden moeten impliciet worden gesloten bij het berekenen van het knipgebied, zonder de daadwerkelijke sub‑paden te beïnvloeden. Het nieuwe knipgebied vervangt het huidige knipgebied.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | Path2D | Een Path2D-pad om te knippen. |
| fillRule | CanvasFillRule | Het algoritme om te bepalen of een punt zich binnen of buiten een pad bevindt. |

### Zie ook

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
