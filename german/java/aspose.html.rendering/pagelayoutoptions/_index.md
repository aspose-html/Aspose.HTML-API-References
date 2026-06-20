---
title: "PageLayoutOptions Aufzählung"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.PageLayoutOptions‑Enum. Gibt Flags an, die zusammen mit anderen PageSetup‑Optionen die Größen und Layouts von Seiten bestimmen. Diese Flags können gemäß ihrer Beschreibungen kombiniert werden."
type: docs

url: /de/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Gibt Flags an, die zusammen mit anderen PageSetup-Optionen die Größen und Layouts von Seiten bestimmen. Diese Flags können gemäß ihrer Beschreibungen kombiniert werden.

```java
[Flags]
public enum PageLayoutOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Standardwert, der anzeigt, dass die PageLayoutOptions die Größen und Layouts von Seiten nicht beeinflussen. |
| FitToContentWidth | `1` | Dieses Flag gibt an, dass die Breite der Seiten aus der Größe des Inhalts selbst bestimmt wird, nicht aus der angegebenen Seitenbreite. Die Breite des Inhalts wird für jede Seite einzeln berechnet. |
| UseWidestPage | `2` | In Kombination mit FitToContentWidth gibt es an, dass die Breite jeder Seite gleich sein wird und der breitesten Inhaltsgröße aller Seiten entspricht. |
| FitToWidestContentWidth | `3` | Dieses Flag gibt an, dass die Breite der Seite aus der Größe des Inhalts selbst bestimmt wird, nicht aus der angegebenen Seitenbreite. Die Breite jeder Seite wird gleich sein und der breitesten Inhaltsgröße aller Seiten entsprechen. |
| FitToContentHeight | `10` | Dieses Flag gibt an, dass die Höhe der Seite aus der Größe des Inhalts selbst bestimmt wird, nicht aus der angegebenen Seitenhöhe. Der gesamte Dokumentinhalt wird auf einer einzigen Seite platziert, wenn dieses Flag angegeben ist. |
| ScaleToPageWidth | `100` | Dieses Flag gibt an, dass der Inhalt des Dokuments so skaliert wird, dass er auf die Seite passt, bei der der Unterschied zwischen der verfügbaren Seitenbreite und dem überlappenden Inhalt am größten ist. Es steht im Konflikt mit dem FitToContentWidth‑Flag und wenn beide Flags angegeben sind, wirkt nur ScaleToPageWidth. |
| ScaleToPageHeight | `1000` | Dieses Flag gibt an, dass der Inhalt des Dokuments so skaliert wird, dass er in die Höhe der ersten Seite passt. Es steht im Konflikt mit dem FitToContentHeight‑Flag und wenn beide Flags angegeben sind, wirkt nur ScaleToPageHeight. Der gesamte Dokumentinhalt wird ausschließlich auf einer einzigen Seite platziert. |

### Siehe auch

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
