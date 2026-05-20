---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML för Java API-referens"
description: "HtmlRenderer‑metod. Definierar en metod för att rendera flera HTMLDocument‑objekt till en specifik IDevice."
type: docs

url: /sv/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Definierar en metod för att rendera flera [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s till en specifik [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta obegränsat. |
| källor | HTMLDocument[] | HTML‑dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Definierar en metod för att rendera flera [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s till en specifik [`IDevice`](../../idevice/), med en avbokningstoken för att begära avbrytning av operationen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| cancellationToken | CancellationToken | En CancellationToken att observera medan du väntar på att uppgiften ska slutföras. |
| källor | HTMLDocument[] | HTML‑dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
