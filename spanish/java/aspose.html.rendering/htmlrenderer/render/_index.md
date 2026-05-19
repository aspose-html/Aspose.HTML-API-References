---
title: "HtmlRenderer.Render"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método HtmlRenderer. Define el método para renderizar múltiples HTMLDocuments en un IDevice específico"
type: docs

url: /es/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Define el método para renderizar múltiples [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s en un [`IDevice`](../../idevice/) específico.

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| tiempo de espera | TimeSpan | Un TimeSpan que representa la cantidad de milisegundos a esperar, o un TimeSpan que representa -1 milisegundo para esperar indefinidamente. |
| fuentes | HTMLDocument[] | Los documentos HTML a renderizar. |

### Ver también

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Define un método para renderizar múltiples [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s en un [`IDevice`](../../idevice/) específico, usando un token de cancelación para solicitar la cancelación de la operación.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| cancellationToken | CancellationToken | Un CancellationToken para observar mientras se espera que la tarea se complete. |
| fuentes | HTMLDocument[] | Los documentos HTML a renderizar. |

### Ver también

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
