---
title: "SvgRenderer.Render"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SvgRenderer. Define el método para renderizar múltiples SVGDocuments en un IDevice específico. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado."
type: docs

url: /es/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Define el método para renderizar múltiples [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s en un [`IDevice`](../../idevice/) específico. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| timeout | TimeSpan | Un TimeSpan que representa la cantidad de milisegundos a esperar, o un TimeSpan que representa -1 milisegundo para esperar indefinidamente. |
| documentos | SVGDocument[] | Los documentos a renderizar. |

### Ver también

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Define un método para renderizar múltiples [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s en un [`IDevice`](../../idevice/) específico, utilizando un token de cancelación para solicitar la cancelación de la operación.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| cancellationToken | CancellationToken | Un token de cancelación para observar mientras se espera que la tarea se complete. |
| fuentes | SVGDocument[] | Los documentos SVG a renderizar. |

### Ver también

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
