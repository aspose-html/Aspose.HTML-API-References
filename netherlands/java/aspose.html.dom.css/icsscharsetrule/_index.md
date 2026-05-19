---
title: "ICSSCharsetRule-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSCharsetRule interface. De CSSCharsetRule‑interface vertegenwoordigt een charset‑regel in een CSS‑stijlblad. De waarde van het encoding‑attribuut beïnvloedt niet de codering van tekstgegevens in de DOM‑objecten; deze codering is altijd UTF-16. Nadat een stijlblad is geladen, is de waarde van het encoding‑attribuut gelijk aan de waarde die in de charset‑regel wordt gevonden. Als er geen charset in het oorspronkelijke document aanwezig was, wordt er geen CSSCharsetRule aangemaakt. De waarde van het encoding‑attribuut kan ook worden gebruikt als hint voor de codering die bij het serialiseren van het stijlblad wordt toegepast."
type: docs

url: /nl/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

De CSSCharsetRule-interface vertegenwoordigt een @charset‑regel in een CSS‑stijlblad. De waarde van het encoding‑attribuut heeft geen invloed op de codering van tekstgegevens in de DOM‑objecten; deze codering is altijd UTF-16. Nadat een stijlblad is geladen, is de waarde van het encoding‑attribuut gelijk aan de waarde die in de @charset‑regel is gevonden. Als er geen @charset in het oorspronkelijke document aanwezig was, wordt er geen CSSCharsetRule aangemaakt. De waarde van het encoding‑attribuut kan ook worden gebruikt als hint voor de codering die wordt gebruikt bij het serialiseren van het stijlblad.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### Zie ook

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
