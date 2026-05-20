---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties-egenskap. Denna egenskap specificerar innehållsbredden för lådor som genereras av blocknivå- och ersatta element."
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Denna egenskap specificerar [innehållsbredden](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) för lådor som genereras av blocknivå- och [ersatta](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) element.

Denna egenskap gäller inte för icke‑ersatta [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) element. Bredden på en icke‑ersatt inline‑elements lådor är den för det renderade innehållet inom dem (innan någon relativ förskjutning av barn). Kom ihåg att inline‑lådor flödar in i [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). Bredden på radlådor ges av deras [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), men kan förkortas av förekomsten av [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

Bredden på en ersatt elements låda är [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) och kan skalas av användaragenten om värdet för denna egenskap är annorlunda än 'auto'.

Värdena har följande betydelser:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Anger en fast bredd.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Anger en procentuell bredd. Procenten beräknas i förhållande till bredden på den genererade lådans [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - Bredden beror på värdena för andra egenskaper. Se avsnitten nedan.Obs: Negativa värden för ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) är olagliga.

```java
public String Width { get; set; }
```

### Returvärde

bredd egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
