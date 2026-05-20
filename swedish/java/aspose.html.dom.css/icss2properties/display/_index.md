---
title: "ICSS2Properties.Display"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties‑egenskap. Värdena för denna egenskap har följande betydelser"
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Värdena för denna egenskap har följande betydelser:

block – Detta värde får ett element att generera en huvud‑block‑box. inline – Detta värde får ett element att generera en eller flera inline‑boxar. list-item – Detta värde får ett element (t.ex. LI i HTML) att generera en huvud‑block‑box och en list‑item‑inline‑box. För information om listor och exempel på listformatering, se avsnittet om [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker – Detta värde deklarerar [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) före eller efter en box som en markör. Detta värde bör endast användas med [:before och :after pseudo‑element](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) som är knutna till block‑nivå‑element. I andra fall tolkas värdet som 'inline'. Se avsnittet om [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) för mer information. none – Detta värde får ett element att inte generera några boxar i [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (dvs. elementet har ingen effekt på layouten). Underordnade element genererar inte heller några boxar; detta beteende kan inte åsidosättas genom att sätta ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display)-egenskapen på underordnade. Observera att ett display‑värde 'none' inte skapar en osynlig box; det skapar ingen box alls. CSS innehåller mekanismer som gör att ett element kan generera boxar i formateringsstrukturen som påverkar formatering men som inte är synliga själva. Se avsnittet om [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) för detaljer. run-in och compact – Dessa värden skapar antingen block‑ eller inline‑boxar, beroende på sammanhang. Egenskaper tillämpas på run-in‑ och compact‑boxar baserat på deras slutliga status (inline‑nivå eller block‑nivå). Till exempel gäller ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space)-egenskapen endast om boxen blir en block‑box. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell och table-caption – Dessa värden får ett element att bete sig som ett table‑element (med de begränsningar som beskrivs i kapitlet om [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Returvärde

display‑egenskapen

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
