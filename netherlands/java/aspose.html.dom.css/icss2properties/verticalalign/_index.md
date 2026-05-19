---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Deze eigenschap beïnvloedt de verticale positionering binnen een regelvak van de vakken die worden gegenereerd door een inline‑niveau element. De volgende waarden hebben alleen betekenis ten opzichte van een bovenliggend inline‑niveau element of ten opzichte van een bovenliggend block‑niveau element als dat element anonieme inline‑vakken genereert; ze hebben geen effect als zo'n bovenliggend element niet bestaat."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Deze eigenschap beïnvloedt de verticale positionering binnen een regelvak van de vakken die worden gegenereerd door een inline‑niveau element. De volgende waarden hebben alleen betekenis ten opzichte van een bovenliggend inline‑niveau element, of ten opzichte van een bovenliggend block‑niveau element, als dat element [anonieme inline‑vakken](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous) genereert; ze hebben geen effect als zo'n bovenliggend element niet bestaat.

Opmerking. De waarden van deze eigenschap hebben iets andere betekenissen in de context van tabellen. Raadpleeg de sectie over [table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) voor details. baseline - Lijn de basislijn van het vak uit met de basislijn van het bovenliggende vak. Als het vak geen basislijn heeft, lijn dan de onderkant van het vak uit met de basislijn van de bovenliggende. middle - Lijn het verticale middelpunt van het vak uit met de basislijn van het bovenliggende vak plus de helft van de x-hoogte van de bovenliggende. sub - Verlaag de basislijn van het vak naar de juiste positie voor subscripties van het bovenliggende vak. (Deze waarde heeft geen effect op de lettergrootte van de tekst van het element.) super - Verhoog de basislijn van het vak naar de juiste positie voor superscripties van het bovenliggende vak. (Deze waarde heeft geen effect op de lettergrootte van de tekst van het element.) text-top - Lijn de bovenkant van het vak uit met de bovenkant van het lettertype van het bovenliggende element. text-bottom - Lijn de onderkant van het vak uit met de onderkant van het lettertype van het bovenliggende element. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Verhoog (positieve waarde) of verlaag (negatieve waarde) het vak met deze afstand (een percentage van de ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height) waarde). De waarde '0%' betekent hetzelfde als 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Verhoog (positieve waarde) of verlaag (negatieve waarde) het vak met deze afstand. De waarde '0cm' betekent hetzelfde als 'baseline'. top - Lijn de bovenkant van het vak uit met de bovenkant van het regelvak. bottom - Lijn de onderkant van het vak uit met de onderkant van het regelvak.

```java
public String VerticalAlign { get; set; }
```

### Retourwaarde

vertical-align eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
