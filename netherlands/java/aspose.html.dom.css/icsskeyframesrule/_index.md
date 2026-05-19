---
title: "ICSSKeyframesRule-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSKeyframesRule interface. De name‑eigenschap van de CSSKeyframeRule-interface haalt op en stelt de naam van de animatie in zoals gebruikt door de animation-name‑eigenschap."
type: docs

url: /nl/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

De naam‑eigenschap van de CSSKeyframeRule‑interface haalt de naam van de animatie op en stelt deze in, zoals gebruikt door de animation-name‑eigenschap.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) De alleen‑lees cssRules‑eigenschap van de [`CSSKeyframeRule`](../icsskeyframerule/) interface retourneert een [`CSSRuleList`](../icssrulelist/) met de regels in de keyframes‑at‑rule. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) De name‑eigenschap van de [`CSSKeyframeRule`](../icsskeyframerule/) interface haalt op en stelt de naam van de animatie in zoals gebruikt door de animation-name‑eigenschap. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | De appendRule‑methode voegt de meegegeven [`CSSKeyframeRule`](../icsskeyframerule/) toe aan het einde van de keyframes‑regelcollectie. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | De deleteRule‑methode verwijdert de [`CSSKeyframeRule`](../icsskeyframerule/) met de opgegeven sleutel. Als er geen regel met deze sleutel bestaat, doet de methode niets. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | De findRule‑methode retourneert de regel met een sleutel die overeenkomt met de opgegeven sleutel. Als zo'n regel niet bestaat, wordt een null‑waarde geretourneerd. |

### Zie ook

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
