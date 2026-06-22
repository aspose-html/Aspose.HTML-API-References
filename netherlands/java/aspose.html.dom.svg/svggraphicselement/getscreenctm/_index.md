---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGGraphicsElement-methode. Retourneert de transformatie‑matrix vanuit de huidige gebruikerseenheden, d.w.z. na toepassing van het attribuut transform, indien aanwezig, op de ouder‑user‑agent‑notitie van een pixel. Voor weergaveapparaten vertegenwoordigt dit idealiter een fysieke schermpixel. Voor andere apparaten of omgevingen waar de fysieke pixelgrootte niet bekend is, kan in plaats daarvan een algoritme worden gebruikt dat vergelijkbaar is met de CSS2-definitie van een pixel. Merk op dat null wordt geretourneerd als dit element niet is gekoppeld aan de documentboom. Deze methode zou beter getiteld kunnen zijn als getClientCTM, maar de naam getScreenCTM wordt om historische redenen behouden."
type: docs

url: /nl/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Retourneert de transformatie‑matrix van de huidige gebruikers‑eenheden (d.w.z. na toepassing van het ‘transform’-attribuut, indien aanwezig) naar de perceptie van een \"pixel\" door de bovenliggende user‑agent. Voor weergave‑apparaten vertegenwoordigt dit idealiter een fysiek scherm‑pixel. Voor andere apparaten of omgevingen waarin de fysieke pixelgrootte onbekend is, kan in plaats daarvan een algoritme worden gebruikt dat vergelijkbaar is met de CSS2‑definitie van een \"pixel\". Merk op dat null wordt geretourneerd als dit element niet is gekoppeld aan de documentboom. Deze methode zou beter getClientCTM genoemd kunnen worden, maar de naam getScreenCTM wordt om historische redenen behouden.

```java
public SVGMatrix GetScreenCTM()
```

### Retourwaarde

Een SVGMatrix-object dat de opgegeven transformatie‑matrix definieert.

### Zie ook

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
