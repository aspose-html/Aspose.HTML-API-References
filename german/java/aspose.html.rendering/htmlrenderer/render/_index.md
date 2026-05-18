---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HtmlRenderer‑Methode. Definiert eine Methode zum Rendern mehrerer HTMLDocuments in ein bestimmtes IDevice"
type: docs

url: /de/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Definiert eine Methode zum Rendern mehrerer [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s in ein bestimmtes [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden angibt, die gewartet werden soll, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |
| Quellen | HTMLDocument[] | Die zu rendernden HTML-Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Definiert eine Methode zum Rendern mehrerer [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s in ein bestimmtes [`IDevice`](../../idevice/), wobei ein Cancellation‑Token verwendet wird, um die Operation abzubrechen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| cancellationToken | CancellationToken | Ein CancellationToken, das während des Wartens auf den Abschluss der Aufgabe beobachtet werden soll. |
| Quellen | HTMLDocument[] | Die zu rendernden HTML-Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
