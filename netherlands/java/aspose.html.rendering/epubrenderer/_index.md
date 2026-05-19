---
title: "EpubRenderer Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.EpubRenderer class. Vertegenwoordigt een EPub-documentrenderer"
type: docs

url: /nl/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Stelt een EPub-documentrenderer voor.

```java
public class EpubRenderer : Renderer<Stream>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Vrijgeeft onbeheerste en - optioneel - beheerde bronnen. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Definieert een methode voor het renderen van meerdere EPub‑documenten naar een specifieke [`IDevice`](../idevice/), met behulp van een annulerings‑token om annulering van de bewerking aan te vragen. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Rendert meerdere EPub‑documenten naar het opgegeven [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Rendert een EPub‑document naar het opgegeven [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Definieert een methode voor het renderen van meerdere EPub‑streams naar een specifieke [`IDevice`](../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven time‑out is verstreken. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Rendert meerdere EPub‑documenten naar het opgegeven [`IDevice`](../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven time‑out is verstreken. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Rendert een EPub‑document naar het opgegeven [`IDevice`](../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven time‑out is verstreken. |

### Zie ook

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
