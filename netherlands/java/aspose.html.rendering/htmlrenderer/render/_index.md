---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HtmlRenderer‑methode. Definieert een methode voor het renderen van meerdere HTMLDocument‑objecten naar een specifiek IDevice"
type: docs

url: /nl/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Definieert een methode voor het renderen van meerdere [`HTMLDocument`](../../../com.aspose.html/htmldocument/)‑objecten naar een specifiek [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| time-out | TimeSpan | Een TimeSpan die het aantal milliseconden aangeeft om te wachten, of een TimeSpan die -1 milliseconde aangeeft om onbeperkt te wachten. |
| sources | HTMLDocument[] | De HTML‑documenten om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Definieert een methode voor het renderen van meerdere [`HTMLDocument`](../../../com.aspose.html/htmldocument/)‑objecten naar een specifiek [`IDevice`](../../idevice/), met behulp van een annulerings‑token om annulering van de bewerking aan te vragen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| cancellationToken | CancellationToken | Een CancellationToken om te observeren terwijl men wacht tot de taak voltooid is. |
| sources | HTMLDocument[] | De HTML‑documenten om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
