---
title: Interface ITextureBrush
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Drawing.ITextureBrush koppel. Definiert eine Pinselschnittstelle die ein Bild verwendet um das Innere einer Form zu füllen.
type: docs
weight: 2740
url: /de/net/aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

Definiert eine Pinselschnittstelle, die ein Bild verwendet, um das Innere einer Form zu füllen.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorMap](../../aspose.html.drawing/itexturebrush/colormap/) { get; } | Die Anzahl der Elemente muss gerade sein. Jedes gerade Element hat eine alte Farbe. Jedes ungerade Element hat eine neue Farbe. |
| [Image](../../aspose.html.drawing/itexturebrush/image/) { get; } | Ruft das vom Pinsel verwendete Bild ab oder legt es fest. |
| [ImageArea](../../aspose.html.drawing/itexturebrush/imagearea/) { get; } | Gibt den Teil des Bildes an, der vom Pinsel verwendet wird. Wenn er gleich RectangleF.Empty ist, wird das gesamte Bild verwendet. Koordinaten sind in Pixel angegeben. |
| [Opacity](../../aspose.html.drawing/itexturebrush/opacity/) { get; } | Deckkraftwert in einer Farbtransformationsmatrix abrufen. |

### Siehe auch

* interface [ITransformableBrush](../itransformablebrush/)
* namensraum [Aspose.Html.Drawing](../../aspose.html.drawing/)
* Montage [Aspose.HTML](../../)


