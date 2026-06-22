---
title: "RendererTSource Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.Renderer1TSource klasse. Vertegenwoordigt een abstracte klasse voor alle renderers"
type: docs

url: /nl/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Stelt een abstracte klasse voor alle renderers voor.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Beschrijving |
| --- | --- |
| TDocument | Het type van het document. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Vrijgeeft niet-beheerde en - optioneel - beheerde bronnen. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Definieert methode voor het renderen van !:TDocument naar opgegeven [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Definieert methode voor het renderen van !:TDocument naar opgegeven [`IDevice`](../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of de opgegeven time‑out is verstreken. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Definieert methode voor het renderen van !:TDocument naar opgegeven [`IDevice`](../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of de opgegeven time‑out is verstreken. |

### Zie ook

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
