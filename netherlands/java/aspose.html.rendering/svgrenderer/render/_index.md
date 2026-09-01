---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SvgRenderer-methode. Definieert een methode voor het renderen van meerdere SVGDocumenten naar een specifieke IDevice. Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven timeout is verstreken"
type: docs

url: /nl/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Definieert een methode voor het renderen van meerdere [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s naar een specifieke [`IDevice`](../../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven timeout is verstreken.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| time‑out | TimeSpan | Een TimeSpan die het aantal milliseconden aangeeft om te wachten, of een TimeSpan die -1 milliseconde aangeeft om onbeperkt te wachten. |
| documenten | SVGDocument[] | De documenten om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Definieert een methode voor het renderen van meerdere [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s naar een specifieke [`IDevice`](../../idevice/), met behulp van een annulerings‑token om annulering van de bewerking aan te vragen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| cancellationToken | CancellationToken | Een annulerings‑token om te observeren terwijl men wacht tot de taak is voltooid. |
| bronnen | SVGDocument[] | De SVG‑documenten om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
