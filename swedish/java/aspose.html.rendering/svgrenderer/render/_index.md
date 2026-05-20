---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML för Java API-referens"
description: "SvgRenderer metod. Definierar en metod för rendering av flera SVGDocuments till en specifik IDevice. Rendering kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när den angivna timeouten har löpt ut."
type: docs

url: /sv/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Definierar en metod för rendering av flera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s till en specifik [`IDevice`](../../idevice/). Rendering kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när den angivna timeouten har löpt ut.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta obegränsat. |
| dokument | SVGDocument[] | Dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Definierar en metod för rendering av flera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s till en specifik [`IDevice`](../../idevice/), med en avbokningstoken för att begära avbrytning av operationen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| cancellationToken | CancellationToken | En avbokningstoken att observera medan man väntar på att uppgiften ska slutföras. |
| källor | SVGDocument[] | SVG-dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
