---
title: "Clase SvgRenderer"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.SvgRenderer. Representa el renderizador de documentos SVG"
type: docs

url: /es/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

Representa un renderizador de documentos SVG.

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | Define un método para renderizar múltiples [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)s en un [`IDevice`](../idevice/) específico, utilizando un token de cancelación para solicitar la cancelación de la operación. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | Define un método para renderizar múltiples [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)s en un [`IDevice`](../idevice/) específico. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado. |

### Ver también

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
