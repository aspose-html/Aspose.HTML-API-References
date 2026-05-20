---
title: "SVGPoint klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint class. Många av SVG DOM‑gränssnitten refererar till objekt av klassen SVGPoint. En SVGPoint är ett x‑y‑koordinatpar. När den används i matrisoperationer behandlas en SVGPoint som en vektor i formen x y 1. Om ett SVGRect‑objekt är markerat som skrivskyddat kommer ett försök att tilldela ett av dess attribut att resultera i ett undantag."
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Många av SVG DOM‑gränssnitten refererar till objekt av klassen SVGPoint. En SVGPoint är ett (x, y)-koordinatpar. När den används i matrisoperationer behandlas en SVGPoint som en vektor av formen: [x] [y] [1] Om ett SVGRect‑objekt markeras som skrivskyddat, kommer ett försök att tilldela ett av dess attribut att resultera i ett undantag som kastas.

```java
public class SVGPoint : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X‑koordinaten. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y‑koordinaten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Applicerar en 2x3‑matristransformation på detta SVGPoint‑objekt och returnerar ett nytt, transformerat SVGPoint‑objekt: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | Returnerar en sträng som representerar detta objekt. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
