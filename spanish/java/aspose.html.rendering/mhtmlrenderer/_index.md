---
title: "Clase MhtmlRenderer"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.MhtmlRenderer. Representa un renderizador de documentos MHTML"
type: docs

url: /es/java/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

Representa un renderizador de documentos MHTML.

```java
public class MhtmlRenderer : Renderer<Stream>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Define un método para renderizar múltiples documentos MHTML en un [`IDevice`](../idevice/) específico, usando un token de cancelación para solicitar la cancelación de la operación. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Renderiza múltiples documentos MHTML en el [`IDevice`](../idevice/) especificado. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | Renderiza un documento MHTML en el [`IDevice`](../idevice/) especificado. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Renderiza múltiples documentos MHTML en el [`IDevice`](../idevice/). El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Renderiza múltiples documentos MHTML en el [`IDevice`](../idevice/). El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Renderiza un documento MHTML en el [`IDevice`](../idevice/). El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |

### Ver también

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
