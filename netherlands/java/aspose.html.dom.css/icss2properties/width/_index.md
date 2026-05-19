---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Deze eigenschap specificeert de inhoudsbreedte van vakken die worden gegenereerd door block-level en vervangen elementen."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Deze eigenschap specificeert de [inhoudsbreedte](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) van vakken die worden gegenereerd door block-level en [vervangen](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) elementen.

Deze eigenschap is niet van toepassing op niet-vervangen [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) elementen. De breedte van de boxen van een niet-vervangen inline‑element is die van de gerenderde inhoud erin (voordat enige relatieve offset van kinderen wordt toegepast). Onthoud dat inline‑boxen vloeien in [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). De breedte van line‑boxes wordt gegeven door hun [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), maar kan worden verkort door de aanwezigheid van [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

De breedte van de box van een vervangen element is [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) en kan worden geschaald door de user agent als de waarde van deze eigenschap anders is dan 'auto'.

De waarden hebben de volgende betekenissen:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Specificeert een vaste breedte.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Specificeert een breedte in procenten. Het percentage wordt berekend ten opzichte van de breedte van het gegenereerde box‑[containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - De breedte hangt af van de waarden van andere eigenschappen. Zie de onderstaande secties. Let op: Negatieve waarden voor ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) zijn ongeldig.

```java
public String Width { get; set; }
```

### Retourwaarde

breedte eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
