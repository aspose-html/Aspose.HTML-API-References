---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICanvasRenderingContext2D-Methode. Erstellt einen neuen Clipping‑Bereich, indem die Schnittmenge des aktuellen Clipping‑Bereichs und des durch den Pfad beschriebenen Bereichs nach der Non‑Zero‑Winding‑Number‑Regel berechnet wird. Offene Teilpfade müssen beim Berechnen des Clipping‑Bereichs implizit geschlossen werden, ohne die eigentlichen Teilpfade zu beeinflussen. Der neue Clipping‑Bereich ersetzt den aktuellen Clipping‑Bereich."
type: docs

url: /de/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Erstellt eine neue Clipping‑Region, indem die Schnittmenge der aktuellen Clipping‑Region und des durch den Pfad beschriebenen Bereichs berechnet wird, unter Verwendung der Non‑Zero‑Winding‑Number‑Regel. Offene Unterpfade müssen beim Berechnen der Clipping‑Region implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen. Die neue Clipping‑Region ersetzt die aktuelle Clipping‑Region.

```java
public void Clip()
```

### Siehe auch

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Erstellt eine neue Clipping‑Region, indem die Schnittmenge der aktuellen Clipping‑Region und des durch den Pfad beschriebenen Bereichs berechnet wird, unter Verwendung der Non‑Zero‑Winding‑Number‑Regel. Offene Unterpfade müssen beim Berechnen der Clipping‑Region implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen. Die neue Clipping‑Region ersetzt die aktuelle Clipping‑Region.

```java
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillRule | CanvasFillRule | Der Algorithmus, mit dem bestimmt wird, ob ein Punkt innerhalb oder außerhalb eines Pfades liegt. |

### Siehe auch

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Erstellt eine neue Clipping‑Region, indem die Schnittmenge der aktuellen Clipping‑Region und des durch den Pfad beschriebenen Bereichs berechnet wird, unter Verwendung der Non‑Zero‑Winding‑Number‑Regel. Offene Unterpfade müssen beim Berechnen der Clipping‑Region implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen. Die neue Clipping‑Region ersetzt die aktuelle Clipping‑Region.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | Path2D | Ein Path2D-Pfad zum Clipping. |
| fillRule | CanvasFillRule | Der Algorithmus, mit dem bestimmt wird, ob ein Punkt innerhalb oder außerhalb eines Pfades liegt. |

### Siehe auch

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
