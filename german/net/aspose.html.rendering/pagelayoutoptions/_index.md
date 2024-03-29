---
title: Enum PageLayoutOptions
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.PageLayoutOptions opsomming. Gibt Flags an die zusammen mit anderen PageSetupOptionen Größen und Layouts von Seiten bestimmen. Diese Flags können entsprechend ihrer Beschreibung miteinander kombiniert werden.
type: docs
weight: 4380
url: /de/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Gibt Flags an, die zusammen mit anderen PageSetup-Optionen Größen und Layouts von Seiten bestimmen. Diese Flags können entsprechend ihrer Beschreibung miteinander kombiniert werden.

```csharp
[Flags]
public enum PageLayoutOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Standardwert, der angibt, dass die PageLayoutOptions die Größen und Layouts von Seiten nicht beeinflussen. |
| FitToContentWidth | `1` | Dieses Flag gibt an, dass die Breite der Seiten von der Inhaltsgröße selbst bestimmt wird, nicht von der angegebenen Seitenbreite. Die Breite des Inhalts wird für jede Seite einzeln berechnet. |
| UseWidestPage | `2` | In Kombination mitFitToContentWidth gibt an, dass die Breite aller Seiten gleich ist und der breitesten Inhaltsgröße aller Seiten entspricht. |
| FitToWidestContentWidth | `3` | Dieses Flag gibt an, dass die Breite der Seite von der Inhaltsgröße selbst und nicht von der angegebenen Seitenbreite bestimmt wird. Die Breite jeder Seite ist gleich und entspricht der breitesten Inhaltsgröße aller Seiten. |
| FitToContentHeight | `10` | Dieses Flag gibt an, dass die Höhe der Seite von der Inhaltsgröße selbst bestimmt wird, nicht von der angegebenen Seitenhöhe. Der gesamte Inhalt des Dokuments befindet sich auf einer einzelnen Seite, wenn dieses Flag angegeben ist. |
| ScaleToPageWidth | `100` | Dieses Flag gibt an, dass der Inhalt des Dokuments so skaliert wird, dass er auf die Seite passt, auf der der Unterschied zwischen der verfügbaren Seitenbreite und dem überlappenden Inhalt am größten ist. Es kollidiert mitFitToContentWidth Flag und nur wenn beide Flags angegeben sindScaleToPageWidth wird wirksam. |
| ScaleToPageHeight | `1000` | Dieses Flag gibt an, dass der Inhalt des Dokuments auf die Höhe der ersten Seite skaliert wird. Es kollidiert mitFitToContentHeight Flag und nur wenn beide Flags angegeben sindScaleToPageHeight wird wirksam. Alle Dokumentinhalte werden nur auf einer Seite platziert. |

### Siehe auch

* namensraum [Aspose.Html.Rendering](../../aspose.html.rendering/)
* Montage [Aspose.HTML](../../)


