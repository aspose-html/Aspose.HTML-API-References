---
title: "SvgRenderer.Render"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo SvgRenderer. Definisce il metodo per il rendering di più SVGDocument in uno specifico IDevice. Il rendering verrà eseguito una volta che non vi siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato sia trascorso"
type: docs

url: /it/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Definisce il metodo per il rendering di più [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) in uno specifico [`IDevice`](../../idevice/). Il rendering verrà eseguito una volta che non vi siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato sia trascorso.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| timeout | TimeSpan | Un TimeSpan che rappresenta il numero di millisecondi da attendere, oppure un TimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |
| documenti | SVGDocument[] | I documenti da renderizzare. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Definisce un metodo per il rendering di più [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) in uno specifico [`IDevice`](../../idevice/), utilizzando un token di cancellazione per richiedere l'annullamento dell'operazione.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| cancellationToken | CancellationToken | Un token di cancellazione da osservare mentre si attende il completamento dell'operazione. |
| fonti | SVGDocument[] | I documenti SVG da renderizzare. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
