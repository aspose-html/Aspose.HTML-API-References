---
title: "Classe MhtmlRenderer"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.rendering.MhtmlRenderer classe. Rappresenta un renderer di documenti MHTML"
type: docs

url: /it/java/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

Rappresenta un renderer di documenti MHTML.

```java
public class MhtmlRenderer : Renderer<Stream>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Definisce un metodo per il rendering di più documenti MHTML in un [`IDevice`](../idevice/) specifico, utilizzando un token di cancellazione per richiedere l'annullamento dell'operazione. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Esegue il rendering di più documenti MHTML nel [`IDevice`](../idevice/) specificato. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | Esegue il rendering del documento MHTML nel [`IDevice`](../idevice/) specificato. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Esegue il rendering di più documenti MHTML nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Esegue il rendering di più documenti MHTML nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Esegue il rendering del documento MHTML nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |

### Vedi anche

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
