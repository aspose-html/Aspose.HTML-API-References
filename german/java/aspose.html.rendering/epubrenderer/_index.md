---
title: "EpubRenderer Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.EpubRenderer Klasse. Stellt einen EPub-Dokument-Renderer dar"
type: docs

url: /de/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Stellt einen EPub-Dokument-Renderer dar.

```java
public class EpubRenderer : Renderer<Stream>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Definiert eine Methode zum Rendern mehrerer EPub‑Dokumente in ein bestimmtes [`IDevice`](../idevice/), unter Verwendung eines Abbruch‑Tokens, um die Stornierung des Vorgangs anzufordern. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Rendert mehrere EPub‑Dokumente in das angegebene [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Rendert ein EPub‑Dokument in das angegebene [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Definiert eine Methode zum Rendern mehrerer EPub‑Streams in ein bestimmtes [`IDevice`](../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr vorhanden sind oder die angegebene Zeitüberschreitung abgelaufen ist. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Rendert mehrere EPub‑Dokumente in das angegebene [`IDevice`](../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr vorhanden sind oder die angegebene Zeitüberschreitung abgelaufen ist. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Rendert ein EPub‑Dokument in das angegebene [`IDevice`](../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr vorhanden sind oder die angegebene Zeitüberschreitung abgelaufen ist. |

### Siehe auch

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
