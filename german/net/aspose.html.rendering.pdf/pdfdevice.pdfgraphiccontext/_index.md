---
title: Class PdfDevice.PdfGraphicContext
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.Pdf.PdfDevicePdfGraphicContext klas. Enthält aktuelle Grafiksteuerungsparameter für das PdfDevice. Diese Parameter definieren den globalen Rahmen in dem die Grafikoperatoren ausgeführt werden.
type: docs
weight: 4450
url: /de/net/aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Enthält aktuelle Grafiksteuerungsparameter für das PdfDevice. Diese Parameter definieren den globalen Rahmen, in dem die Grafikoperatoren ausgeführt werden.

```csharp
public class PdfGraphicContext : GraphicContext
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfGraphicContext](pdfgraphiccontext/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Setzt oder erhält Zeichenabstand. |
| override [FillBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/fillbrush/) { get; set; } | Legt das Pinselobjekt fest oder ruft es ab, das verwendet wird, um das Innere von Pfaden zu füllen. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Legt das TrueType-Schriftartobjekt fest oder ruft es ab, das zum Rendern von Text verwendet wird. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Legt die Textschriftgröße fest oder erhält sie. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Legt den Textschriftstil fest oder ruft ihn ab. |
| override [LineCap](../../aspose.html.rendering.pdf/pdfgraphiccontext/linecap/) { get; set; } | Legt den Code fest oder ruft ihn ab, der die Form der Endpunkte für jeden offenen Pfad angibt, der mit Strichen versehen ist. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Legt den Phasenoffset des aktuellen Linienstrichmusters fest oder ruft ihn ab. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Setzt oder ruft die Beschreibung des Strichmusters ab, das verwendet werden soll, wenn Pfade gestrichen werden. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Sets von erhält den Stil von gestrichelten Linien eines gestrichenen Pfads. |
| override [LineJoin](../../aspose.html.rendering.pdf/pdfgraphiccontext/linejoin/) { get; set; } | Legt den Code fest oder ruft ihn ab, der die Form der Verbindungen zwischen verbundenen Segmenten eines gezeichneten Pfads angibt. |
| override [LineWidth](../../aspose.html.rendering.pdf/pdfgraphiccontext/linewidth/) { get; set; } | Setzt oder erhält die Dicke der zu streichenden Pfade. |
| override [MiterLimit](../../aspose.html.rendering.pdf/pdfgraphiccontext/miterlimit/) { get; set; } | Setzt oder ermittelt die maximale Länge von gegehrten Linienverbindungen für gestrichene Pfade. Dieser Parameter begrenzt die Länge der "Spitzen", die entstehen, wenn Liniensegmente in scharfen Winkeln zusammenlaufen. |
| override [StrokeBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/strokebrush/) { get; set; } | Legt das Pinselobjekt fest oder ruft es ab, das für Strichpfade verwendet wird. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | erhält a[`TextInfo`](../../aspose.html.rendering/textinfo/) Objekt, das Informationen über gerenderten Text enthält. |
| override [TransformationMatrix](../../aspose.html.rendering.pdf/pdfgraphiccontext/transformationmatrix/) { get; set; } | Legt Transformationsmatrix fest oder ruft diese ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../aspose.html.rendering.pdf/pdfgraphiccontext/clone/)() | Erstellt eine neue Instanz einer Klasse mit denselben Eigenschaftswerten wie eine vorhandene Instanz. |
| override [Transform](../../aspose.html.rendering.pdf/pdfgraphiccontext/transform/)(Matrix) | Ändern Sie die aktuelle Transformationsmatrix, indem Sie die angegebene Matrix multiplizieren. |

### Siehe auch

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* namensraum [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* Montage [Aspose.HTML](../../)


