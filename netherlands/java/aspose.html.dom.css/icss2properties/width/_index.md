---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Deze eigenschap specificeert de inhoudsbreedte van boxen die worden gegenereerd door blokniveau- en vervangen elementen."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Deze eigenschap specificeert de [inhoudsbreedte](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) van boxen die worden gegenereerd door blokniveau- en [vervangen](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) elementen.

Deze eigenschap is niet van toepassing op niet-vervangen [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) elementen. De breedte van de vakken van een niet-vervangen inline‑element is die van de gerenderde inhoud erin (voordat er een relatieve offset van kinderen is). Onthoud dat inline‑vakken vloeien in [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). De breedte van line‑vakken wordt bepaald door hun [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), maar kan worden verkort door de aanwezigheid van [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

De breedte van de box van een vervangen element is [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) en kan worden geschaald door de user agent als de waarde van deze eigenschap anders is dan 'auto'.

De waarden hebben de volgende betekenissen:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Specificeert een vaste breedte.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Specificeert een procentuele breedte. Het percentage wordt berekend ten opzichte van de breedte van het gegenereerde vak's [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - De breedte hangt af van de waarden van andere eigenschappen. Zie de onderstaande secties. Opmerking: Negatieve waarden voor ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) zijn illegaal.

```java
public String Width { get; set; }
```

### Retourwaarde

breedte eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
