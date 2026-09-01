---
title: "Classe RendererTSource"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.rendering.Renderer1TSource. Rappresenta una classe astratta per tutti i renderer"
type: docs

url: /it/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Rappresenta una classe astratta per tutti i renderer.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parametro | Descrizione |
| --- | --- |
| TDocument | Il tipo del documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Definisce il metodo per il rendering di !:TDocument nel [`IDevice`](../idevice/) specificato. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Definisce il metodo per il rendering di !:TDocument nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Definisce il metodo per il rendering di !:TDocument nel [`IDevice`](../idevice/) specificato. Il rendering verrà eseguito una volta che non ci siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o che sia trascorso il timeout specificato. |

### Vedi anche

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
