---
title: "RendererTSource Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.Renderer1TSource Klasse. Stellt eine abstrakte Klasse für alle Renderer dar."
type: docs

url: /de/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Stellt eine abstrakte Klasse für alle Renderer dar.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Beschreibung |
| --- | --- |
| TDocument | Der Typ des Dokuments. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Definiert eine Methode zum Rendern von !:TDocument in das angegebene [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Definiert eine Methode zum Rendern von !:TDocument in das angegebene [`IDevice`](../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr vorhanden sind oder die angegebene Zeitüberschreitung abgelaufen ist. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Definiert eine Methode zum Rendern von !:TDocument in das angegebene [`IDevice`](../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr vorhanden sind oder die angegebene Zeitüberschreitung abgelaufen ist. |

### Siehe auch

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
