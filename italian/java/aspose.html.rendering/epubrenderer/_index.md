---
title: "EpubRenderer Classe"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.rendering.EpubRenderer class. Rappresenta un renderer di documenti EPub"
type: docs

url: /it/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Rappresenta un renderer di documenti EPub.

```java
public class EpubRenderer : Renderer<Stream>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Definisce un metodo per il rendering di più documenti EPub in un specifico [`IDevice`](../idevice/), utilizzando un token di cancellazione per richiedere l'annullamento dell'operazione. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Esegue il rendering di più documenti EPub nel [`IDevice`](../idevice/) specificato. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Esegue il rendering del documento EPub nel [`IDevice`](../idevice/) specificato. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Definisce un metodo per il rendering di più stream EPub in uno specifico [`IDevice`](../idevice/). Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Esegue il rendering di più documenti EPub nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Esegue il rendering del documento EPub nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |

### Vedi anche

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
