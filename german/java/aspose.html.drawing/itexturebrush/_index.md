---
title: "ITextureBrush-Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.drawing.ITextureBrush-Schnittstelle. Definiert eine Pinsel‑Schnittstelle, die ein Bild verwendet, um das Innere einer Form zu füllen."
type: docs

url: /de/java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

Definiert die Pinsel‑Schnittstelle, die ein Bild verwendet, um das Innere einer Form zu füllen.

```java
public interface ITextureBrush : ITransformableBrush
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) Die Anzahl der Elemente muss gerade sein. Jedes gerade Element ist die alte Farbe. Jedes ungerade Element ist die neue Farbe. |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) Ruft das vom Pinsel verwendete Bild ab oder legt es fest. |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) Gibt den Teil des Bildes an, der vom Pinsel verwendet wird. Wenn er gleich RectangleF.Empty ist, wird das gesamte Bild verwendet. Die Koordinaten sind in Pixeln. |
[getOpacity]
[setOpacity] Get opacity value in a color transform matrix. |

### Siehe auch

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
