---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Denna egenskap påverkar den vertikala positioneringen inom en radbox för de boxar som genereras av ett inline‑nivåelement. Följande värden har endast betydelse i förhållande till ett föräldra‑inline‑nivåelement eller ett föräldra‑block‑nivåelement om det elementet genererar anonyma inline‑boxar; de har ingen effekt om ingen sådan förälder finns."
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Denna egenskap påverkar den vertikala positioneringen inom en radbox för de boxar som genereras av ett inline‑nivåelement. Följande värden har endast betydelse i förhållande till ett föräldra‑inline‑nivåelement eller ett föräldra‑block‑nivåelement om det elementet genererar [anonyma inline‑boxar](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); de har ingen effekt om ingen sådan förälder finns.

Obs. Värdena för denna egenskap har något olika betydelser i tabellkontext. Se avsnittet om [tabellhöjdsalgoritmer](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) för detaljer. baseline – Justera boxens baslinje med föräldra-boxens baslinje. Om boxen saknar en baslinje, justera boxens botten med förälderns baslinje. middle – Justera boxens vertikala mittpunkt med föräldra-boxens baslinje plus halva x‑höjden på föräldern. sub – Sänk boxens baslinje till rätt position för nedsänkta tecken i föräldra-boxen. (Detta värde påverkar inte teckenstorleken på elementets text.) super – Höj boxens baslinje till rätt position för upphöjda tecken i föräldra-boxen. (Detta värde påverkar inte teckenstorleken på elementets text.) text-top – Justera boxens topp med toppen av föräldraelementets teckensnitt. text-bottom – Justera boxens botten med botten av föräldraelementets teckensnitt. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' – Höj (positivt värde) eller sänk (negativt värde) boxen med detta avstånd (en procentsats av ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)-värdet). Värdet '0%' betyder samma som 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' – Höj (positivt värde) eller sänk (negativt värde) boxen med detta avstånd. Värdet '0cm' betyder samma som 'baseline'. top – Justera boxens topp med toppen av radboxen. bottom – Justera boxens botten med botten av radboxen.

```java
public String VerticalAlign { get; set; }
```

### Returvärde

vertical-align-egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
