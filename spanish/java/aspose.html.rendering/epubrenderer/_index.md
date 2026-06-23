---
title: "Clase EpubRenderer"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.rendering.EpubRenderer class. Representa un renderizador de documentos EPub"
type: docs

url: /es/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Representa un renderizador de documentos EPub.

```java
public class EpubRenderer : Renderer<Stream>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Define un método para renderizar múltiples documentos EPub en un [`IDevice`](../idevice/) específico, usando un token de cancelación para solicitar la cancelación de la operación. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Renderiza múltiples documentos EPub en el [`IDevice`](../idevice/) especificado. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Renderiza un documento EPub en el [`IDevice`](../idevice/) especificado. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Define un método para renderizar múltiples flujos EPub en un [`IDevice`](../idevice/) específico. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Renderiza múltiples documentos EPub en el [`IDevice`](../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Renderiza un documento EPub en el [`IDevice`](../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |

### Ver también

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
