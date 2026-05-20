---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Värden för denna egenskap har följande betydelser"
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Värden för denna egenskap har följande betydelser:

normal - Elementet öppnar inte en extra inbäddningsnivå i förhållande till den bidi‑algoritmen. För inline‑nivå element fungerar implicit omordning över elementgränser. embed - Om elementet är på inline‑nivå öppnar detta värde en extra inbäddningsnivå i förhållande till den bidi‑algoritmen. Riktningen för denna inbäddningsnivå anges av egenskapen ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) . Inuti elementet sker omordning implicit. Detta motsvarar att lägga till en LRE (U+202A; för 'direction: ltr') eller RLE (U+202B; för 'direction: rtl') i början av elementet och en PDF (U+202C) i slutet av elementet. bidi-override - Om elementet är på inline‑nivå eller ett block‑nivå element som endast innehåller inline‑nivå element skapar detta en överskrivning. Detta innebär att inuti elementet sker omordning strikt i sekvens enligt egenskapen ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) ; den implika delen av bidi‑algoritmen ignoreras. Detta motsvarar att lägga till en LRO (U+202D; för 'direction: ltr') eller RLO (U+202E; för 'direction: rtl') i början av elementet och en PDF (U+202C) i slutet av elementet.

```java
public String UnicodeBidi { get; set; }
```

### Returvärde

unicode-bidi egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
