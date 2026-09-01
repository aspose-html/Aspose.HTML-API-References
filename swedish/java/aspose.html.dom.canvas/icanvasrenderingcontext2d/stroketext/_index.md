---
title: "ICanvasRenderingContext2D.StrokeText"
second_title: "Aspose.HTML för Java API-referens"
description: "ICanvasRenderingContext2D‑metod. Ritar konturer av en given text på den angivna x‑y‑positionen"
type: docs

url: /sv/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/
---
## StrokeText(String, double, double) {#stroketext}

Ritar (strokar) en given text vid den angivna (x, y)-positionen.

```java
public void StrokeText(String text, double x, double y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | Texten som ska ritas med det aktuella teckensnittet, textAlign, textBaseline och direction-värdena. |
| x | Double | x-axeln för koordinaten för textens startpunkt. |
| y | Double | y-axeln för koordinaten för textens startpunkt. |

### Se även

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## StrokeText(String, double, double, double?) {#stroketext_1}

Ritar (strokar) en given text vid den angivna (x, y)-positionen.

```java
public void StrokeText(String text, double x, double y, double? maxWidth)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | Texten som ska ritas med det aktuella teckensnittet, textAlign, textBaseline och direction-värdena. |
| x | Double | x-axeln för koordinaten för textens startpunkt. |
| y | Double | y-axeln för koordinaten för textens startpunkt. |
| maxWidth | Nullable`1 | Den maximala bredden att rita. Om den anges och strängen beräknas bli bredare än denna bredd, justeras teckensnittet för att använda ett mer horisontellt kompakt teckensnitt (om ett sådant finns tillgängligt eller om ett rimligt läsbart kan syntetiseras genom att skala det aktuella teckensnittet horisontellt) eller ett mindre teckensnitt. |

### Se även

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
