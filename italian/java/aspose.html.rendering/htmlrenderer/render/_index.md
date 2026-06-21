---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo HtmlRenderer. Definisce il metodo per il rendering di più HTMLDocument in uno specifico IDevice."
type: docs

url: /it/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Definisce il metodo per il rendering di più [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s in uno specifico [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| timeout | TimeSpan | Un TimeSpan che rappresenta il numero di millisecondi da attendere, oppure un TimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |
| fonti | HTMLDocument[] | I documenti HTML da renderizzare. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Definisce un metodo per il rendering di più [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s in uno specifico [`IDevice`](../../idevice/), utilizzando un token di cancellazione per richiedere l'annullamento dell'operazione.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| cancellationToken | CancellationToken | Un CancellationToken da osservare mentre si attende il completamento dell'operazione. |
| fonti | HTMLDocument[] | I documenti HTML da renderizzare. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
