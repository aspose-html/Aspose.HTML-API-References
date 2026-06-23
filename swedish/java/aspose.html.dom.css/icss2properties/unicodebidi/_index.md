---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Värden för denna egenskap har följande betydelser"
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Värden för denna egenskap har följande betydelser:

normal - Elementet öppnar inte en extra inbäddningsnivå i förhållande till den bidirektionella algoritmen. För inline‑nivåelement fungerar implicit omordning över elementgränser. embed - Om elementet är inline‑nivå öppnar detta värde en extra inbäddningsnivå i förhållande till den bidirektionella algoritmen. Riktningen för denna inbäddningsnivå anges av egenskapen ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). Inuti elementet sker omordning implicit. Detta motsvarar att lägga till en LRE (U+202A; för 'direction: ltr') eller RLE (U+202B; för 'direction: rtl') i början av elementet och en PDF (U+202C) i slutet av elementet. bidi-override - Om elementet är inline‑nivå eller ett block‑nivåelement som endast innehåller inline‑nivåelement skapar detta ett överskrivande. Detta innebär att inuti elementet sker omordning strikt i sekvens enligt egenskapen ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); den implicita delen av den bidirektionella algoritmen ignoreras. Detta motsvarar att lägga till en LRO (U+202D; för 'direction: ltr') eller RLO (U+202E; för 'direction: rtl') i början av elementet och en PDF (U+202C) i slutet av elementet.

```java
public String UnicodeBidi { get; set; }
```

### Returvärde

unicode-bidi egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
