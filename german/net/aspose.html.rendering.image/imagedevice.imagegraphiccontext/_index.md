---
title: Class ImageDevice.ImageGraphicContext
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.Image.ImageDeviceImageGraphicContext klas. Enthält aktuelle Grafiksteuerungsparameter für dieImageDevice . Diese Parameter definieren den globalen Rahmen innerhalb dessen die Grafikoperatoren ausgeführt werden.
type: docs
weight: 4310
url: /de/net/aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Enthält aktuelle Grafiksteuerungsparameter für die[`ImageDevice`](../imagedevice/) . Diese Parameter definieren den globalen Rahmen, innerhalb dessen die Grafikoperatoren ausgeführt werden.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageGraphicContext](imagegraphiccontext/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Setzt oder erhält Zeichenabstand. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Legt das Pinselobjekt fest oder ruft es ab, das verwendet wird, um das Innere von Pfaden zu füllen. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Legt das TrueType-Schriftartobjekt fest oder ruft es ab, das zum Rendern von Text verwendet wird. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Legt die Textschriftgröße fest oder erhält sie. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Legt den Textschriftstil fest oder ruft ihn ab. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Legt den Code fest oder ruft ihn ab, der die Form der Endpunkte für jeden offenen Pfad angibt, der mit Strichen versehen ist. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Legt den Phasenoffset des aktuellen Linienstrichmusters fest oder ruft ihn ab. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Setzt oder ruft die Beschreibung des Strichmusters ab, das verwendet werden soll, wenn Pfade gestrichen werden. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Sets von erhält den Stil von gestrichelten Linien eines gestrichenen Pfads. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Legt den Code fest oder ruft ihn ab, der die Form der Verbindungen zwischen verbundenen Segmenten eines gezeichneten Pfads angibt. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Setzt oder erhält die Dicke der zu streichenden Pfade. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Setzt oder ermittelt die maximale Länge von gegehrten Linienverbindungen für gestrichene Pfade. Dieser Parameter begrenzt die Länge der "Spitzen", die entstehen, wenn Liniensegmente in scharfen Winkeln zusammenlaufen. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Legt das Pinselobjekt fest oder ruft es ab, das für Strichpfade verwendet wird. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | erhält a[`TextInfo`](../../aspose.html.rendering/textinfo/) Objekt, das Informationen über gerenderten Text enthält. |
| override [TransformationMatrix](../../aspose.html.rendering.image/imagegraphiccontext/transformationmatrix/) { get; set; } | Legt Transformationsmatrix fest oder ruft diese ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.html.rendering.image/imagegraphiccontext/clone/)() | Erstellt eine neue Instanz einer GdiGraphicContext-Klasse mit denselben Eigenschaftswerten wie eine vorhandene Instanz. |
| override [Transform](../../aspose.html.rendering.image/imagegraphiccontext/transform/)(Matrix) | Ändern Sie die aktuelle Transformationsmatrix, indem Sie die angegebene Matrix multiplizieren. |

### Siehe auch

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* namensraum [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* Montage [Aspose.HTML](../../)


