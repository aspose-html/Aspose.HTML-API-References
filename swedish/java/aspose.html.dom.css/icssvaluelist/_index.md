---
title: "ICSSValueList gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSValueList gränssnitt. CSSValueList‑gränssnittet härstammar från CSSValue‑gränssnittet och tillhandahåller abstraktionen av en ordnad samling av CSS‑värden."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

CSSValueList‑gränssnittet härstammar från [`CSSValue`](../cssvalue/)‑gränssnittet och tillhandahåller abstraktionen av en ordnad samling av CSS‑värden.

Vissa egenskaper tillåter en tom lista i sin syntax. I så fall använder dessa egenskaper identifieraren none. Så en tom lista betyder att egenskapen har värdet none.

Objekten i CSSValueList är åtkomliga via ett heltalsindex, med början från 0.

```java
public interface ICSSValueList
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Denna metod används för att hämta ett CSSValue enligt ordinalt index. Ordningen i denna samling representerar ordningen av värdena i CSS‑stil‑egenskapen. Om index är större än eller lika med antalet värden i listan returneras null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) Läs‑endast‑egenskapen length för CSSValueList‑gränssnittet representerar antalet CSSValues i listan. Giltigt intervall för index är 0 till length‑1 inklusive. |

## Anmärkningar

Detta gränssnitt var en del av ett försök att skapa en typad CSS Object Model. Försöket har övergivits och de flesta webbläsare implementerar det inte.

För att uppnå ditt mål kan du använda:

den otippade [CSS Object Model](https://drafts.csswg.org/cssom/), brett stöd, eller den moderna [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), mindre stöd och anses experimentell.

### Se även

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
