---
title: Class PageSetup
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.PageSetup klas. Stellt ein Seiteneinrichtungsobjekt dar das für die Konfigurationsausgabeseitengruppe verwendet wird.
type: docs
weight: 4390
url: /de/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Stellt ein Seiteneinrichtungsobjekt dar, das für die Konfigurationsausgabeseitengruppe verwendet wird.

```csharp
public class PageSetup
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | Erhält oder setzt ein Flag, das bestimmt, wann die Seitengröße auf die breiteste Seite im Dokument angepasst wird. Diese Option ist zeitaufwändig, sodass die Zeit der Dokumentverarbeitung um das Zweifache erhöht werden kann. Die Anpassung wird nur durchgeführt, wenn die breiteste Seite im Dokument breiter ist als die in festgelegte Seitengröße`PageSetup` . Angepasste Seitengröße wird für alle Seiten im Dokument verwendet. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | Ruft alle Seitenkonfigurationen in der Seitensequenz ab oder legt sie fest. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | Holt oder setzt[`AtPagePriority`](../atpagepriority/) die die Reihenfolge der Anwendung von Seitengrößendeklarationen bestimmt. Standardmäßig überschreiben Optionen CSS`@Buchseite` Regeln . |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | Ruft die Konfiguration der ersten Seite ab oder legt sie fest. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | Ruft die Konfiguration ungerader Seiten ab. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | Ruft ab oder setzt die[`PageLayoutOptions`](../pagelayoutoptions/) . Standardwert istNone , jeder andere Wert überschreibt die[`AdjustToWidestPage`](./adjusttowidestpage/) Verhalten. Funktioniert nur mit HTML-Dokumenten. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | Ruft die gerade Seitenkonfiguration ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Legt die Konfiguration der linken/rechten Seite fest. |

### Siehe auch

* namensraum [Aspose.Html.Rendering](../../aspose.html.rendering/)
* Montage [Aspose.HTML](../../)


