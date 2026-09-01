---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties-egenskap. Denna egenskap specificerar huruvida innehållet i ett blocknivåelement klipps när det överskrider elementets låda som fungerar som ett innehållande block för innehållet. Värden har följande betydelser"
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Denna egenskap specificerar huruvida innehållet i ett blocknivåelement klipps när det överskrider elementets låda (som fungerar som ett innehållande block för innehållet). Värden har följande betydelser:

visible - Detta värde indikerar att innehållet inte klipps, d.v.s. det kan renderas utanför blocklådan. hidden - Detta värde indikerar att innehållet klipps och att ingen rullningsmekanism ska tillhandahållas för att visa innehållet utanför klippningsområdet; användare kommer inte att ha åtkomst till klippt innehåll. Storleken och formen på klippningsområdet specificeras av egenskapen ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip). scroll - Detta värde indikerar att innehållet klipps och att om användaragenten använder en rullningsmekanism som är synlig på skärmen (såsom en rullningslist eller en panorerare), så ska den mekanismen visas för en låda oavsett om något av dess innehåll är klippt. Detta undviker problem med att rullningslister dyker upp och försvinner i en dynamisk miljö. När detta värde anges och målmediet är 'print' eller 'projection', ska överskjutande innehåll skrivas ut. auto - Beteendet för värdet 'auto' beror på användaragenten, men bör leda till att en rullningsmekanism tillhandahålls för överskjutande lådor.

```java
public String Overflow { get; set; }
```

### Returvärde

overflow-egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
