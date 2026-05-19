---
title: "Clase RendererTSource"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.Renderer1TSource. Representa una clase abstracta para todos los renderizadores"
type: docs

url: /es/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Representa una clase abstracta para todos los renderizadores.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parámetro | Descripción |
| --- | --- |
| TDocument | El tipo del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Define un método para renderizar !:TDocument en el [`IDevice`](../idevice/) especificado. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Define un método para renderizar !:TDocument en el [`IDevice`](../idevice/). El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Define un método para renderizar !:TDocument en el [`IDevice`](../idevice/). El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado. |

### Ver también

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
