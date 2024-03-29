---
title: ICanvasRenderingContext2D.Clip
second_title: Aspose.HTML für .NET-API-Referenz
description: ICanvasRenderingContext2D methode. Erstellt einen neuen ClippingBereich durch Berechnung des Schnittpunkts des aktuellen ClippingBereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Unterpfade müssen beim Berechnen des ClippingBereichs implizit geschlossen werden ohne die tatsächlichen Unterpfade zu beeinflussen . Der neue ClippingBereich ersetzt den aktuellen ClippingBereich.
type: docs
weight: 150
url: /de/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Erstellt einen neuen Clipping-Bereich durch Berechnung des Schnittpunkts des aktuellen Clipping-Bereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Unterpfade müssen beim Berechnen des Clipping-Bereichs implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen . Der neue Clipping-Bereich ersetzt den aktuellen Clipping-Bereich.

```csharp
public void Clip()
```

### Siehe auch

* interface [ICanvasRenderingContext2D](../)
* namensraum [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* Montage [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Erstellt einen neuen Clipping-Bereich durch Berechnung des Schnittpunkts des aktuellen Clipping-Bereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Teilpfade müssen bei der Berechnung des Clipping-Bereichs implizit geschlossen werden, ohne dass dies Auswirkungen auf die eigentlichen Teilpfade hat. Der neue Clipping-Bereich ersetzt den aktuellen Clipping-Bereich.

```csharp
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillRule | CanvasFillRule | Der Algorithmus, mit dem bestimmt wird, ob sich ein Punkt innerhalb eines Pfads oder außerhalb eines Pfads befindet |

### Siehe auch

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* namensraum [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* Montage [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Erstellt einen neuen Clipping-Bereich durch Berechnung des Schnittpunkts des aktuellen Clipping-Bereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Teilpfade müssen bei der Berechnung des Clipping-Bereichs implizit geschlossen werden, ohne dass dies Auswirkungen auf die eigentlichen Teilpfade hat. Der neue Clipping-Bereich ersetzt den aktuellen Clipping-Bereich.

```csharp
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | Path2D | Ein Path2D-Pfad zum Ausschneiden. |
| fillRule | CanvasFillRule | Der Algorithmus, mit dem bestimmt wird, ob sich ein Punkt innerhalb eines Pfads oder außerhalb eines Pfads befindet. |

### Siehe auch

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* namensraum [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* Montage [Aspose.HTML](../../../)


