---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SvgRenderer-Methode. Definiert eine Methode zum Rendern mehrerer SVGDocuments in ein bestimmtes IDevice. Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung verstrichen ist."
type: docs

url: /de/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Definiert eine Methode zum Rendern mehrerer [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s in ein bestimmtes [`IDevice`](../../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer oder Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung verstrichen ist.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| Timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden zum Warten darstellt, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |
| Dokumente | SVGDocument[] | Die zu rendernden Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Definiert eine Methode zum Rendern mehrerer [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s in ein bestimmtes [`IDevice`](../../idevice/), wobei ein Cancellation-Token verwendet wird, um die Operation abzubrechen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| cancellationToken | CancellationToken | Ein Cancellation-Token, das während des Wartens auf den Abschluss der Aufgabe beobachtet werden soll. |
| Quellen | SVGDocument[] | Die SVG-Dokumente, die gerendert werden sollen. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
